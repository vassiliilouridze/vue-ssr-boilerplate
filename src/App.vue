<template>
  <div id="app">
    <header class="header">
      <nav class="inner">
        <router-link to="/">Home</router-link>
        <router-link to="/inspire">Inspire</router-link>
      </nav>
    </header>
    <transition name="fade" mode="out-in">
      <router-view class="view"></router-view>
    </transition>
  </div>
</template>

<script>
  import Meta from './mixins/meta'

  export default {
    mixins: [Meta],

    data () {
      return {
        foo: 'test'
      }
    }
  }
</script>

<style lang="stylus">

</style>