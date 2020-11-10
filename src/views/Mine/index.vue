<template>
  <div id="main">
    <Header title="我的"/>
    <Footer/>
  </div>
</template>

<script>
import Header from '@/components/Header'
import Footer from '@/components/Footer'
export default {
  name: 'Mine',
  data () {
    return {

    }
  },
  components: {
    Header,
    Footer
  }
}
</script>

<style>

</style>
