<template>
<img :src="gift.url" :alt="gift.tag" class="img-fluid rounded selectable">
  <h2>
    {{ gift.tag }}
  </h2>
</template>


<script>
import { Gift } from '../models/Gift.js';

// export default {
//   // NOTE props allow us to pass down data from a parent component
//   props: {
//     movie: { type: Movie }
//   },
//   setup() {
//     return {};
//   },
// }

</script>


<style lang="scss" scoped></style>