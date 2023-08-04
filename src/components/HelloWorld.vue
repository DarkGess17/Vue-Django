<template>
  <div>
  <div class="row">
    <div class="col-2"></div>
  <nav class="navbar col-8">
    <!-- Logo de la empresa en el lado izquierdo -->
    
    <div class="logo">
      <img src="../images/Logo.png" alt="Logo de la empresa" />
    </div>

    <!-- Elementos de navegación en el centro -->
    <div class="nav-items">
      <router-link to="/home">Home</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/destination">Destination</router-link>
      <router-link to="/tour">Tour</router-link>
      <router-link to="/blog">Blog</router-link>
    </div>

    <!-- Botones de Login y SignUp en el lado derecho -->
    <div class="auth-buttons">
      <button class="btn" style="color: #FA7436" @click="handleLogin">Login</button>
      <button class="btn orange" style="background-color:#fa8d3b; color: #ffffff;" @click="handleSignUp">Sign Up</button>
    </div>
  </nav>
  <div class="col-2"></div>
</div>
<br> <br>
<main class="container-fluid">
  <section class="row">
    <div class="col-2"></div>

    <div class="col-md-4 align-items-center">
            <aside class="d-flex flex-column justify-content-center align-items-center">
              <h1 style="color:black; font-size: 500%; font-family: Neue Swift Pro Bold;">
                <b>Get started your exciting</b> <span style="color: #FA7436;"><b>jorney</b> </span><b>with us.</b>
              </h1>
            </aside>
            <br>
            <aside class="d-flex flex-column justify-content-center align-items-center">
              <p style="color:gray; font-size: 180%; font-family: Neue Swift Pro;">
                A Team of experienced tourism professionals will provide you with the best advice and tips for your desire place
              </p>

            </aside>
            <br>
            <button type="button" class="btn btn-outline btn-lg d-flex flex-column justify-content-center align-items-center" style="border-color: #FA7436; font-family: Neue Swift Pro Bold; color: #FA7436; ;">Discover now</button>

          </div>

          <div class="col-md-4"> 
            <img src="../images/tourist-with-thumb-up__1_-removebg 1.png">
          </div> 

          <div class="col-2"> 
            
          </div> 
  </section>

  <br><br><br><br>

  <section class="row container-fluid">
    <div class="col-2"></div>

    <div class="col-2 container-fluid">
            <div >Location <icon class="justify-content: center;	fa fa-angle-down" style="color: #FA7436;"></icon> 
              <div>
              <input type="text" style="border-style: hidden; background-color: #F7F8FC;" placeholder="Where are you going">
              </div>  

            </div>
        </div>

        <div class="col-2 container-fluid">
          <div >Date <icon class="justify-content: center;	fa fa-angle-down" style="color: #FA7436;"></icon> 
            <div>
            <input type="date" style="border-style: hidden; background-color: #F7F8FC;" placeholder="When you will go">
            </div>  


        </div>
      </div>

      <div class="col-2 container-fluid">
        <div >Guest <icon class="justify-content: center;	fa fa-angle-down" style="color: #FA7436;"></icon> 
          <div>
          <input type="number" style="border-style: hidden; background-color: #F7F8FC;" placeholder="Number of guest">
          </div>  


      </div>
    </div>
    <div class="col-2 container-fluid">
      <button type="button" class="btn  btn-lg d-flex flex-column justify-content-center align-items-center" style="background-color: #FA7436; font-family: Neue Swift Pro Bold; color: #ffffff; ;">Explore now</button>
  </div>

  <div class="col-2"></div>

</section>
<br><br><br><br><br><br><br><br><br><br><br><br><br>

<section>

  <div class="col d-flex justify-content-center align-items-center">

<h1 style="color:black; font-size: 350%; font-family: Neue Swift Pro Bold;">
  <b>Things you need</b> <span style="color: #FA7436;"><b>to do</b> </span>
</h1>
<br><br><br>


