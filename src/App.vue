<script>
import AppHeader from './components/AppHeader.vue';
import mainPage from './components/mainPage.vue';
import AppMarketing from './components/AppMarketing.vue';
import TipsTricks from './components/TipsTricks.vue';
import AppFeature from './components/AppFeature.vue';
import OurTest from './components/OurTest.vue';
import AppPosts from './components/AppPosts.vue';
import ContactTeam from './components/ContactTeam.vue';
import AppFooter from './components/AppFooter.vue';




export default {
  data(){
    return {
        
    }
  },

  components: {AppHeader, mainPage, AppMarketing, TipsTricks, AppFeature, OurTest, AppPosts, ContactTeam, AppFooter },
}
</script>

<template>
  <AppHeader />
  <mainPage />
  <AppMarketing />
  <TipsTricks />
  <AppFeature />
  <OurTest />
  <AppPosts />
  <ContactTeam />
  <AppFooter />
</template>

<style lang="scss">
@use "./style/general.scss";
@import "@fortawesome/fontawesome-free/css/all.css";
</style>
