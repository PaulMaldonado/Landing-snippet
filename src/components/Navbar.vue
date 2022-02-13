<template>
  <div>
      <nav class="navbar navbar-expand-lg navbar-light bg-light">
          <div class="container">
            <a class="navbar-brand" href="/">
                <img src="../assets/img/Logo.svg" alt="Logo" width="100" height="100" class="d-inline-block align-text-top">
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <i class="fa-solid fa-bars"></i>
            </button>

            <div class="collapse navbar-collapse justify-content-end" id="navbarSupportedContent">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a href="#" class="nav-link">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </a>
                    </li>

                    <li class="nav-item">
                        <a href="#" class="nav-link">Sing in</a>
                    </li>

                    <li class="nav-item">
                        <Button />
                    </li>
                </ul>
            </div>
          </div>
      </nav>
  </div>
</template>

<script>
import Button from './Button.vue'

export default {
    name: 'Navbar',
    components: {
        Button,
    }
}
</script>

<style scoped>
    .bg-light {
        background-color: transparent !important;
    }

    .fa-bars {
        font-size: 1.5em !important;
    }

    .navbar-toggler {
        box-shadow: none !important;
        border-color: transparent !important;
    }

    .fa-magnifying-glass {
        font-size: 1.2em;
    }

    .nav-link {
        font-size: 1.2em !important;
    }

    .btn {
        padding: .600rem .90rem;
    }

    .btn-dark {
        box-shadow: none !important;
        border-color: black !important;
    }
</style>