</div>
<br>
<div class="col d-flex justify-content-center align-items-center">
  <p style="color:gray; font-size: 140%; font-family: Neue Swift Pro;">
    We ensure that you'll embark on a prefectly planned,
  </p>
</div>
<div class="col d-flex justify-content-center align-items-center">
          <p style="color:gray; font-size: 140%; font-family: Neue Swift Pro;">
           safe vacation at a price you can afford.
          </p>
        </div>
        <br><br><br>
</section>


<section>

  <div class="container d-flex justify-content-center align-items-center">

    <div class="row justify-content-center">

<div class="col-3 text-left p-3" style="color:black; font-size: 150%; background-color:white; padding-right: 10px;"> 
  <br> <img src="../images/Group (2).png"><br><br><br> <b>Sign Up</b><br><br> <span style="color: gray; font-size: 70%;"> Completes all the work associated with planning and processing</span>
</div>

<div class="col-3 text-left p-3" style="color:black; font-size: 150%; background-color:white; padding-right: 10px;"> 
  <br> <img src="../images/Group.png"><br><br><br> <b>Worth of Money</b><br><br> <span style="color: gray; font-size: 70%;"> After successful access the book from exclusive deals & pricing</span>
</div>

<div class="col-3 text-left p-3" style="color:black; font-size: 150%; background-color:white; padding-right: 10px;"> 
  <br> <img src="../images/Group (1).png"><br><br><br> <b>Exciting Travel</b><br><br> <span style="color: gray; font-size: 70%;"> Star and explore a wide range of exciting travel experience.</span>
</div>

</div>

  </div>

</section>
<br><br><br><br><br><br><br><br><br><br>

<section>

  <div class="col d-flex justify-content-center align-items-center">

<h1 style="color:black; font-size: 350%; font-family: Neue Swift Pro Bold;">
  <b>Exclusive</b> <span style="color: #FA7436;"><b>deals & discounts</b> </span>
</h1>
<br><br><br><br>


</div>

<br>
          <div class="col d-flex justify-content-center align-items-center">
          <p style="color:gray; font-size: 140%; font-family: Neue Swift Pro;">
            Discover our fantastic early booking discounts
          </p>
        </div>

        <div class="col d-flex justify-content-center align-items-center">
          <p style="color:gray; font-size: 140%; font-family: Neue Swift Pro;">
           & start planning your jorney.
          </p>
        </div>
        <br><br><br>


</section>
<br><br><br><br><br><br>


<section>

  <div class="container">
            <div class="row">  
              <div class="col d-flex justify-content-center align-items-center" v-for="product in products" :key="product.id">
                    <div class="image-container">
                      <img :src="product.image" class="img-fluid2 main-image2">
                      
                        <div>
                            <div class="col d-flex justify-content-left align-items-left" ><br><b style="font-size: 150%;"><span>{{product.name}}</span></b>   
                              <span class="col d-flex justify-content-end" style="font-size: 150%;">
                                <icon class="col d-flex justify-content-end align-items-center;	fa fa-star" style="color:#FA7436 ;;"></icon>{{ product.calification }}</span>
                              </div>

                            </div>  
                          <br>
                                <div>
                                  <div class="col d-flex justify-content-left align-items-left">
                                    <icon class="col d-flex justify-content-left align-items-left;	fa fa-map-marker" style="color:#000000 ;;"><p style="color:gray; font-size: 120%; font-family: Neue Swift Pro;"> {{ product.category_name }}</p> </icon> 
                                    <span class="col d-flex justify-content-end" style="font-size: 110%; color: gray;"> <del>${{ product.price }}</del></span>
                                    <span class="col d-flex justify-content-end" style="font-size: 110%; color: #FA7436;"> ${{ product.price - product.price*0.4 }}</span>
                                  </div>
                                </div>
                              </div>
                    
                  </div>
                 </div>
              </div>
         

