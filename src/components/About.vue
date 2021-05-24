<template>
  <div class="wrapper">
    
      <div class="popular">
          <h2>Popular Posts</h2>
          <div class="scroll-container">
              <div class="card">
                  <h5> <a href="/">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ex itaque porro maiores dolore corporis minima facilis, reiciendis voluptas cum rerum!</a></h5>
              </div>
              <div class="card">
                  <h5> <a href="/">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ex itaque porro maiores dolore corporis minima facilis, reiciendis voluptas cum rerum!</a></h5>
              </div>
                   <div class="card">
                  <h5> <a href="/">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ex itaque porro maiores dolore corporis minima facilis, reiciendis voluptas cum rerum!</a></h5>
              </div>
                   <div class="card">
                  <h5> <a href="/">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ex itaque porro maiores dolore corporis minima facilis, reiciendis voluptas cum rerum!</a></h5>
              </div>
              
             



          </div>
      </div>
        <div class="about">
          <h2>About Me</h2>
          <img class="avatar" src="http://www.hotavatars.com/wp-content/uploads/2019/01/I80W1Q0.png" alt="">
          <h3>Aswin CP</h3>
          <p class="about-desc">FullStack Webdeveloper and Mobile Application Developer. Currently pursuing Bachelor of Computer Science from College Of Applied Science, Calicut.</p>
          <p class="social-icons">
              <a href="/"><i class="fab fa-twitter"></i></a>
              <a href="/"><i class="fab fa-linkedin-in"></i></a>
              <a href="/"><i class="fab fa-github"></i></a>
              <a href="/"><i class="far fa-envelope"></i></a>

              
         </p>
      </div>
    
  </div>
</template>

<script>
export default {
   
}
</script>

<style lang="scss" scoped>
 .wrapper{
        margin:20px;
   
        max-height:800px;
        .about{
            margin-top:10px ;
            border-radius: 5px;
            width:100%;
            background-color: whitesmoke;
            height: 350px;
            text-align: center;
        

            h2{
                padding: 15px 0px;
            }
            .avatar {
                display: block;
                margin-left: auto;
                margin-right: auto;
                width: 100px;
                height: 100px;
                border-radius: 50%;

            }
            h3{
                margin: 20px 0px;
                
        
            }
            .social-icons{
                padding: 0px 10px;
                font-family:Verdana, Geneva, Tahoma, sans-serif;
                font-size: .85rem;
                display: flex;
                justify-content: space-evenly;
                i{  
                    margin-top: 10px;
                    font-size: 1rem;
                    color:darkred;
                    padding: 14px 20px;
                }
            }
            .about-desc{
                padding: 0px 12px;
                
                font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif    ;
            }
            @media screen and (max-width:1200px){
            .about-desc{
                font-size: .8rem;
            
            }
            }
          

        }
        .popular{
            
            border-radius: 5px;
            width:100%;
            background-color: whitesmoke;
            max-height: 450px;
            h2{
                text-align: center;
                padding:25px 0px;
            }
            .scroll-container{
                margin: 0px 15px;
            
                max-height: 350px;
                border-radius: 8px;
            
                overflow-y:scroll ;
                overflow-x:hidden;
            &::-webkit-scrollbar{
                display: none;
            }
                .card{
               
                    height: 70px;
                    h5{
                        padding: 2px 5px;
                        font-size: .98rem;
                         overflow: hidden;
                        text-overflow: ellipsis;
                        display: -webkit-box;
                        -webkit-line-clamp: 2; /* number of lines to show */
                        -webkit-box-orient: vertical;
                        a{
                            color:#000;
                            text-decoration: none;
                        }
                    }

                }
            }
        }


    }

</style>