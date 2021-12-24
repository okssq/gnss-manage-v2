<template>
  <div class="layout-header">
    <q-btn icon="webhook" flat color="white" no-caps label="Management System" size="16px">

    </q-btn>

    <q-btn round flat icon="person_outline" color="white">
      <q-menu>
        <q-list padding>
          <q-item clickable v-close-popup>
            <q-item-section>用户管理</q-item-section>
          </q-item>
          <q-item clickable v-close-popup>
            <q-item-section>退出</q-item-section>
          </q-item>
        </q-list>
      </q-menu>
    </q-btn>

  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.layout-header{
  z-index: 11;
  height: 64px;
  background-color: rgb(30 136 229) !important;
  border-color: rgb(30 136 229) !important;
  box-shadow: 0 2px 4px -1px rgb(0 0 0 / 20%), 0 4px 5px 0 rgb(0 0 0 / 14%), 0 1px 10px 0 rgb(0 0 0 / 12%);
  display: flex;
  flex-wrap: nowrap;
  overflow: hidden;
  justify-content: space-between;
  align-items: center;
  padding: 0 16px 0 4px;
}
</style>