<template>
  <div class="home">
      <div class="container-fluid d-none d-lg-block">
          <div class="row p-0">
            <div class="col-md-3 p-0">
              <div class="card left_side_content bg-dark">

              </div>
            </div>
            <div class="col-md-9 m-0 p-0">
              <div class="d-flex justify-content-center align-items-center" style="height: 80vh;">
                  <img 
                      src="../assets/images/profile_photo.png" 
                      class="profile_photo card-image ms-5" 
                      alt="profile"
                    >   
                  <div class="card border-0 mt-5 mx-5">
                      <h5 class="text-success text-uppercase">Lorem ipsum dolor sit amet</h5>
                      <h1 class="text-dark">
                        Jhon Doe
                      </h1>
                      <p class="text-muted">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Voluptate unde est natus blanditiis assumenda voluptates possimus quia dicta et ullam. Repellat necessitatibus error accusantium cum, animi itaque a vero nesciunt nobis non consequatur corporis ratione magnam veritatis adipisci sint ad libero quae exercitationem facilis sunt iure doloremque ipsum? Quibusdam, laboriosam.</p>
                      <div class="d-flex mt-3">
                          <button class="btn btn-success border-0 rounded-0 py-2 px-5">Get in touch</button>
                          <button class="btn btn-light border-0 text-dark text-bold rounded-0  py-2 px-5 ms-5">View my work</button>
                      </div>                                                     
                  </div>
                         
              </div>
               <div class="d-flex align-items-center bg-dark" style="height: 20vh;">
                    <ul class="nav contact border-0 mx-auto mt-5" style="width: 30%;">
                      <li class="nav-item">
                        <a class="nav-link"  href="#">
                          <i class="fa-brands fa-facebook"></i>
                        </a>
                      </li>
                      <li class="nav-item">
                        <a class="nav-link"  href="https://www.linkedin.com/" target="_blanck">
                          <i class="fa-brands fa-linkedin"></i>
                        </a>
                      </li>  
                      <li class="nav-item">
                        <a class="nav-link"  href="#">
                         <i class="fa-brands fa-github"></i>
                        </a>
                      </li>
                      <li class="nav-item">
                        <a class="nav-link"  href="#">
                          <i class="fa-brands fa-facebook"></i>
                        </a>
                      </li>                                           
                    </ul>                    
              </div> 
            </div>
            
          </div>
      </div>
  </div>
</template>

<script>

export default {
  name: 'HomeView',
  components: {
    
  }
}
</script>

<style scoped>
.left_side_content{
  height: 100vh;
}
.profile_photo{
  height: 396px;
  width: 285px;
}
.content_wrapper{
  height: 100vh;
}
/* .footer_wrapper{
  height: 54.5vh;
} */
h5.text-success{
  font-size: 12px;
  color: rgb(119, 201, 178) !important;
  font-weight: bold;
}
h1{
  font-size: 100px;
  font-weight: bold;
}
.btn.btn-success{
  background-color: rgb(119, 201, 178) !important;
  font-weight: bold;
  color: white;
  font-size: 11px;
}
.btn.btn-light{
  font-weight: bold;
  color: black;
  font-size: 11px;
}
.contact a.nav-link{
  height: 30px;
  width: 30px;
  border-radius: 50%;
  background-color:  rgb(119, 201, 178);
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  margin: 0 10px 0 10px;;
}
</style>
