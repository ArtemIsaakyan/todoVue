<template>
  <div class="menu-list">
    <ul class="menu-items">
      <li class="menu-item">First</li>
      <li class="menu-item">Second</li>
      <li class="menu-item">First</li>
      <li class="menu-item">Second</li>
      <li class="menu-item">First</li>
    </ul>
    <button class="add-btn">Add new</button>
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
  flex-direction: column;
  justify-content: space-between;
  height: 100vh;
  width: 25%;
  padding: 75px 15px 15px 15px;
  background-color: rgb(248, 247, 247);
}

.menu-items {
  width: 100%;
  list-style: none;
  overflow: auto;
}

.menu-item {
  font-size: 20px;
  margin: 0 0 10px 0;
}

.add-btn {
  margin-top: 37px;
}
</style>