<template>
    <div> I'm a {{text}} view</div>
</template>

<script>
import { ref } from 'vue'

export default {
  setup () {
    const text = ref('sync')

    return { text }
  }
}
</script>
