<template>
  <div>
    <h1>my wizard</h1>
    <form-wizard>
      <wizard-step> step 1 </wizard-step>
      <wizard-step> step 2 </wizard-step>
      <wizard-step> step 3 </wizard-step>
    </form-wizard>
  </div>
</template>

<script>
export default {
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
