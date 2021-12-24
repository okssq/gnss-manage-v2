<template>
<div class="fullscreen overflow-hidden column no-wrap">
  <layout-header />
  <div class="flex1 overflow-hidden row no-wrap">
    <layout-side />
    <div class="flex1 overflow-hidden column no-wrap layout-main">
      <layout-crumbs />
      <div class="flex1 overflow-hidden">

      </div>
    </div>
  </div>
</div>
</template>

<script>
import LayoutHeader from './header.vue'
import LayoutSide from './side.vue'
import LayoutCrumbs from './crumbs.vue'
export default {
  components: {
    LayoutHeader,
    LayoutSide,
    LayoutCrumbs
  },
}
</script>

<style scoped>
.layout-main{
  background-color: rgb(238,245,249);
}
</style>