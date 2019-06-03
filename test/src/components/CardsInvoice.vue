<template>
  <div class="cards fadeOutUp">
    <ul class="cards-list persist">
      <li class="cards-item first">
        <div class="cards-item__header">
          <div class="cards-item__header-title">
            <div class="logo">
              <img :src="require('../assets/images/logo-heineken.png')">
            </div>
            <div class="pill-alert">Unpaid</div>
          </div>
          <div class="cards-item__header-subtitle">
            <div class="invoice">
              <h4>Invoice</h4>
              <span>H3110017</span>
            </div>
            <div class="amount">
              <h4>Total amount</h4>
              <span>
                <label>&euro;</label> 204
              </span>
            </div>
          </div>
        </div>
        <div class="cards-item__body">
          <div class="category">
            <div class="buyer">
              <h4>Buyer Name</h4>
              <span>Heineken Reunion Sarl</span>
            </div>
            <div class="seller">
              <h4>Seller Name</h4>
              <span>Heineken Belgium</span>
            </div>
          </div>
          <div class="detail">
            <div class="start">
              <h4>Started</h4>
              <span>14 Feb 2018</span>
            </div>
            <div class="address">
              <h4>Blockchain Address</h4>
              <span class="spacing">0x4E5748…c81868F6</span>
            </div>
          </div>
        </div>
      </li>
      <li class="cards-item second">
        <div class="cards-item__header">
          <div class="cards-item__header-title">
            <div class="logo">
              <img :src="require('../assets/images/logo-heineken.png')">
            </div>
            <div class="pill-alert">Unpaid</div>
          </div>
          <div class="cards-item__header-subtitle">
            <div class="invoice">
              <h4>Invoice</h4>
              <span>H3110017</span>
            </div>
            <div class="amount">
              <h4>Total amount</h4>
              <span>
                <label>&euro;</label> 204
              </span>
            </div>
          </div>
        </div>
        <div class="cards-item__body">
          <div class="category">
            <div class="buyer">
              <h4>Buyer Name</h4>
              <span>Heineken Reunion Sarl</span>
            </div>
            <div class="seller">
              <h4>Seller Name</h4>
              <span>Heineken Belgium</span>
            </div>
          </div>
          <div class="detail">
            <div class="start">
              <h4>Started</h4>
              <span>14 Feb 2018</span>
            </div>
            <div class="address">
              <h4>Blockchain Address</h4>
              <span class="spacing">0x4E5748…c81868F6</span>
            </div>
          </div>
        </div>
      </li>
      <li class="cards-item third">
        <div class="cards-item__header">
          <div class="cards-item__header-title">
            <div class="logo">
              <img :src="require('../assets/images/logo-heineken.png')">
            </div>
            <div class="pill-alert">Unpaid</div>
          </div>
          <div class="cards-item__header-subtitle">
            <div class="invoice">
              <h4>Invoice</h4>
              <span>H3110017</span>
            </div>
            <div class="amount">
              <h4>Total amount</h4>
              <span>
                <label>&euro;</label> 204
              </span>
            </div>
          </div>
        </div>
        <div class="cards-item__body">
          <div class="category">
            <div class="buyer">
              <h4>Buyer Name</h4>
              <span>Heineken Reunion Sarl</span>
            </div>
            <div class="seller">
              <h4>Seller Name</h4>
              <span>Heineken Belgium</span>
            </div>
          </div>
          <div class="detail">
            <div class="start">
              <h4>Started</h4>
              <span>14 Feb 2018</span>
            </div>
            <div class="address">
              <h4>Blockchain Address</h4>
              <span class="spacing">0x4E5748…c81868F6</span>
            </div>
          </div>
        </div>
      </li>
      <li class="cards-item forth">
        <div class="cards-item__header">
          <div class="cards-item__header-title">
            <div class="logo">
              <img :src="require('../assets/images/logo-heineken.png')">
            </div>
            <div class="pill-alert">Unpaid</div>
          </div>
          <div class="cards-item__header-subtitle">
            <div class="invoice">
              <h4>Invoice</h4>
              <span>H3110017</span>
            </div>
            <div class="amount">
              <h4>Total amount</h4>
              <span>
                <label>&euro;</label> 204
              </span>
            </div>
          </div>
        </div>
        <div class="cards-item__body">
          <div class="category">
            <div class="buyer">
              <h4>Buyer Name</h4>
              <span>Heineken Reunion Sarl</span>
            </div>
            <div class="seller">
              <h4>Seller Name</h4>
              <span>Heineken Belgium</span>
            </div>
          </div>
          <div class="detail">
            <div class="start">
              <h4>Started</h4>
              <span>14 Feb 2018</span>
            </div>
            <div class="address">
              <h4>Blockchain Address</h4>
              <span class="spacing">0x4E5748…c81868F6</span>
            </div>
          </div>
        </div>
      </li>
    </ul>
    <button class="button-receipts" v-on:click="seen = !seen"></button>
    <Receipts v-if="seen"/>
  </div>
</template>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<script>
import Receipts from "@/components/Receipts.vue";

export default {
  name: "CardsInvoice",
  components: {
    Receipts
  },
  data: () => {
    return {
      seen: false
    };
  }
};
</script>
