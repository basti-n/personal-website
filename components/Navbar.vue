<template>
  <div class="container">
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a class="navbar-item" href="/">Portfolio</a>
        <button class="button navbar-burger">
          <span></span>
          <span></span>
          <span></span>
        </button>
      </div>
      <div class="navbar-menu">
        <div class="navbar-end">
          <nuxt-link class="navbar-item" to="/">Home</nuxt-link>
          <nuxt-link class="navbar-item" to="/about">Über mich</nuxt-link>
          <nuxt-link class="navbar-item" to="/projects">Projekte</nuxt-link>
          <nuxt-link class="navbar-item" to="/contact">Kontakt</nuxt-link>
        </div>
      </div>
    </nav>
  </div>
</template>