</section>
<br><br>
        <section>
            
          <div class="container d-flex justify-content-center align-items-center">
             <div class="row">
            <div class="col justify-content-end align-items-center">
                
                <icon class=" col-6 justify-content-end; fa fa-arrow-circle-o-left" style="font-size: 350%; color:gray;"></icon>
              </div>         
                
              <div class=" col-6 justify-content-end align-items-center ">
                <icon class="col d-flex justify-content-center align-items-center; fa fa-arrow-circle-o-right" style="font-size: 350%; color:#FA7436;"></icon>
              </div>
            </div>
          </div>

      </section>

      <br><br><br>
      <br><br><br>
      <br><br><br>

      <section>

        <div class="col d-flex justify-content-center align-items-center">

<h1 style="color:black; font-size: 350%; font-family: Neue Swift Pro Bold;">
  <b>Best</b> <span style="color: #FA7436;"><b>vacation plan</b> </span>
</h1>
<br><br><br><br>

</div>
<br>
          <div class="col d-flex justify-content-center align-items-center">
          <p style="color:gray; font-size: 140%; font-family: Neue Swift Pro;">
            Plan your perfect vacation with our travel agency. Choose
          </p>
        </div>
        <div class="col d-flex justify-content-center align-items-center">
          <p style="color:gray; font-size: 140%; font-family: Neue Swift Pro;">
           among hundreds of all-inclusive offers!
          </p>
        </div>
        <br><br><br>
      </section>

      <section>

        <div class="container2">
            <div class="row">
                <div class="col d-flex justify-content-center align-items-center">
                    <div class="image-container2">
                      
                        <img src="../images/Image (1).png" alt="Imagen 1" class="img-fluid2 main-image2">
                        <img class="hover-image2 img-fluid" src="../images/Hover effect.png" alt="">

                          <div>
                            <div class="col d-flex justify-content-left align-items-left" ><br><b style="font-size: 150%;"><span>Rome, Italy</span></b>   
                              <span class="col d-flex justify-content-end" style="font-size: 150%; color: #FA7436;"> <b>$5,42k</b></span>
                              </div>

                            </div>  
                          <br>
                                <div>
                                  <div class="col d-flex justify-content-left align-items-left">
                                    <icon class="col d-flex justify-content-left align-items-left;	fa fa-location-arrow" style="color: #FA7436 ;;"><p style="color:gray; font-size: 120%; font-family: Neue Swift Pro;"> 10 Days trips</p> </icon> 
                                    <span class="col d-flex justify-content-end" style="font-size: 110%; color: gray;"> <icon class="col d-flex justify-content-end align-items-center;	fa fa-star" style="color:#FA7436 ;;"></icon>4.8</span>
                                  </div>
                                </div>
                    </div>
                    
                </div>
                
                <div class="col d-flex justify-content-center align-items-center">
                  <div class="image-container2">
                      <img src="../images/Image (2).png" alt="" class="img-fluid2 main-image2">
                      <img class="hover-image2 img-fluid2" src="../images/Hover effect.png" alt="">

                      <div>
                        <div class="col d-flex justify-content-left align-items-left" ><br><b style="font-size: 150%;"><span>London, UK</span></b>   
                          <span class="col d-flex justify-content-end" style="font-size: 150%; color: #FA7436;"> <b>$2,42k</b></span>
                          </div>
                        
                        
                      </div>  
                      <br>
                      <div>
                        <div class="col d-flex justify-content-left align-items-left">
                          <icon class="col d-flex justify-content-left align-items-left;	fa fa-location-arrow" style="color: #FA7436 ;;"><p style="color:gray; font-size: 120%; font-family: Neue Swift Pro;"> 07 Days trips</p> </icon> 
                          <span class="col d-flex justify-content-end" style="font-size: 110%; color: gray;"> <icon class="col d-flex justify-content-end align-items-center;	fa fa-star" style="color:#FA7436 ;;"></icon>4.7</span>
                        </div>
                      </div>
                  </div>
              </div>
              <div class="col d-flex justify-content-center align-items-center">
                <div class="image-container2">
                    <img src="../images/Image (3).png" alt="" class="img-fluid2 main-image2">
                    <img class="hover-image2 img-fluid2" src="../images/Hover effect.png" alt="">

                    <div>
                      <div class="col d-flex justify-content-left align-items-left" ><br><b style="font-size: 150%;"><span>Osaka, Japan</span></b>   
                        <span class="col d-flex justify-content-end" style="font-size: 150%; color: #FA7436;"> <b>$5,42k</b></span>
                        </div>
                      </div>  
                    <br>
                    <div>
                      <div class="col d-flex justify-content-left align-items-left">
                        <icon class="col d-flex justify-content-left align-items-left;	fa fa-location-arrow" style="color: #FA7436 ;;"><p style="color:gray; font-size: 120%; font-family: Neue Swift Pro;"> 10 Days trips</p> </icon> 
                        <span class="col d-flex justify-content-end" style="font-size: 110%; color: gray;"> <icon class="col d-flex justify-content-end align-items-center;	fa fa-star" style="color:#FA7436 ;;"></icon>4.8</span>
                      </div>
                    </div>
                </div>
            </div>
           
            </div>
            
          </div>

      </section>
      <br><br><br><br><br><br>

      <section class="row">

        <div class="col-2"> </div> 

        <div class="col-md-4 align-items-left">
          <br><br><br><br>
          <aside class="d-flex flex-column justify-content-left align-items-left">
            <h1 style="color:black; font-size: 300%; font-family: Neue Swift Pro Bold;">
              <b>What people say <br></b> <span style="color: #FA7436;"><b>abou us.</b> </span>
            </h1>
          </aside>
          <br>
          <aside class="d-flex flex-column justify-content-center align-items-left">
            <p style="color:gray; font-size: 120%; font-family: Neue Swift Pro;">
              Our Clients send us bunch of smilies with our services <br>and we love them.
            </p>

          </aside>
          <br>
          <div class="row">
            <div class="col justify-content-end align-items-center">
                
                <icon class=" col-2 justify-content-end; fa fa-arrow-circle-o-left" style="font-size: 350%; color:gray;"></icon>
              </div>         
                
              <div class=" col-10 justify-content-end align-items-left ">
                <icon class="col d-flex justify-content-left align-items-left; fa fa-arrow-circle-o-right" style="font-size: 350%; color:#FA7436;"></icon>
              </div>
            </div>
        </div> 
        
        <div class="col-md-4"> 
          <img src="../images/Comentario.png">
        </div> 
        
        <div class="col-2"> 
          
        </div> 
        

      </section>
      <br><br><br><br>

      <section>

        <div class="col d-flex justify-content-center align-items-center">

