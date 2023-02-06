<template>
  <div class="main-content">
    <div class="container">
      <div class="row">
        <div class="col-lg-4 col-md-12 mt-2">
          <div class="balance">
            <div class="d-flex align-items-center">
              <div class="w-50">
                <img src="./../assets/images/icon/smak.png" alt="smak">
                <h4 class="subtitle">Live price</h4>
                <p>$ 0.1 USD <span>-0.5%</span></p>
              </div>
              <div class="w-50">
                <img src="./../assets/images/icon/Wallet.png" alt="">
                <h4 class="subtitle">Balance</h4>
                <p>11,000,000.123 SMAK</p>
              </div>
            </div>
            <a href="" class="sign-out">Sign out</a>
          </div>
        </div>
        <div class="col-lg-4 col-md-12 mt-2">
          <div class="by-smak">
            <div class="d-flex align-items-center">
              <div class="w-50 market-cap">
                <p>Market cap </p>
                <h4 class="subtitle">300,00,000 USD</h4>
              </div>
              <div class="w-50 smak-burned">
                <p>SMAK burned</p>
                <h4 class="subtitle">300,00,000 USD</h4>
              </div>
            </div>
            <div class="d-flex align-items-center">
              <div class="w-50 max-cap">
                <p>Max supply cap</p>
                <h4 class="subtitle">839,000,000 SMAK</h4>
              </div>
              <div class="w-50 smak-btn">
                <router-link to=""><img src="./../assets/images/icon.png" alt="">Buy Smak</router-link>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-12 mt-2">
          <div class="analytics">
            <div class="d-flex align-items-center">
              <h4 class="me-auto">TOTAL TVL <span class="highlight">$ 50.34M </span></h4>
              <router-link class="analytic-btn" to="">Go to analytics</router-link>
            </div>
            <div class="d-flex align-items-center btn-group">
              <router-link class="active" to="">1d</router-link>
              <router-link to="">1w</router-link>
              <router-link to="">1m</router-link>
            </div>
            <img src="./../assets/images/analytics.png" alt="analytics">
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

</script>
