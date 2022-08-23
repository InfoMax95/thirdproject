<template>
  <header>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <a class="navbar-brand" href="#">WebSite</a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNavDropdown"
        aria-controls="navbarNavDropdown"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavDropdown">
        <ul class="navbar-nav">
          <li class="nav-item">
            <router-link class="nav-link" to="/">Home</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="/about">About</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="/contact">Contact</router-link>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              id="navbarDropdownMenuLink"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              Section
            </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
              <router-link class="dropdown-item" to="/about">About</router-link>
              <router-link class="dropdown-item" to="/about">About</router-link>
              <router-link class="dropdown-item" to="/about">About</router-link>
            </div>
          </li>
        </ul>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: "MyHeader",
};
</script>

<style scoped lang="scss"></style>
