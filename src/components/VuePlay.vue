<template>
  <div id="print">
    <button v-on:click="count++">
      You clicked me {{ count }} times.
    </button>
  </div>
</template>

<script>
export default {
  name: 'VuePlay',
  data() {
    return {
      count: 0
    }
  }
}
</script>
