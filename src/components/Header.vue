<template>
  <div class="header">
    <h1 class="logo">Todo App</h1>
  </div>
</template> 


<script>
export default {
  name: 'headerArea',
}
</script>


<style>
.header {
  background-color: rgb(255, 81, 0);
  height: 60px;
  width: 100%;
  position: absolute;
}

.logo {
  display: flex;
  flex-direction: column;
  justify-content: center;
  text-align: end;
  height: 100%;
  color: #faf8f8;
  padding: 0 30px;
}
</style>