<template>
  <div id="app">
    <nav class="navbar navbar-expand-md bg-dark navbar-dark">
        <ul class="navbar-nav">
            <li class="nav-item active">
               <router-link to="/">Sorveteria Zé de William</router-link>
            </li>
        </ul>
        <ul class="navbar-nav ml-auto">
          <li class="nav-item active">
            <!--<a class="nav-link" href="#">Dashboard</a>-->
            <button type="button" class="btn btn-dark" data-toggle="modal" data-target="#myModal">
              <router-link to="/dashboard">Dashboard</router-link>
            </button>
          </li>
          <li class="nav-item active">
            <!--<a class="nav-link" href="#">Sign in</a>-->
            <button type="button" class="btn btn-dark" data-toggle="modal" data-target="#myModal">
              <router-link to="/login">Login</router-link>
            </button>
          </li>
        </ul>
    </nav>
    <div class="container">
      <div class="row">
        <div class="col-sm-12">
          
        </div>
      </div>
    </div>
    <router-view/>
  </div>
</template>



<script>
export default {
  name: 'App',
};
</script>
