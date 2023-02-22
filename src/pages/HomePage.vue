<template>
<div class="container-fluid">
  <div class="row">
    <div class="col-12">
      <form @submit.prevent="">
          <div class="input-group mb-3 me-3">
            <input v-model="editable.query" required type="text" class="form-control" placeholder="New Gift"
              aria-label="New Gift" aria-describedby="button-addon2">
            <button class="btn btn-outline-secondary" type="submit" id="button-addon2">
              <i class="">!</i>
            </button>
          </div>
        </form>
    </div>
  </div>
  <div class="row">
          <div v-for="giftForTheVFor in gifts" key: giftForTheVFor.id class="col-md-3 p-4">

      </div>
  </div>
</div>
</template>

<script>

import { AppState } from "../AppState.js";


export default {
  setup() {
    return {}
  }
}
</script>

<style scoped lang="scss">
.home {
  display: grid;
  height: 80vh;
  place-content: center;
  text-align: center;
  user-select: none;

  .home-card {
    width: 50vw;

    >img {
      height: 200px;
      max-width: 200px;
      width: 100%;
      object-fit: contain;
      object-position: center;
    }
  }
}
</style>
