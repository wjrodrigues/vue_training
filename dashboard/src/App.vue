<template>
  <modal-factory />
  <RouterView />
</template>

<script>
import ModalFactory from './components/Modals/Factory.vue'

export default {
  components: { ModalFactory }
}
</script>