<template>
    <th> <Button v-bind:class="{'white': !clicked, 'blue': clicked}" v-on:click="!clicked" ></Button></th> 
</template>
<script setup>
    export default {
        data: {
    clicked: false,
        }
    }
</script>
<style scoped>
.white {
  background-color: white;
  width: 200px;
  height: 200px;
}
.blue {
  width: 200px;
  height: 200px;
  background-color: blue;
}
</style>
