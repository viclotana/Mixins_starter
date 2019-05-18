<template>
  <div> 
    <button v-on:click="clicked('you just clicked on button 2')">Button 2</button>
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
