<template>
  <div>
    <Nav/>
    <Jumbotron />
    <Deffinition />
    <div class="test">
      <Testimonial />
      <PovandResource />
      <HelpandTips />
      <YouAllSet />
      <Footer class="footer" />
    </div>
  </div>
</template>

<script>
import Nav from '@/components/Nav'
import Jumbotron from '@/components/Home/Jumbotron'
import Deffinition from '@/components/Home/Deffinition'
import Testimonial from '@/components/Home/Testimonial'
import PovandResource from '@/components/Home/PovandResource'
import HelpandTips from '@/components/Home/HelpandTips'
import YouAllSet from '@/components/Home/YouAllSet'
import Footer from '@/components/Footer'

export default {
  components: {
    Nav,
    Jumbotron,
    Deffinition,
    Testimonial,
    PovandResource,
    HelpandTips,
    YouAllSet,
    Footer
  }
}
</script>

<style>

.test {
  background-color: black;
  height: 1488px;
  width: 100%;
  position: absolute;
}

</style>