<h1 style="color:black; font-size: 350%; font-family: Neue Swift Pro Bold;">
  <b>Get update with</b> <span style="color: #FA7436;"><b>latest blog</b> </span>
</h1>
<br><br>
        </div>
      </section>

<section>

  <div class="container3">
          <div class="row">
              <div class="col d-flex justify-content-center align-items-center">
                  <div class="image-container3">
                    
                      <img src="../images/Image (1).png" alt="Imagen 1" class="img-fluid3 main-image3">
                      <img class="hover-image3 img-fluid" src="../images/Hover effect.png" alt="">
                      
                        <div>
                          <br>
                          <div class="col d-flex justify-content-left align-items-left" ><br>
                            <b style="font-size: 100%;"><span>The amazing Difference a <br> Year of Traveling.</span></b>   
                       
                            </div>

                          </div>  
                        <br>
                              <div>
                                <div class="col d-flex justify-content-left align-items-left">
                                <p style="color:gray; font-size: 120%; font-family: Neue Swift Pro;"> July 27, 2021</p>  
                                 
                                </div>
                              </div>
                  </div>
                  
              </div>

              <div class="col d-flex justify-content-center align-items-center">
                <div class="image-container3">
                    <img src="../images/Image (2).png" alt="" class="img-fluid3 main-image3">
                    <img class="hover-image3 img-fluid3" src="../images/Hover effect.png" alt="">

                    <div>
                      <br>
                      <div class="col d-flex justify-content-left align-items-left" ><br>
                        <b style="font-size: 100%;"><span>Travel far enough, you <br> meet yourself.</span></b>   
                   
                        </div>
                      
                      
                    </div>  
                    <br>
                    <div>
                            <div class="col d-flex justify-content-left align-items-left">
                            <p style="color:gray; font-size: 120%; font-family: Neue Swift Pro;"> July 27, 2021</p> 
                             
                            </div>
                          </div>
                </div>
            </div>
            <div class="col d-flex justify-content-center align-items-center">
              <div class="image-container3">
                  <img src="../images/Image (3).png" alt="" class="img-fluid3 main-image3">
                  <img class="hover-image3 img-fluid3" src="../images/Hover effect.png" alt="">

                  <div>
                    <br>
                    <div class="col d-flex justify-content-left align-items-left" ><br>
                      <b style="font-size: 100%;"><span>How to Save Money While <br> Visiting Africa.</span></b>   
                 
                      </div>
                    
                    
                  </div>  
                  <br>
                        <div>
                          <div class="col d-flex justify-content-left align-items-left">
                          <p style="color:gray; font-size: 120%; font-family: Neue Swift Pro;"> July 27, 2021</p> 
                           
                          </div>
                        </div>
              </div>
          </div>
          <div class="col d-flex justify-content-center align-items-center">
            <div class="image-container3">
                <img src="../images/Image (4).png" alt="" class="img-fluid3 main-image3">
                <img class="hover-image3 img-fluid3" src="../images/Hover effect.png" alt="">

                <div>
                  <br>
                  <div class="col d-flex justify-content-left align-items-left" ><br>
                    <b style="font-size: 100%;"><span>Reflections on 5 Months of <br>Travel: Time to Hang</span></b>   
               
                    </div>
                  
                  
                </div>  
                <br>
                <div>
                        <div class="col d-flex justify-content-left align-items-left">
                        <p style="color:gray; font-size: 120%; font-family: Neue Swift Pro;"> July 27, 2021</p> 
                         
                        </div>
                      </div>
            </div>
        </div>
          </div>
          
        </div>

