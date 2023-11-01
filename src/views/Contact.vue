<template>
    <section id="contact">

        <div class="bg-video-full tint-video-blue">
            <video autoplay loop muted playsinline>
				<source src="@/assets/capitol.mp4" type="video/webm"/>
				<source src="@/assets/capitol.mp4" type="video/mp4"/>
			</video>
        </div>

        <div class="container">
            <div class="row">
                <div class="col-md-4 text-white textbox-dark-callout">
                    <h1>Contact us</h1>
                    <p>Didn’t find what you’re looking for?  Have some more questions?</p>
					<p>Email us at <a href="mailto:info@strateratech.com">info@strateratech.com</a> and we are happy to schedule a time to discuss more.</p>
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
