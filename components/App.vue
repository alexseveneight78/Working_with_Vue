<template>
  <div>
    <p>The name of header is : {{ header }}</p>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      header: "Working with assembling Vue Components"
    };
  }
};
</script>

<style scoped>
p {
  width: 30%;
  background-color: lightgreen;
  padding: 5px 20px;
  border: 1px dashed green;
  border-radius: 0% 75% 0% 75%;
}
</style>
