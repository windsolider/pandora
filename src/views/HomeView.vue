<template>
  <div class="container-fluid d-flex flex-row position-relative ">
    <ul class="list-group sidebar h-100 position-relative">
      <li class="list-group-item">An item</li>
      <li class="list-group-item">A second item</li>
      <li class="list-group-item">A third item</li>
      <li class="list-group-item">A fourth item</li>
      <li class="list-group-item">And a fifth one</li>
    </ul>
    <div class="content h-100">
      <div class="dialog">
        <ul class="list-group sidebar h-100 position-relative">
          <li class="list-group-item">An item</li>
          <li class="list-group-item">A second item</li>
          <li class="list-group-item">A third item</li>
          <li class="list-group-item">A fourth item</li>
          <li class="list-group-item">And a fifth one</li>
        </ul>
      </div>
      <div class="">
        <div class="input-group">
          <textarea class="form-control" aria-label="With textarea"></textarea>
          <button type="button" class="btn btn-light">发送</button>
        </div>
      </div>
    </div>
  </div>
</template>
<script setup lang="ts">

</script>
<style scoped>
.sidebar {
  width: 240px;
  background-color:black;
}
</style>
