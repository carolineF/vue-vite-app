<template>
  <p>Mouse: {{x}}x{{y}}</p>
</template>

<script>
import { useMouse } from '@vueuse/core'
export default {
  name: 'App',
  setup() {
    return useMouse()
  }
}
</script>