<template>
    <div class="col-md-2 card">
        <slot>

        </slot>
    </div>
</template>

<script>
export default {
    data() {
      return {
        product : {
            title : null,
            count : null,
            price : null,
            selectedImage: null
        }
      }
    },
}
</script>