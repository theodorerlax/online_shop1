<template>
  <div class="v-main-wrapper">
    <keep-alive>
      <router-view></router-view>
    </keep-alive>
  </div>

</template>

<script>
  export default {
    name:"v-main-wrapper",
    components: {},
    props: {},
    data(){
      return {
        title: 'Main wrapper'
      }
    },
    computed: {},
    methods: {},
    watch: {},
    mounted() {}
  }
</script>

<style>
.v-main-wrapper{
  max-width: 100%;
  margin: 0 auto;
}
</style>