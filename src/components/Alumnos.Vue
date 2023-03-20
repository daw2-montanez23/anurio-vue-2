<template>
      <div id="Alumnos" class="bg-success">
        <h1 class="pt-4 pb-4 text-center fs-1"><i class="fa-solid fa-user-tie pe-3"></i>Alumnos</h1>
        <div class="row">
            <div class="col-2 d-flex justify-content-center offset-1">
                <div class="card" style="width: 15rem;">
                  <a href="#"><img class="card-img-top imagen_card" src="../img/Jose.PNG" alt="Marta"></a>
                  <div class="card-body">
                    <h5 class="card-title">Jose Luis Viri</h5>
                </div>
            </div>
        </div>
        <div class="col-2 d-flex justify-content-center">
            <div class="card" style="width: 15rem;">
                <a href="#"><img class="card-img-top imagen_card" src="../img/Pau.PNG" alt="Pablo"></a>
                <div class="card-body">
                    <h5 class="card-title">Pablo Diaz</h5>
                  </div>
                </div>
            </div>
            <div class="col-2 d-flex justify-content-center">
                <div class="card" style="width: 15rem;">
                  <a href="#"><img class="card-img-top imagen_card" src="../img/wilbern.jpg" alt="Juan"></a>
                  <div class="card-body">
                    <h5 class="card-title">Wilvern</h5>
                  </div>
                </div>
            </div>
            <div class="col-2 d-flex justify-content-center">
                <div class="card" style="width: 15rem;">
                  <a href="#"><img class="card-img-top imagen_card" src="../img/nico.PNG" alt="Eric"></a>
                  <div class="card-body">
                    <h5 class="card-title">Nicolas Barrio</h5>
                  </div>
                </div>
            </div>
            <div class="col-2 d-flex justify-content-center">
                <div class="card" style="width: 15rem;">
                  <a href="#"><img class="card-img-top imagen_card" src="../img/sergio.jpg" alt="Jordi"></a>
                  <div class="card-body">
                    <h5 class="card-title">Sergio Coco</h5>
                  </div>
                </div>
            </div>
        </div>
    </div>  
</template>

<script>
    export default{
        name: 'Alumnos',
        props:{
            msg: String
        }
    }
</script>