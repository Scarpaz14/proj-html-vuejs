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
      <li class="nav-item active">
        <a class="nav-link" href="#">Home <i class="fa-solid fa-angle-down"></i></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Pages <i class="fa-solid fa-angle-down"></i></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Courses <i class="fa-solid fa-angle-down"></i></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Faeatures <i class="fa-solid fa-angle-down"></i></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Blogs <i class="fa-solid fa-angle-down"></i></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Shop <i class="fa-solid fa-angle-down"></i></a>
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
    </form>
  </div>
</nav>
</template>

<script>

export default {
    name:'NavBar'

}
</script>

<style lang="scss" scoped>

.img-logo{
    height: 25px;
}
.navbar{
    background-color: #1f1f52;
    a{
        color:white;
    }
}
form{
    display: flex;
}

.form-control{
  width: 70%;
}

#navbarSupportedContent{
    display: flex;
    justify-content: end;
}


</style>