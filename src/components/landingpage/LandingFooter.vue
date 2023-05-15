<template>
  <nav class="navbar fixed-bottom navbar-dark bg-primary">
    <div class="picture-wrapper">
    </div>

    <div class="language-changer">
      <LanguageSwitcher/>
    </div>
  </nav>
</template>

<script>
import LanguageSwitcher from "../utils/LanguageSwitcher";

export default {
  name: 'LandingFooter',
  components: {
    LanguageSwitcher
  }
}
</script>

<style scoped>
.language-changer {
  position: relative;
  display: flex;
  vertical-align: center;
}

</style>