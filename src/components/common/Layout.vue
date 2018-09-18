<template>
  <div class="">
    <div class="header">header</div>
    <div class="content">
      <keep-alive>
        <router-view></router-view>
      </keep-alive>
    </div>
    <div class="footer">footer</div>
  </div>
</template>

<style lang="scss" scoped>
.content {
  background-color: lightblue;
}
</style>
<style>
@import '../../assets/style/common/reset';
</style>

<script>
export default {
  components: {},
  data () {
    return {}
  },
  props: {},
  watch: {},
  methods: {},
  filters: {},
  computed: {},
  created () { },
  mounted () { },
  destroyed () { }
}
</script>
