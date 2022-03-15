<template>
  <div class="home">
    <header id="header" class="pt-2">
      <Navbar />
      <Hero />
    </header>
    <InfoPanel />
    <TrustedCompany />
    <WelcomeKevins />
    <Counter />
    <Service />
    <GetFreeTrial />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue';
import Hero from '@/components/Hero.vue';
import InfoPanel from '@/components/InfoPanel.vue';
import TrustedCompany from '@/components/TrustedCompany.vue';
import WelcomeKevins from '@/components/WelcomeKevins.vue';
import Counter from '@/components/Counter.vue';
import Service from '@/components/Service.vue';
import GetFreeTrial from '@/components/GetFreeTrial.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'Home',
  components: {
    Navbar,
    Hero,
    InfoPanel,
    TrustedCompany,
    WelcomeKevins,
    Counter,
    Service,
    GetFreeTrial,
    Footer,
  },
};
</script>
