<template>
 <header>
  <div class="logo">LOGO</div>

  <nav>
        <router-link to="/">Home</router-link>
  </nav>

 </header>
</template>

<script>

export default {
  
}
</script>

<style lang="scss">
header{
    background-color:blanchedalmond;
    display: flex;
    justify-content: space-between;
    .logo{
        padding:17px 30px;
        font-size: 20px;
    }
    nav{
      
        margin:15px 30px;
        a{  
              border-radius: 5px;
              padding: 10px 15px;
              text-decoration: none;
              color: #1b1a17;
              font-size: 20px;
              font-weight: 700;
              transition: .4s;
              text-align: center;
              &:hover{
                  background-color: #fff;
                  color: #000;
              }
        }
        
    }
    .navbar-toggle{
        display: none;
    }
    @media screen and (max-width:800px){
            .navbar-toggle {
                display: block;
                position: absolute;
                right:30px;
                top:25px;
                cursor: pointer; 
                color: rgba(0,0,0,0.8);
                font-size: 24px;
            }
        
    }

}
</style>