</section>
<br><br><br>

<section>

  <div class="container">
          <div class="row justify-content-center">
              <div class="col-2">
                
              </div>
              <div class="col" style="background-color: #FA7436; border-radius: 10px;">
                  <h1 style="text-align: center; color: #ffffff;"><br><br>Subscribe and get exclusive <br> deals & offer</h1>
                  <br><br><br>
                  <div class="input-group">
                    <div class="input-group-prepend">
                        <span class="input-group-text">
                            <i class="fa fa-envelope"></i>
                        </span>
                    </div>
                    <input type="text" class="form-control" placeholder="Enter your email">
                    <div class="input-group-append">
                        <button class="btn btn-primary" style="background-color: #FA7436;" type="button">Subscribe</button>
                    </div>
                </div>
              </div>
              <div class="col-2">
              
              </div>
          </div>
      </div>

</section>
<br><br><br><br>

<section class="row container-fluid">

  <div class="col-3">



</div>
<div class="col container-fluid">
        <div ><img src="../images/Logo.png" alt="Logo" class="logo">
          
          <div>
          <br>  <p style="color: gray;"><b>Book your trip in minute, get full <br> Control for much longer.</b></p>

          <div class="d-flex justify-content-left">
            <a href="#" class="btn btn-primary circle-icon">
                <i class="fa fa-facebook"></i>
            </a>
            <a href="#" class="btn btn-primary circle-icon circle-icon-instagram" style="background-color: #FA7436;">
                <i class="fa fa-instagram"></i>
            </a>
            <a href="#" class="btn btn-primary circle-icon">
              <font-awesome-icon icon="fa-brands fa-facebook" />
            </a>
        </div>
        </div>

          </div>  

      </div>

      <div class="col-1 container-fluid">
      <div ><b style="font-size: 150%;">Company</b>
        
        <div>
          <br>
          <a href="#" style="text-decoration: none; color: gray;">About us</a>
          <br><br>
          <a href="#" style="text-decoration: none; color: gray;">Careers</a>
          <br><br>
          <a href="#" style="text-decoration: none; color: gray;">Logistic</a>
          <br><br>
          <a href="#" style="text-decoration: none; color: gray;">Privacy & Policy</a>
          <br><br>
        </div>  


    </div>
    </div>
    <div class="col-1 container-fluid">
      <div ><b style="font-size: 150%;">Contact</b>
        
        <div>
          <br>
          <a href="#" style="text-decoration: none; color: gray;">Help/FAQ</a>
          <br><br>
          <a href="#" style="text-decoration: none; color: gray;">Press</a>
          <br><br>
          <a href="#" style="text-decoration: none; color: gray;">Affilates</a>
          <br><br>
          
        </div> 
      </div>
    </div> 

    <div class="col-1 container-fluid">
      <div ><b style="font-size: 150%;">More</b>
        
        <div>
          <br>
          <a href="#" style="text-decoration: none; color: gray;">Press Centre</a>
          <br><br>
          <a href="#" style="text-decoration: none; color: gray;">Our Blog</a>
          <br><br>
          <a href="#" style="text-decoration: none; color: gray;">Low fare tips</a>
          <br><br>
          
        </div>  


    </div></div>

    <div class="col-3">

