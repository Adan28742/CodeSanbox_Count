<template>
  <main>
    <div>
      <h4>El numero actual es ...</h4>
      <h1>{{ count }}</h1>
      <button>+</button>
      <button>-</button>
    </div>
  </main>
</template>

<script>
export default {
  name: "counterItem",
  data() {
    return {
      count: 0,
    };
  },
};
</script>