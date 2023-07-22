<template>
  <div id="app">
    <calendar-week/>
    <calendar-entry/>
  </div>
</template>

<script>
import CalendarWeek from './components/CalendarWeek.vue';
import CalendarEntry from './components/CalendarEntry.vue';

export default {
  name: 'App',
  components: {
    "calendar-week": CalendarWeek,
    "calendar-entry": CalendarEntry
  }
}
</script>

<style lang="scss">
html, body, #app {
  height: 100%;
}
</style>

<style lang="scss" scoped>
#app {
  background: #6e6e6e;
  display: flex;
  flex-direction: column;
  align-items: center;
  -webkit-align-items: center;
  justify-content: center;
  -webkit-justify-content: center;
}
</style>
