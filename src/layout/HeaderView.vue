<template>
    <header class="header">
        <nav class="navbar navbar-expand-lg navbar-dark bg-transparent">
            <div class="container-fluid">
              <a class="navbar-brand" href="#"><img class="img-fluid" src="./../assets/images/logo.png" alt=""></a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav m-auto">
                  <li class="nav-item">
                    <router-link class="nav-link" aria-current="page" to="/">Dashboard</router-link>
                  </li>
                  <li class="nav-item">
                    <router-link class="nav-link" to="/swap">Swap</router-link>
                  </li>
                  <li class="nav-item">
                    <router-link class="nav-link" to="/liquidity">Liquidity</router-link>
                  </li>
                  <li class="nav-item">
                    <router-link class="nav-link" to="/pool">Pool</router-link>
                  </li>
                  <li class="nav-item">
                    <router-link class="nav-link" to="/stake">Stake</router-link>
                  </li>
                  <li class="nav-item">
                    <router-link class="nav-link" to="/lottery">Lottery</router-link>
                  </li>
                  <li class="nav-item">
                    <router-link class="nav-link" to="/charts">Charts</router-link>
                  </li>
                </ul>
                <div class="right">
                    <router-link to="" class="night-btn"><i class="fa-solid fa-moon"></i></router-link>
                    <router-link class="connect-wallet" to="">Connect wallet</router-link>
                </div>
              </div>
            </div>
        </nav>
    </header>
</template>
