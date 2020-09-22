<template>
    <div> I'm an {{text}} view</div>
</template>

<script>
import { ref } from 'vue'

export default {
  async setup () {
    const text = ref('async')

    return { text }
  }
}
</script>
