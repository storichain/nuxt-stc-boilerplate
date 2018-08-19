<template>
  <section>
    <div class="intro">
        <div class="logo_intro">
            <div class="sb"><img src="/images/logo_sb.png" alt="S"></div>
            <div class="st"><img src="/images/logo_txt.png" alt="Storichain"></div>
        </div>
    </div>

    <div class="footer">
        <p class="copy">copyright &copy; 2018 STORICHAIN ALL RIGHTS RESERVED</p>
        <ul class="cp_lk">
            <li><a href="#">Private policy</a></li>
            <li><a href="#">Terms of Platform</a></li>
            <li><a href="#">Advertise</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

