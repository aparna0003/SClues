<template>
  <v-container class="black col-xs-6">
     <v-row
      class="col-lg-6  col-sm-12 col-xs-12"
      
    >  <!--breadcrumb is added-->
    
      <v-col 
      classs= "col-lg-12">
       <breadcrumb/>
        
      </v-col>
      
    </v-row>
   




         
    <v-row>
         <v-col>


                <script
 type="text/javascript">
function fun1()
{
        var div =  document.getElementById('f2');
                div.classList.remove('tb-active');
                var div =  document.getElementById('f3');
                div.classList.remove('tb-active');
                var div =  document.getElementById('f4');
                div.classList.remove('tb-active');
                document.getElementById('f1').classList.add("tb-active");

}
function fun2()
            {
                var div =  document.getElementById('f1');
                div.classList.remove('tb-active');
                var div =  document.getElementById('f3');
                div.classList.remove('tb-active');
                var div =  document.getElementById('f4');
                div.classList.remove('tb-active');
                document.getElementById('f2').classList.add("tb-active");

            }
function fun3()
{
  
                var div =  document.getElementById('f1');
                div.classList.remove('tb-active');
                var div =  document.getElementById('f2');
                div.classList.remove('tb-active');
                var div =  document.getElementById('f4');
                div.classList.remove('tb-active');
                document.getElementById('f3').classList.add("tb-active");

            
}
function fun4()
{   
                var div =  document.getElementById('f1');
                div.classList.remove('tb-active');
                var div =  document.getElementById('f2');
                div.classList.remove('tb-active');
                var div =  document.getElementById('f3');
                div.classList.remove('tb-active');
                document.getElementById('f4').classList.add("tb-active");


}
</script>

         <div class="container-fluid px-sm-1 py-5 mx-auto">
            <div class="row justify-content-center">
                <div class="d-flex">
                    <div class="card">
                        <div class="d-flex flex-column thumbnails">
                            <div id="f1" onclick = "fun1()" class="tb tb-active"> <img class="thumbnail-img fit-image" src="https://i.imgur.com/wL1uRBk.jpg"> </div>
                            <div id="f2" onclick = "fun2()" class="tb"> <img class="thumbnail-img fit-image" src="https://i.imgur.com/3NusNP2.jpg"> </div>
                            <div id="f3" onclick = "fun3()" class="tb"> <img class="thumbnail-img fit-image" src="https://i.imgur.com/pXUPOVR.jpg"> </div>
                            <div id="f4" onclick = "fun4()" class="tb"> <img class="thumbnail-img fit-image" src="https://i.imgur.com/xX5Qmsa.jpg"> </div>
                        </div>
                        <fieldset id="f11" class="active">
                            <div class="product-pic"> <img class="pic0" src="https://i.imgur.com/wL1uRBk.jpg"> </div>
                        </fieldset>
                        <fieldset id="f21" class="">
                            <div class="product-pic"> <img class="pic0" src="https://i.imgur.com/3NusNP2.jpg"> </div>
                        </fieldset>
                        <fieldset id="f31" class="">
                            <div class="product-pic"> <img class="pic0" src="https://i.imgur.com/pXUPOVR.jpg"> </div>
                        </fieldset>
                        <fieldset id="f41" class="">
                            <div class="product-pic"> <img class="pic0" src="https://i.imgur.com/xX5Qmsa.jpg"> </div>
                        </fieldset>
                    </div>
                </div>
            </div>
        </div>
        <style>
    body {
    background-color: #6200EA;
    color: #000;
    overflow-x: hidden
}

.card {
    margin: auto;
    padding: 20px;
    border-radius: 15px;
    margin-top: 50px;
    margin-bottom: 50px
}

fieldset.active {
    display: block !important
}

fieldset {
    display: none
}

.pic0 {
    width: 400px;
    height: 500px;
    margin-left: 85px;
    margin-right: auto;
    display: block
}

.product-pic {
    padding-left: auto;
    padding-right: auto;
    width: 100%
}

.thumbnails {
    position: absolute
}

.fit-image {
    width: 100%;
    object-fit: cover
}

.tb {
    width: 62px;
    height: 62px;
    border: 1px solid grey;
    margin: 2px;
    opacity: 0.4;
    cursor: pointer
}

.tb-active {
    opacity: 1
}

.thumbnail-img {
    width: 60px;
    height: 60px
}

@media screen and (max-width: 768px) {
    .pic0 {
        width: 250px;
        height: 350px
    }
}
</style>


        </v-col>
    <!--to insert the card with details-->
      <v-col   
         class=" col-md-2 col-lg-4 col-sm-12"
         offset-md="5"
         <card/>          
      </v-col>
    </v-row>





    <v-row>
      <tab/>
    </v-row>
    <v-row>
      <scroll/>
    </v-row>
    <v-row
      class="mb-6" 
      >  <!---the area to enter comments are added-->
      <v-col>
          Click to enter your queries 
         <input/>
      </v-col>
    </v-row>

    
  
  </v-container>
  </template>
  <script>
  export default {
    data: () => ({
      //
    }),
  }
</script>