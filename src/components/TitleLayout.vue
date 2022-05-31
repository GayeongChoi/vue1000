<template>
  <section className="cont__title">
    <div className="container">
      <strong> {{ name1 }} </strong>
      <em> {{ name2 }}</em>
    </div>
  </section>
</template>

<script>
export default {
  props: {
    name1: String,
    name2: String,
  },
};
</script>
