<template>
  
 <div class="container">
       <div class="left-col">
          <div class="scroll-container">
                <div class="card">
                     <router-link to="/post">
                  <h2>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nisi animi nihil quos impedit.</h2>
                  <div class="date">March 7,2021</div>
                  <img src="https://img.gaadicdn.com/images/carexteriorimages/630x420/Audi/RS-Q8/7943/1598516299283/front-left-side-47.jpg" alt="">
               
                      <p class="description">
                          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Consectetur animi, rerum blanditiis veniam nihil, fugit reprehenderit fugiat, quis temporibus officiis cum sunt modi quo possimus corporis consequuntur excepturi est totam. Quisquam culpa laborum velit illo corrupti, unde harum nulla similique aperiam, cupiditate, repellat magnam optio nostrum quis facilis distinctio! Assumenda deserunt enim modi sequi sunt, corrupti harum voluptatum! Eaque, doloremque. In molestiae incidunt error ipsum asperiores dolor quidem, unde maiores fuga quo, quas, cum alias quod dolorum labore sunt beatae?
                  </p>
                  </router-link>
                </div>
                <div class="card">
                     <router-link to="/post">
                  <h2>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nisi animi nihil quos impedit.</h2>
                  <div class="date">March 7,2021</div>
                  <img src="https://img.gaadicdn.com/images/carexteriorimages/630x420/Audi/RS-Q8/7943/1598516299283/front-left-side-47.jpg" alt="">
               
                      <p class="description">
                          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Consectetur animi, rerum blanditiis veniam nihil, fugit reprehenderit fugiat, quis temporibus officiis cum sunt modi quo possimus corporis consequuntur excepturi est totam. Quisquam culpa laborum velit illo corrupti, unde harum nulla similique aperiam, cupiditate, repellat magnam optio nostrum quis facilis distinctio! Assumenda deserunt enim modi sequi sunt, corrupti harum voluptatum! Eaque, doloremque. In molestiae incidunt error ipsum asperiores dolor quidem, unde maiores fuga quo, quas, cum alias quod dolorum labore sunt beatae?
                  </p>
                  </router-link>
                </div>
                <div class="card">
                     <router-link to="/post">
                  <h2>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nisi animi nihil quos impedit.</h2>
                  <div class="date">March 7,2021</div>
                  <img src="https://img.gaadicdn.com/images/carexteriorimages/630x420/Audi/RS-Q8/7943/1598516299283/front-left-side-47.jpg" alt="">
               
                      <p class="description">
                          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Consectetur animi, rerum blanditiis veniam nihil, fugit reprehenderit fugiat, quis temporibus officiis cum sunt modi quo possimus corporis consequuntur excepturi est totam. Quisquam culpa laborum velit illo corrupti, unde harum nulla similique aperiam, cupiditate, repellat magnam optio nostrum quis facilis distinctio! Assumenda deserunt enim modi sequi sunt, corrupti harum voluptatum! Eaque, doloremque. In molestiae incidunt error ipsum asperiores dolor quidem, unde maiores fuga quo, quas, cum alias quod dolorum labore sunt beatae?
                  </p>
                  </router-link>
                </div>
               
                 
            
          </div>
       </div>
       <div class="right-col">
          <About/>
       </div>
 </div>

</template>

<script>
import About from './About.vue'
export default {
  components: { About },

}
</script>

<style lang="scss" scoped>
.container{
    width:100%;
    display: flex;

    .left-col{
        background-color:blanchedalmond;
        width:75%;
        min-height: 84vh;

        .scroll-container{
            display: flex;
            flex-direction: column;
            margin: 50px 30px;
            max-height: 95vh;
            background-color:whitesmoke;
            
            overflow-x: hidden;
            overflow-y: scroll;
        &::-webkit-scrollbar{
            display: none;
        

        }
            .card{
                margin: 20px 0px;

                a{
                    text-decoration: none;
                    color:#000;
                }
                padding: 10px 20px;
                h2{
                    
                    font-size: 2.5rem;
                    margin-bottom: 5px;   
                    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; 
                }
                .date{
                    float: right;
                    margin-bottom: 10px;    
                }
                img{
                    object-fit: cover;
                    width: 100%;
                    height: 400px;
                    margin-bottom: 10px;
                    border-radius: 5px;
                }
                .description{
                    line-height: 1.3;
                    font-size: 1.15rem;
                    text-align: left;
                    overflow: hidden;
                    text-overflow: ellipsis;
                    display: -webkit-box;
                    -webkit-line-clamp: 3; /* number of lines to show */
                    -webkit-box-orient: vertical;
                    padding: 2px 5px;
                    font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
                }
            }
        }
  

    }
    .right-col{
        width:25%;
        min-height: 84vh;
        background-color: blanchedalmond;
    }
}


@media screen and (max-width:900px) {
    .container{
        justify-content:stretch;
        flex-direction: column;
        .left-col{
        
            width:100%; 
             .scroll-container{
                margin: 30px 10px;
                max-height: 82vh;
                background-color:whitesmoke;
              .card{
                  margin: 10px 0px;
                  h2{
                    font-size: 1.25rem;
                }
                .date{
                    font-size: .8rem;
                }
                img{
                    height: 180px;
                }
                .description{
                    font-size: .95rem;
                    overflow: hidden;
                    text-overflow: ellipsis;
                    display: -webkit-box;
                    -webkit-line-clamp: 3; /* number of lines to show */
                    -webkit-box-orient: vertical;
                }
              }
        }
        }
        .right-col{
            
             width:100%;
        }

    }
}


</style>