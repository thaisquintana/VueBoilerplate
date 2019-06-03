<template>
  <div>
    <Header/>
    <div class="welcome">
      <div class="welcome-title fadeOut">
        <p>
          Show me
          <b>Invoices</b> of
          <b>Heineken Belgium</b>
        </p>
        <span>
          from
          <b>January</b> to
          <b>April</b> of
          <b>2018</b>
        </span>
      </div>
      <div class="welcome-graphic zoomOut">
        <img :src="require('../assets/images/detail.svg')">
      </div>
    </div>
    <audio id="audio" autoplay :src="require('../assets/audio/el-invoices-audio.mp3')"></audio>
    <Loading/>
    <CardsInvoice/>
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
import CardsInvoice from "@/components/CardsInvoice.vue";
import Header from "@/components/Header.vue";
import Loading from "@/components/Loading.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "home",
  components: {
    CardsInvoice,
    Header,
    Footer,
    Loading
  },
  mounted: function() {
    var playVoice = audio.play();

    if (playVoice !== undefined) {
      playVoice
        .then(_ => {
          audio.play();
        })
        .catch(error => {
          console.log(error);
        });
    }
  }
};
</script>
