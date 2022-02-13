<template>
  <div>
      <footer class="p-4">
          <div class="container">
              <div class="row">
                  <nav class="navbar navbar-expand-lg navbar-light bg-light">
                    <div class="container">
                        <a class="navbar-brand" href="/">
                            <img src="../assets/img/Logo.svg" alt="Logo" width="100" height="100" class="d-inline-block align-text-top">
                        </a>

                        <div class="justify-content-end">
                            <ul class="navbar-nav">
                                <li class="nav-item">
                                    <a href="#" class="nav-link">
                                        Terms and Conditions
                                    </a>
                                </li>

                                <li class="nav-item">
                                    <a href="#" class="nav-link">
                                        Privacy Policy
                                    </a>
                                </li>
                            </ul>
                        </div>
                    </div>
                </nav>
              </div>
          </div>
      </footer>
  </div>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style scoped>
    .bg-light {
        background-color: transparent !important;
    }
</style>