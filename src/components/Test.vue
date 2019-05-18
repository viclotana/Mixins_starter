<template>
  <div> 
    <button v-on:click="clicked('you just clicked on button 1')">Button 1</button>
  </div>
</template>

<script>
export default {
  name: "Test",
  methods: {
    clicked(value) {
      alert(value);
    }
  }
};
</script>
