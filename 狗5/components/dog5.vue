<template>
  <tr>
    <td>
      <input type="number" v-model.number="obj['count']"/>
    </td>
    <td>
      <span>{{ obj["goodsName"] }}</span>
    </td>
    <td>
      <span v-show="obj['count'] == 0">εεδΊ!!!</span>
    </td>
  </tr>
</template>

<script>
export default {
    props: ["obj"]
};
</script>

<style>
</style>
