<template>
  <component :is="name" v-bind="$props"/>
</template>

<script>
import Loading from './Loading.vue'

export default {
  name: "index-icon",
  components: { Loading },
  props: {
    name: { type: String, required: true }
  }
}
</script>
