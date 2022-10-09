<template>
  <p class="clearfix mb-0">
    <span class="float-md-left d-none d-md-block d-md-inline-block mt-25">
      <b-link
        class="ml-25 font-weight-bolder"
        href="https://t.me/aytapapina"
        target="_blank"
      >Report a bug</b-link>
    </span>
  </p>
</template>

<script>
import { BLink, VBPopover } from 'bootstrap-vue'
import Ripple from 'vue-ripple-directive'

export default {
  name: 'AppFooter',
  components: {
    BLink,
  },
  directives: {
    'b-popover': VBPopover,
    Ripple,
  },
}
</script>
