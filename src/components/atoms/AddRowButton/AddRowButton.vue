<template>
  <Button>
    <svg
    width="32px"
    height="32px"
    viewBox="0 0 32 32"
    version="1.1"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
      <g id="add-row">
        <circle id="button-background" fill="#D0D4DA" cx="16" cy="16" r="16" />
        <polygon
          id="plus"
          fill="#FFFFFF"
          points="
            20.52
            16.84
            17.04
            16.84
            17.04
            20.24
            14.46
            20.24
            14.46
            16.84
            11
            16.84
            11
            14.4
            14.46
            14.4
            14.46
            11
            17.04
            11
            17.04
            14.4
            20.52
            14.4
          "
        />
      </g>
    </g>
   </svg>
  </Button>
</template>

<script>
import Button from '../Button/Button.vue'

export default {
  name: 'AddRowButton',
  components: {
    Button
  }
}
</script>
