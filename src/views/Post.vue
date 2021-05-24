<template>
  <div class="container">
    <div class="post">
       <div class="card">
                  <router-link to="/post">
                    <h2>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nisi animi nihil quos impedit.</h2>
                    <div class="date">March 7,2021</div>
                        <img src="https://img.gaadicdn.com/images/carexteriorimages/630x420/Audi/RS-Q8/7943/1598516299283/front-left-side-47.jpg" alt="">
                
                        <p class="description">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus repudiandae deleniti necessitatibus deserunt soluta dolor, exercitationem consectetur. Atque consequuntur odio corporis adipisci cupiditate molestias minima doloribus modi sit accusamus. Numquam veritatis suscipit consequatur sequi ad autem minus tempore dolorem qui tempora magni voluptas dolore labore nostrum itaque, aut blanditiis ipsum molestias enim eligendi repudiandae dicta pariatur facere dolorum? Facilis hic libero officiis aliquam qui asperiores laboriosam, nesciunt, voluptatum inventore blanditiis corrupti fugit animi deleniti? Voluptate, odio ducimus corporis illo consequuntur laboriosam quos iste. Laborum, consectetur dolorem cumque ex esse iusto exercitationem impedit eveniet, quae a voluptas ut neque numquam expedita culpa libero ipsa quam dicta? Impedit nam corporis debitis minima, ipsa asperiores molestiae architecto a? Culpa sit deleniti corrupti recusandae voluptatibus porro quas sunt, debitis adipisci pariatur repellat? 
                            <br><br> Voluptas corrupti veniam, minima qui, tempora incidunt assumenda obcaecati expedita a quasi excepturi quaerat quibusdam dicta sunt perferendis similique quisquam quia cumque? A nemo assumenda ratione velit? A repellat eos dicta veritatis numquam quia minus sequi facilis nisi eveniet, quasi voluptas totam laborum delectus tempora laboriosam neque amet temporibus fugit. Repellendus quam aliquam molestiae eligendi quidem nobis libero illo eum quis quaerat laudantium totam voluptatibus, nam repellat odio error harum reiciendis ad nihil temporibus iure. Ad nisi doloribus tempore debitis reprehenderit provident deserunt temporibus officiis laborum amet, assumenda nihil sint. Fugiat officia nulla voluptates, dignissimos sed dolores culpa id voluptatibus reprehenderit tempora autem repudiandae voluptate eligendi similique cumque ipsam, veniam architecto ducimus quidem facilis quia vel? Nisi dolore reprehenderit nihil debitis molestias. Reprehenderit repellat illo officiis eius sequi, molestias fugiat ipsa et dolore. Cupiditate pariatur vel vitae hic. Rem culpa quia dolor voluptate, molestiae sit ullam tempora tenetur, reprehenderit deleniti laudantium doloribus eligendi ad ipsa unde autem. Ratione eius, blanditiis maiores ipsam et quos dolores laboriosam tempora animi necessitatibus incidunt ullam aut officia tempore sunt ex dolore repellat, molestiae aliquam error neque inventore quis! Eius, repellat dolor voluptate tenetur magnam alias illum tempore velit maxime aut. Distinctio sint iusto ratione illum eos pariatur, et neque quidem similique mollitia debitis consequuntur eaque. Adipisci enim porro cumque veniam quibusdam mollitia voluptate libero, cum, quidem excepturi dignissimos sit blanditiis facilis id nisi. Atque, enim quas. Eveniet soluta, suscipit pariatur aliquam quod, amet rem saepe, exercitationem labore dolorum similique officia repellendus aliquid minima laudantium voluptatem nam ab praesentium perferendis ipsa maxime? Incidunt, iure et saepe deleniti ad aliquid totam quasi quisquam quis cumque doloremque nihil optio quod error ipsam! Explicabo deserunt voluptatum ullam! Sequi magni sint maiores mollitia voluptatibus rem, ipsa sapiente modi illo similique aperiam sit atque fuga cum, vero corrupti voluptatum ab exercitationem error et accusantium quis labore. Iusto vero velit qui expedita voluptatem accusamus aliquam, repellat, fugit natus saepe blanditiis rerum pariatur illo quisquam suscipit incidunt sit, dignissimos maxime quos tempora? Officia consequatur, nobis veritatis sint temporibus quo exercitationem? Obcaecati pariatur aliquid,<br><br> hic ullam perferendis quam nemo ad excepturi veniam praesentium ab architecto laborum, saepe unde non est natus facilis nulla? Quidem, dolore eum sapiente vel cum quod omnis distinctio necessitatibus fugiat qui?
                         
                            
                       </p>
                  </router-link>
         </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.container{
  min-height: 88vh;
  padding: 15px 10px;


  .post{
    position: relative;
    min-height: 87vh;
    background-color: white;
    .card{
      margin: 20px 0px;
      padding: 10px 20px;
    a{
      text-decoration: none;
      color:#000;
    }
    
    h2{
      font-weight: 800;
      font-size: 2.5rem;
      margin-bottom: 25px;  
      margin-top: 25px;  
      font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; 
    }
    .date{
      float: right;
      margin-bottom: 10px;    
    }
    img{
      object-fit: cover;
      width: 100%;
      height: 650px;
      margin-bottom: 10px;
      border-radius: 5px;
    }
    .description{
      
      font-size: 1.2rem;
      margin-top: 25px;
      line-height: 1.8;
      text-align: left;
      overflow: hidden;
      text-overflow: ellipsis;
      display: -webkit-box;
    
      -webkit-box-orient: vertical;
      padding: 2px 5px;
      padding-right: 40px;
      font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
                
  }
 
  }
}
 @media screen and (max-width:800px) {
  .container{
    .post{
      .card{
    padding: 10px 7px;
    padding-bottom: 40px;
    margin: 5px 0px;
    h2{
      font-size: 1.4rem;
      padding:10px 0px;
      margin-top:18px;
     
    }
    .date{
      font-size: .8rem;
    }
    img{
     height: 200px;
     
      
    }
    .description{
      font-size: 1rem;
      line-height: 1.5;
      padding: 2px 5px;
   
     
    }
  }
    }
  }
            
}
</style>