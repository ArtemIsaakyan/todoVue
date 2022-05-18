<template>
  <headerArea />
  <div class="block">
    <menuList />
    <workArea />
  </div>
</template>

<script>
import menuList from './components/MenuTodo.vue'
import workArea from './components/WorkArea.vue'
import headerArea from './components/Header.vue'

export default {
  name: 'App',
  components: {
    menuList,
    workArea,
    headerArea,
  }
}
</script>

<style>
*,
*::before,
*::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}

.block {
  display: flex;
}
</style>
