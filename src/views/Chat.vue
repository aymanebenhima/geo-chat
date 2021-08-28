<template>
  <div class="chat container">
      <h2>Username: {{ this.name }}</h2>
  </div>
</template>

<script>
export default {
    name: 'Chat',
    props: ['name'],
    data() {
        return {
            
        }
    },
}
</script>

<style>

</style>