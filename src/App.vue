<script setup lang="ts">
onLaunch(() => {
  console.log('onLaunch')
})
onShow(() => {
  console.log('onShow')
})
onHide(() => {
  console.log('onHide')
})
</script>
<style lang="scss">
// #ifndef APP-NVUE
@import 'uview-ui/index.scss';
@import '@/styles/color-ui.css';
@import '@/styles/index.scss';
// #endif
</style>
