<script lang="ts">
export default {
  data() {
    return {
      name: "Hello Options Component",
    };
  },
  methods: {
    showName() {
      console.log(this.name);
    },
  },
};
</script>

<template>
  <div>
    <h1>{{ name }}</h1>
    <button
      @click="showName"
      class="px-4 py-2 bg-green-500 text-white rounded hover:bg-green-600"
    >
      Show Name
    </button>
  </div>
</template>
