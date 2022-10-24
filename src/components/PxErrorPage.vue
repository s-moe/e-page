<template>
  <div>
    <div></div>
    <h1>{{ status - code }}</h1>
    <h3>{{ message }}</h3>
  </div>
</template>
<script>
export default {
  name: "px-error-page",
  props: {
    statusCode: { type: Number },
    message: { type: String, default: "Uh-oh! There is an error" },
    detail: { type: String, default: "Default message for detail string" },
    icon: { type: String },
    actions: { type: Array },
  },
};
</script>
<style>
h1 {
  color: blue;
}
</style>