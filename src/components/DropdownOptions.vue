<template>
<header class="navbar navbar-expand-md navbar-dark bg-grey d-print-none">
                <div class="">
                  <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbar-menu">
                    <span class="navbar-toggler-icon"></span>
                  </button>
                  <div class="collapse navbar-collapse" id="navbar-menu">
                    <div class="d-flex">
                      <ul class="navbar-nav p-2">
                        <li class="nav-item active">
                          <a class="nav-link" href="./#">
                            <span class="nav-link-title">
                              <i class="fas fa-home"></i>
                            </span>
                          </a>
                        </li>
                        <li class="nav-item dropdown">
                          <a class="nav-link dropdown-toggle" href="#navbar-nuts" data-bs-toggle="dropdown" role="button" aria-expanded="false">
                            <span class="nav-link-title">
                              Nuts
                            </span>
                          </a>
                          <div class="dropdown-menu">
                            <a class="dropdown-item" href="./#">
                              First
                            </a>
                            <a class="dropdown-item" href="./#">
                              Second
                            </a>
                            <a class="dropdown-item" href="./#">
                              Third
                            </a>
                          </div>
                        </li>
                        <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#navbar-bolts" data-bs-toggle="dropdown" role="button" aria-expanded="false">
                        <span class="nav-link-title">
                            Bolts
                        </span>
                        </a>
                        <div class="dropdown-menu">
                        <a class="dropdown-item" href="./#">
                            First
                        </a>
                        <a class="dropdown-item" href="./#">
                            Second
                        </a>
                        <a class="dropdown-item" href="./#">
                            Third
                        </a>
                        </div>
                        </li>

                        <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#navbar-aboutus" data-bs-toggle="dropdown" role="button" aria-expanded="false">
                        <span class="nav-link-title">
                            About Us
                        </span>
                        </a>
                        <div class="dropdown-menu">
                        <a class="dropdown-item" href="./#">
                            First
                        </a>
                        <a class="dropdown-item" href="./#">
                            Second
                        </a>
                        <a class="dropdown-item" href="./#">
                            Third
                        </a>
                        </div>
                        </li>
                        <li class="nav-item">
                          <a class="nav-link" href="./#">
                            <span class="nav-link-title">
                              Resources
                            </span>
                          </a>
                        </li>
                        <li class="nav-item">
                          <a class="nav-link" href="./#">
                            <span class="nav-link-title">
                              Contact Us
                            </span>
                          </a>
                        </li>                        
                      </ul>
                    </div>
                  </div>
                </div>
              </header>
</template>

<script>
export default {
    name: "DropdownOptions"
}
</script>

<style scoped>
.nav-link {
    background-color: white
}