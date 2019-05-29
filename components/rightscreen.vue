<template>
    <!-- right side screen-->
    <div id="rightside" class="right-side col-md-9 col-xs-12">
      <div class="header">
       <input type="text" class="form-control search-box" placeholder="Search...">
       <button type="button" class="form-control btn btn-primary" id="cartbtn"> <i class="fas fa-shopping-cart"></i>   ({{ items }})</button>
      </div>
      <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">      
         <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>       
         <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>       
         <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        </ol>
       
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img class="d-block w-100 img-fluid" src="http://placehold.it/900x150" alt="First slide">
            </div>
       
            <div class="carousel-item">       
                <img class="d-block w-100 img-fluid" src="http://placehold.it/900x150" alt="Second slide">      
            </div>
       
            <div class="carousel-item">       
                <img class="d-block w-100 img-fluid" src="http://placehold.it/900x150" alt="Third slide">      
            </div>       
        </div>
       
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">       
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>      
            <span class="sr-only">Previous</span>      
        </a>
       
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">       
            <span class="carousel-control-next-icon" aria-hidden="true"></span>       
            <span class="sr-only">Next</span>       
        </a>
       
    </div>
      
     <br>
     <!--Items-->
      <Item :additem="add"></Item>
    
</div>
</template>

<script>
import store from "@/store.js";
import Item from "@/components/Item.vue";

export default {
    comments: {Item},
    name: '#additems',
    data() {
        return {
           items: 0,
        }
        
    },
    methods: {
        add() {
           return this.items++;
        },
        clear() {
            return this.items
        }
    }

}
</script>

<style>
#carouselIndicators {
    height: 50px;
    width: 50px;
}
.form-control.search-box {
    width: calc(100% - 110px) !important;
    float: left;
}

#cartbtn {
    width: 90px;
    float: right;
}
</style>
