<template>
    <div class="row">
      <div class="col-md-6">
        <div class="card flex-md-row mb-4 box-shadow h-md-250">
          <div class="card-body d-flex flex-column align-items-start">
            <strong class="d-inline-block mb-2 text-primary">Dell</strong>
              <h5 class="mb-0">
                <a class="text-dark">Gaming</a>
              </h5>
                <div class="mb-1 text-muted">Alienware M15</div>
                <p class="card-text mb-auto">Intel i9-8950HK</p>
                <p class="card-text mb-auto">NVIDIA RTX 2080</p>
                <p class="card-text mb-auto">32GB DDR4-2666MHz</p>
                <div class="btn-group" role="button">
                <button type="button" class="btn btn-outline-info" @click="add"><i class="fas fa-cart-arrow-down"></i></button>
                <button type="button" class="btn btn-outline-info"><i class="fas fa-angle-double-right"></i></button>
                <button type="button" class="btn btn-outline-info" @click="clear"><i class="far fa-trash-alt"></i></button>
                </div>
            </div>
            <img class="card-img-right flex-auto d-none d-md-block" style="width: 250px; height: 250px;" src="./1023.jpg">
          </div>
      </div>
     </div>
</template>

<script>
import store from "@/store.js";

export default {
    props: {
        add: Function
    },
    methods: {
        
    },
}
</script>

<style>

</style>
