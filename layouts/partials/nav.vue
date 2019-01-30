<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <nuxt-link to="/" class="navbar-brand">
              <img src="/assets/img/logoSurabayaDevSmall.png" alt="" srcset="">
            </nuxt-link>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup"
                aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse justify-content-end" id="navbarNavAltMarkup">
                <div class="navbar-nav">
                    <nuxt-link class="nav-item nav-link active" to="/about">
                      <h6>About Us</h6>
                    </nuxt-link>
                    <nuxt-link class="nav-item nav-link active" to="/event">
                       <h6>Event</h6>
                    </nuxt-link>
                    <nuxt-link class="nav-item nav-link active" to="/galeri">
                      <h6>Galeri</h6>
                    </nuxt-link>
                    <nuxt-link class="nav-item nav-link active" to="/blog">
                       <h6>Blog</h6>
                    </nuxt-link>
                    <nuxt-link class="nav-item nav-link active" to="/store">
                      <h6>Store</h6>
                    </nuxt-link>
                </div>
            </div>
        </div>
    </nav>
  </div>
</template>

<script>
export default {
  
}
</script>

<style>

</style>
