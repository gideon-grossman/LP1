<template>
<header class="navbar navbar-custom navbar-expand-md navbar-dark bg-grey d-print-none">
                <div class="">
                  <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbar-menu">
                    <span class="navbar-toggler-icon"></span>
                  </button>
                  <div class="collapse navbar-collapse" id="navbar-menu">
                    <div class="d-flex">
                      <ul class="navbar-nav navbar-brand p-2 ">
                        <li class="nav-item active">
                          <a class="nav-link" href="./#">
                            <span class="nav-link-title">
                              <i class="fas fa-home"></i>
                            </span>
                          </a>
                        </li>
                        <li class="nav-item dropdown">
                          <a class="nav-link dropdown-toggle" href="#" data-toggle="dropdown" role="button" aria-expanded="false">
                            <span class="nav-link-title">
                              Nuts
                            </span>
                          </a>
                          <div class="dropdown-menu">
                        <a class="dropdown-item" href="./#">
                            Cap Nuts
                        </a>
                        <a class="dropdown-item" href="./#">
                            Castle Nuts
                        </a>
                        <a class="dropdown-item" href="./#">
                            Coupling Nuts
                        </a>
                        <a class="dropdown-item" href="./#">
                            Flange Serrated Nuts
                        </a>
                        <a class="dropdown-item" href="./#">
                            Hex Finish Nuts
                        </a>
                        <a class="dropdown-item" href="./#">
                            T-Nuts
                        </a>
                        <a class="dropdown-item" href="./#">
                            Wing Nuts
                        </a>
                            
                          </div>
                        </li>
                        <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#navbar-bolts" data-toggle="dropdown" role="button" aria-expanded="false">
                        <span class="nav-link-title">
                            Bolts
                        </span>
                        </a>
                        <div class="dropdown-menu">
                        <a class="dropdown-item" href="./#">
                            Anchor Bolts
                        </a>
                        <a class="dropdown-item" href="./#">
                            Carriage Bolts
                        </a>
                        <a class="dropdown-item" href="./#">
                            Blind Bolts
                        </a>
                        <a class="dropdown-item" href="./#">
                            Double End Bolts
                        </a>
                        <a class="dropdown-item" href="./#">
                            Eye Bolts
                        </a>
                        <a class="dropdown-item" href="./#">
                            Hex Bolts
                        </a>
                        <a class="dropdown-item" href="./#">
                            Machine Bolts
                        </a>
                        </div>
                        </li>

                        <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#navbar-aboutus" data-toggle="dropdown" role="button" aria-expanded="false">
                        <span class="nav-link-title">
                            About Us
                        </span>
                        </a>
                        <div class="dropdown-menu">
                        <a class="dropdown-item" href="./#">
                            Jobs
                        </a>
                        <a class="dropdown-item" href="./#">
                            The ZOTO Team
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
/* Modify brand and text color */ 
.navbar-custom .navbar-brand, 
.navbar-custom .navbar-text { 
    color: green; 
} 
</style>