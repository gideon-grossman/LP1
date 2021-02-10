<template>
    <div>
      <ContactInfoStripe/>
      <div>
        <b-navbar toggleable="lg" type="dark" variant="warning">
          <div class="d-flex">
            <div class="mr-auto" href="#"> 
                <img alt="Vue logo" width="15%" align="left" src="@/assets/hardwareLogo.png">
            </div>


            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

            <b-collapse id="nav-collapse" is-nav>
              <b-navbar-nav>
                <b-nav-form>
                  <div class="input-icon">
                    <input type="text" class="form-control" size="50" placeholder="Enter Part #, SKU or Keyword">                  
                  </div>
                </b-nav-form>
              </b-navbar-nav>

                <!-- Right aligned nav items -->
              <b-navbar-nav class="ml-auto">
                <b-button href="#" class="ml-2">Quote</b-button>
                <b-button href="#" class="ml-2">
                  <i class="fas fa-user"></i>
                </b-button>
              </b-navbar-nav>
            </b-collapse>
          </div>
        </b-navbar>
      </div>
      <DropdownOptions/>
    </div>
</template>

<script>
import ContactInfoStripe from "@/components/ContactInfoStripe.vue"
import DropdownOptions from "@/components/DropdownOptions.vue"
export default {
    name: "Header",
    components: {ContactInfoStripe, DropdownOptions}
}
</script>

<style scoped>
input.heighttext{
  padding: 20px 10px;
  line-height: 28px;
}
</style>