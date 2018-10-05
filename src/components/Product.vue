<template>
 <div class="row">
                <div class="col-lg-3 col-md-6">
                    <div class="card">
                        <div class="card-body">
                          <img  class="product-image" src="https://img.pystatic.com/products/334007-7b1716ba-04f2-4f0e-96b3-b9cdbe0096e0.jpg"> 
                                       <h5 class="card-title">Grande Mitad y Mitad <b class="card-add" title="Agregar a mi pedido">+</b> </h5>

                                        <p class="card-text">Muzzarella, salsa de tomates, tomate en rodajas, ajo picado, aceitunas verdes y orégano.</p>
                                        
                                    
                             <div class="card-footer">
<span class="discounted-price">$35</span>
<span class="has-discount">$38,89</span>
</div>   
                        </div>
                    </div>
                </div>
            </div>
</template>
<script>
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.card {
    min-height: 60px;
    background-color: lightgrey;
}
.card-body {
   padding-top: 1.25rem;
  padding-right: 1.25rem;
    padding-bottom: 1.25rem;
    padding-left: 0.25rem;
}
.product-image {
    border: #dfdfdf 1px solid;
    width: 96px;
    height: 96px;
    border-radius: 4px;
    float: left;
    margin-right: 0.3rem;
    display: table-cell;
    #overflow: hidden;
}
.card-title {
    font-size: 14px;
    margin-bottom: 0rem;
}
.card-text {
    width: 100%;
    padding-top: 2px;
   #clear: left;
    #overflow: hidden;
    text-overflow: ellipsis;
    -webkit-box-orient: vertical;
    -webkit-line-clamp: 1;
    max-height: 22px;
    font-size: 13px;
    color: #7b7b7b;
    line-height: 15px;
   #display: -webkit-inline-box
}
.card-add {
    width: 22px;
    height: 24px;
    position: relative;
    float: right;
    margin: -5px 0 0 0px;
    font-size: 0;
   background: url(https://live.pystatic.com/webassets/profile/add-button-63e98ca38b47cd1b5a247c0a3334e075.svg) no-repeat 0 -97px;  
}
.card-footer {
    padding: 0.75rem 1.25rem;
    padding-top: 1.75rem;
    padding-right: 1.25rem;
    padding-bottom: 0.75rem;
    padding-left: 1.25rem;
    background-color: transparent;
    border-top: 0px;
    position: relative;
    float: top;
}
span.discounted-price {
    color: #1FBFBF;
}
span.has-discount {
    font-size: .9em;
    line-height: 1;
    text-decoration: line-through;
    color: #A9B1B7;
    padding: 0 0 .2em;
}
</style>
