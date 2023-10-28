<template>
    <section id="contact">

        <div class="bg-parallax-photo">
            <parallax :speed-factor="0.5" sectionClass="parallax-outside" containerClass="parallax-inside">
                <img src="@/assets/bg-triangle-blue2.png" class="float-right float-md-none" />
            </parallax>
        </div>

        <div class="container py-5">
            <div class="row justify-content-md-between">
                <div class="col-md-6 py-md-5">
                    <h1 class="text-blue my-lg-5">Contact us</h1>
                </div>

                <div class="col-md-5 py-md-5">
                    <h5 class="text-gray">Have a question about what we’re up to? Want to know more about working with us? Drop us a note at info@strateratech.com!</h5>

                  
                </div>
            </div>
        </div>
        
    </section>
</template>



<script>
import Parallax from "vue-parallaxy";
export default {
  components: {
    Parallax,
  },
};
</script>
