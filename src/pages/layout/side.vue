<template>
  <q-scroll-area class="layout-side">
    <q-list >
      <q-expansion-item
        expand-separator
        icon="perm_identity"
        label="管理工具"
      >
        <q-list >
          <q-item clickable v-ripple>
            <q-item-section>
              <q-item-label>部标终端管理</q-item-label>
            </q-item-section>
          </q-item>
          <q-item clickable v-ripple>
            <q-item-section>
              <q-item-label>主动安全终端管理</q-item-label>
            </q-item-section>
          </q-item>
          <q-item clickable v-ripple>
            <q-item-section>车辆列表</q-item-section>
          </q-item>
        </q-list>
      </q-expansion-item>
      <q-expansion-item
        expand-separator
        icon="perm_identity"
        label="主动安全"
      >
        <q-list >
          <q-item clickable v-ripple>
            <q-item-section>
              <q-item-label>报警中心</q-item-label>
            </q-item-section>
          </q-item>
          <q-item clickable v-ripple>
            <q-item-section>
              <q-item-label>AI报警设置</q-item-label>
            </q-item-section>
          </q-item>
        </q-list>
      </q-expansion-item>
      <q-expansion-item
        expand-separator
        icon="perm_identity"
        label="系统中心"
      >
        <q-list >
          <q-item clickable v-ripple>
            <q-item-section>
              <q-item-label>公司管理</q-item-label>
            </q-item-section>
          </q-item>
          <q-item clickable v-ripple>
            <q-item-section>
              <q-item-label>公司配置管理</q-item-label>
            </q-item-section>
          </q-item>
          <q-item clickable v-ripple>
            <q-item-section>用户管理</q-item-section>
          </q-item>
          <q-item clickable v-ripple>
            <q-item-section>菜单管理</q-item-section>
          </q-item>
          <q-item clickable v-ripple>
            <q-item-section>公告管理</q-item-section>
          </q-item>
          <q-item clickable v-ripple>
            <q-item-section>版本管理</q-item-section>
          </q-item>
        </q-list>
      </q-expansion-item>
    </q-list>
  </q-scroll-area>
</template>

<script>
export default {
  name: "side"
}
</script>

<style scoped>
.layout-side{
  z-index: 10;
  width: 256px;
  padding: 8px 15px;
  background-color: #ffffff;
  height: 100%;
  box-shadow: 1px 0 20px rgb(0 0 0 / 8%);
}
</style>