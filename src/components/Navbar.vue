<template>
  <nav class="navbar navbar-expand-lg bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Shop</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <router-link class="nav-link" to="/">Home</router-link>
          <router-link class="nav-link" to="/about">About</router-link>
          <router-link class="nav-link" to="/produkte">Produkte</router-link>

          <!-- <li class="nav-item">
             <a class="nav-link active" aria-current="page" href="#">Home</a>
           </li>
           <li class="nav-item">
             <a class="nav-link" href="#">About</a>
           </li>
           <li class="nav-item">
             <a class="nav-link" href="#">Produkte</a>
           </li>
           <li class="nav-item">
           </li> -->
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Navbar'
}
</script>

<style scoped>

</style>