</div>

 
</section>
</main>

<footer>

<div class="container">
  <div class="row">
    <hr style="border-top: 1px solid gray; margin-top: 20px;">
     
      <div class="col-4" style="color: gray;">Copyright, Trabook 2022. All rights reserved.</div>
      <div class="col-4"></div>
      <div class="col-4 text-right" style="color: gray; text-align: right;">Terms & Conditions</div>
      <br><br>
  </div>
</div>
<br><br> 

</footer>



</div>
</template>

<script>

import axios from 'axios'

export default {

 
  data() {
    return {
      products: []
    }
  },

  mounted(){
    axios.get('http://127.0.0.1:8000/api/products/')
    .then(response=>{
      this.products = response.data
    })
    .catch(error=>{
      console.log(error)
    })
  },
  

  methods: {
    handleMouseOver(imageId) {
      this.activeImageId = imageId;
    },
    handleMouseLeave() {
      this.activeImageId = null;
    },
    handleLogin() {
      // Lógica para abrir el formulario de inicio de sesión
    },
    handleSignUp() {
      // Lógica para abrir el formulario de registro
    },
  },
 
};

</script>

<style>
/* Estilos CSS para el navbar */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px;

}

.logo img {
  max-height: 40px;
}

.nav-items {
  display: flex;
  justify-content: center;
  gap: 20px;
}

.nav-items a {
  text-decoration: none;
  color: #333;
  font-size: 16px;
}

.auth-buttons button {
  padding: 8px 16px;
  color: #fff;
  cursor: pointer;
}

.auth-buttons button + button {
  margin-left: 10px;
}

.image-container {
                position: relative;
            }
    
            .hover-image {
                position: absolute;
                top: 0;
                left: 0;
                opacity: 0;
                transition: opacity 0.3s ease;
            }
    
            .image-container.clicked .hover-image {
                opacity: 1;
            }

.image-container2 {
                position: relative;
            }
    
            .hover-image2 {
                position: absolute;
                top: 0;
                left: 0;
                opacity: 0;
                transition: opacity 0.3s ease;
            }
    
            .image-container2.clicked .hover-image {
                opacity: 1;
            }

.image-container3 {
              position: relative;
          }
  
          .hover-image3 {
              position: absolute;
              top: 0;
              left: 0;
              opacity: 0;
              transition: opacity 0.3s ease;
          }
  
          .image-container3.clicked .hover-image {
              opacity: 1;
          }
</style>