<template>
  <div class="gray-card">
    <p>{{ card.itemText }}</p>
  </div>
</template>

<script>
export default {
  props: ["card"],
};
</script>

<style scoped>
.gray-card {
  height: 26px;
  background-color: #ebebeb;
  color: #444444;
  font-size: 14px;
  text-align: center;
  margin-right: 8px;
  margin-bottom: 8px;
  padding: 6px;
  display: flex;
  align-items: center;
  justify-content: center;
}
p {
  display: block;
  margin-block-start: 1em;
  margin-block-end: 1em;
  margin-inline-start: 0px;
  margin-inline-end: 0px;
}
</style>
