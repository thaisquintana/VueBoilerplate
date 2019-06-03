<template>
  <div class="all-receipts">
    <div class="receipts">
      <div class="receipts-buyer">
        <div class="buyer-header">
          <h4>Buyer</h4>
          <span class="place">Heineken Reunion Sarl</span>
          <span class="address">Des Benjoins, Rue 2, Saint-Denis</span>
          <span class="neighborhood">1202 RE, Reunion</span>
        </div>
        <hr>
        <div class="buyer-details">
          <div class="buyer-category">
            <ul>
              <li>Code</li>
              <li>Operating Name</li>
              <li>Function</li>
              <li class="trade">Trade Register Number</li>
              <li>VAT Number</li>
              <li>IBAN Number</li>
              <li>BIC Code</li>
            </ul>
          </div>
          <div class="buyer-types">
            <ul>
              <li>HNKR</li>
              <li>HNK Reunion</li>
              <li>
                Local Operations, Manufacturing, Sales,
                Marketing
              </li>
              <li>904199460</li>
              <li>1202317918B58</li>
              <li>RE40INGB4854154986</li>
              <li>INGBRE3A</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="receipts-seller">
        <div class="seller-header">
          <h4>Seller</h4>
          <span class="place">Heineken Belgium</span>
          <span class="address">Rue Condorcet 163, Moe</span>
          <span class="neighborhood">1264 BE, Belgium</span>
        </div>
        <hr>
        <div class="seller-details">
          <div class="seller-category">
            <ul>
              <li>Code</li>
              <li>Operating Name</li>
              <li>Function</li>
              <li class="trade">Trade Register Number</li>
              <li>VAT Number</li>
              <li>IBAN Number</li>
              <li>BIC Code</li>
            </ul>
          </div>
          <div class="seller-types">
            <ul>
              <li>HNKR</li>
              <li>Heineken Belgium</li>
              <li>
                Local Operations, Manufacturing, Sales,
                Marketing
              </li>
              <li>570785970</li>
              <li>1635388252B59</li>
              <li>BE19INGB1265897894</li>
              <li>INGBFR7A</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="wallet fadeInWallet">
      <img :src="require('../assets/images/wallet.svg')">
    </div>
  </div>
</template>
