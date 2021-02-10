<template>
    <div>


<div>
  <b-navbar toggleable="lg" type="dark" variant="warning">
    <b-navbar-brand href="#"> 
        <img alt="Vue logo" width="15%" align="left" src="@/assets/hardwareLogo.png">
    </b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>


      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-form>
                            <div class="input-icon">
                              <input type="text" class="form-control" placeholder="Search…">
                                                         
                            </div>
                            
                             </b-nav-form>

                <b-button href="#" class="ml-2">Quote</b-button>
                                <b-button href="#" class="ml-2">
                                        <font-awesome-icon icon="user-secret" />

                                </b-button>


      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>

    </div>
</template>

<script>
export default {
    name: "Header"
}
</script>