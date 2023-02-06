<template>
  <div>
    <Main firstName="Jewel" lastName="Eni" age="20" hobbies="codding, reading, listening to music"/>
    <Main firstName="Chisom" lastName="Akubo" age="21" hobbies="sewing, gyming"/>
    <Main firstName="Tamuno" lastName="Omubo" age="22" hobbies="reading"/>
  </div>

</template>

<script>
import Main from './components/Main.vue'
export default {
  components: {
    Main,
  },
};
</script>

<style scoped></style>
