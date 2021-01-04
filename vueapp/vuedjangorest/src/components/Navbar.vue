<template>
    <div class="nav-bar">
        <nav class="navbar navbar-expand-lg navbar-light bg-white nav-1">
            <div class="container mw-0 px-3">

                <a class="navbar-brand" href="#">
                <img src="../assets/logo.png" width="" height="30" class="d-inline-block align-top" alt="">
                </a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                    <div class="collapse navbar-collapse" id="navbarSupportedContent">
                        <ul class="navbar-nav">
                            <li class="nav-item">
                                <router-link :to = "{ name: 'posts' }" exact>Posts</router-link>
                            </li>
                        </ul>
                    </div>
            </div>
        </nav>
    </div>
</template>

<script>
  export default 
  {
      name: 'Navbar',
  }
</script>

<style scooped>
    a
    {
        color: #000;
    }
</style>