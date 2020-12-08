<template>
  <button class="button" type="submit"><slot /></button>
</template>

<script>
export default {
  name: 'MyButton',
};
</script>
<style scoped lang="scss">
.button {
  background: #333;
  color: #fff;
  border: 1px solid #ccc;
  padding: 10px 10px;
  border-radius: 4px;
}
</style>
