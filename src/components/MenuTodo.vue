<template>
  <div class="menu-list">
    <ul class="menu-items">
      <li class="menu-item">First</li>
      <li class="menu-item">Second</li>
    </ul>
  </div>
</template> 


<script>
export default {
  name: 'menuList',
}
</script>

<style>
.menu-list {
  display: flex;
  height: 100vh;
  width: 30%;
  padding: 75px 15px 0 15px;
  background-color: rgb(248, 247, 247);
}

.menu-items {
  width: 100%;
  list-style: none;
}

.menu-item {
  font-size: 20px;
  margin-bottom: 10px;
}
</style>