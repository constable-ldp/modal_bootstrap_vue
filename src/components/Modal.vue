<template>
  <div>
    <b-button @click="showModal">Open</b-button>
    <b-modal ref="my-modal">
        <h3>Modal!</h3>
    </b-modal>
  </div>
</template>

<script>
  export default {
    methods: {
      showModal() {
        this.$refs['my-modal'].show()
      }
    }
  }
</script>