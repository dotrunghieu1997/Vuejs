<template>
        <!--left menu-->
        <div id="leftside" class="left-side col-md-3 col-xs-12">
          <div class="card">
            <img class="card-img-top rounded-circle" src="./1023.jpg">
            <div class="card-body">
              <h5 class="card-title" style="text-align: center">GO  <i class="fas fa-laptop"></i>  Shop</h5>
              <ul class="list-group list-group-flush">
            <div class="btn-group" role="button">
              <button type="button" class="btn btn-outline-secondary" @click="btnphone">Phone</button>
              <button type="button" class="btn btn-outline-secondary" @click="btnlap">Laptop</button>
            </div>
            <div class="row">
                <div class="col">
                  <div class="list-group" id="list-tab" role="tablist">
                    <a class="list-group-item list-group-item-action active" id="list-home-list" data-toggle="list" href="#list-home" role="tab" aria-controls="Dell">Dell</a>
                    <a class="list-group-item list-group-item-action" id="list-profile-list" data-toggle="list" href="#list-profile" role="tab" aria-controls="Asus">Asus</a>
                    <a class="list-group-item list-group-item-action" id="list-messages-list" data-toggle="list" href="#list-messages" role="tab" aria-controls="Hp">Hp</a>
                    <a class="list-group-item list-group-item-action" id="list-settings-list" data-toggle="list" href="#list-settings" role="tab" aria-controls="Acer">Acer</a>
                  </div>
                </div>
            </div>
          </ul>
        </div>
      </div>
    </div>
</template>

<script>
export default {

};
</script>

<style>
#leftside {
    right: 0px;
}
</style>
