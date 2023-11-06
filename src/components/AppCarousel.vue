<template>

 <main class="h-100vh">
      <div class="container mb-5">
        <div class="row">
          <div class="col-12">
            <h3 class="mb-5">Our Team</h3>
            <div id="team-carousel" class="carousel slide" data-ride="carousel">
              <div class="carousel-inner">
                <div class="carousel-item active">
                  <div class="row">
                    <div class="col-4 ">
                        <div class="member-card text-center d-none d-md-block">
                            <div class="rounded-circle--team">
                              </div>
                            <div class="card-body">
                              <h5 class="card-title">lorem</h5>
                              <p class="card-text">Position</p>
                             
                            </div>
                          </div>
                    </div>
                    
                    <div class="col-4">
                        <div class="member-card text-center ">
                            <div class="rounded-circle--team">
                              </div>
                            <div class="card-body">
                              <h5 class="card-title">lorem</h5>
                              <p class="card-text">Position</p>
                             
                            </div>
                          </div>
                    </div>
                    
                    <div class="col-4">
                        <div class="member-card text-center d-none d-md-block">
                            <div class="rounded-circle--team">
                              </div>
                            <div class="card-body">
                              <h5 class="card-title">lorem</h5>
                              <p class="card-text">Position</p>
                             
                            </div>
                          </div>
                    </div>
                  </div>
                </div>
                
                <div class="carousel-item">
                  <div class="row">
                    <div class="col-4">
                        <div class="member-card text-center d-none d-md-block">
                            <div class="rounded-circle--team">
                              </div>
                            <div class="card-body">
                              <h5 class="card-title">lorem</h5>
                              <p class="card-text">Position</p>
                             
                            </div>
                          </div>
                    </div>
                    
                    <div class="col-4">
                        <div class="member-card text-center">
                            <div class="rounded-circle--team">
                              </div>
                            <div class="card-body">
                              <h5 class="card-title">lorem</h5>
                              <p class="card-text">Position</p>
                             
                            </div>
                          </div>
                    </div>
                    
                    <div class="col-4 ">
                        <div class="member-card text-center d-none d-md-block">
                            <div class="rounded-circle--team">
                              </div>
                            <div class="card-body">
                              <h5 class="card-title">lorem</h5>
                              <p class="card-text">Position</p>
                             
                            </div>
                          </div>
                    </div>
                  </div>
                </div>
              </div>
              <a class="carousel-control-prev " href="#team-carousel" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              </a>
              <a class="carousel-control-next " href="#team-carousel" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
              </a>
            </div>
          </div>
        </div>
      </div>
 </main>


</template>

<script>
export default {
  name: 'AppCards',
};
</script>

<style scoped lang="css">
 a{
   margin-top:40px;
   text-decoration:none;
   padding:5px 15px;
   background:black;
   color:white;
    border:black 1px solid;
    transition: .6s;
 }
 a:hover{ 
   background:white;
   color:black;
   border:black 1px solid;
   
 }
 .card{
   transition:.5s;
   cursor:pointer;
 }
 .card:hover{
   background:black;
   color:white;
 }
 .card:hover .text-muted{
   color:white;
 }
</style>
