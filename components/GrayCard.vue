<template>
  <div class="container-card">
    <div class="row">
      <div class="col"><p>{{ card.itemText }}</p></div>
    </div>
  </div>
</template>

<script>
export default {
  props: ["card"],
};
</script>

<style scoped>
.row {
  height: 30px;
  background-color: #ebebeb;
  color: #444444;
  font-size: 14px;
  text-align: center;
  margin: 5px;
  vertical-align: inherit;
  padding: 6px;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>

