<template>
  <svg
    width="32px"
    height="32px"
    viewBox="0 0 32 32"
    version="1.1"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
      <g :fill="checked ? color : '#FFFFFF'">
        <path
          d="M27,28 L11.414,28 L28,11.414 L28,27 C28,27.553 27.553,28 27,28 Z M23,4 L28,4 L28,8.586 L8.586,28 L4,28 L4,23 C4,22.447 4.447,22 5,22 L10,22 L10,17 C10,16.447 10.447,16 11,16 L16,16 L16,11 C16,10.447 16.447,10 17,10 L22,10 L22,5 C22,4.447 22.447,4 23,4 Z"
        />
      </g>
    </g>
  </svg>
</template>

<script>
export default {
  name: "Staircase",
  props: {
    checked: Boolean,
    color: String
  }
};
</script>
