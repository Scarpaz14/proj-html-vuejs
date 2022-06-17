<template>
  <nav class="navbar navbar-expand-lg">
  <div class="logo">
    <img class="img-logo img-fluid" src="../../assets/image/light-logo.png" alt="logo">
  </div>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active" v-for="(link,index) in links" :key="index">
        <a class="nav-link mx-2" href="#">{{link.text}} <i class="fa-solid fa-angle-down"></i></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#"><i class="fa-solid fa-cart-shopping"></i></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#"><i class="fa-regular fa-circle-user"></i></a>
      </li>
    </ul>
    <form class="form-inline my-2 my-lg-0">
        <input class="form-control mr-sm-2" type="search" placeholder="Search"  aria-label="Search" >
        <button type="button" class="btn btn-light"><i class="fa-solid fa-magnifying-glass"></i></button>
    </form>
  </div>
</nav>
</template>

<script>

export default {
    name:'NavBar',
     data(){
        return{
            links: [
                {
                    text:"Home",
                },
                {
                    text:"Pages",  
                },
                {
                    text:"Courses",                 
                },
                {
                    text:"Features",
                },
                {
                    text:"Blog",
                },
                {
                    text:"Shop",
                },
            ],
        }
    }

}
</script>

<style lang="scss" scoped>

.img-logo{
    height: 25px;
}
.navbar{
    background-color: var(--secondary-color);
    a{
        color:white;
    }

    a:hover{
      color:var(--primary-color);
      transform: scale(1.1);
    }
}
form{
    display: flex;
}
.btn-light{
  border: none;
  background-color: white;
  position: relative;
  right: 10px;
  color:var(--primary-color);
}

.form-control{
  width: 70%;
  border: none;
}

#navbarSupportedContent{
    display: flex;
    justify-content: end;
}



</style>