<template>
  <svg
    id="bold"
    enable-background="new 0 0 32 32"
    viewBox="0 0 32 32"
    :width="size"
    :height="size"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="m26 32h-20c-3.314 0-6-2.686-6-6v-20c0-3.314 2.686-6 6-6h20c3.314 0 6 2.686 6 6v20c0 3.314-2.686 6-6 6z"
      fill="#ffe6e2"
    />
    <path
      d="m16 20c-.205 0-.401-.084-.542-.232l-5.25-5.5c-.455-.476-.117-1.268.542-1.268h2.75v-5.75c0-.689.561-1.25 1.25-1.25h2.5c.689 0 1.25.561 1.25 1.25v5.75h2.75c.659 0 .997.792.542 1.268l-5.25 5.5c-.141.148-.337.232-.542.232z"
      fill="#fc573b"
    />
    <path
      d="m26.25 26h-20.5c-.965 0-1.75-.785-1.75-1.75v-.5c0-.965.785-1.75 1.75-1.75h20.5c.965 0 1.75.785 1.75 1.75v.5c0 .965-.785 1.75-1.75 1.75z"
      fill="#fd907e"
    />
  </svg>
</template>

<script>
export default {
    props: {
        size: {
            type: [String, Number],
            default: "50"
        },
    }
}
</script>

<style></style>
