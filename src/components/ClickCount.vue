<template>
  <div class="count">
    <h3>Installed CLI Plugins</h3>
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>
