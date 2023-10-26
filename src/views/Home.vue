<template>
    <section>
        
        <div class="bg-video">
            <video autoplay loop muted>
				<source src="@/assets/washington-monument.mp4" type="video/webm"/>
				<source src="@/assets/washington-monument.mp4" type="video/mp4"/>
			</video>
        </div>
        
        <div class="container py-5 px-5">
            <div class="row justify-content-md-end">
                <div class="col-md-6 py-5 text-white text-standout">
                    <h1>Transforming the Digital Approach of the IRS.</h1>
                    <h3>We are a coalition of agile technology and design firms dedicated to serving the IRS and enhancing its digital capabilities.</h3>
                    <p>Adapting to change is challenging, and implementing systematic change is even more so. That's why these design and development firms have come together to infuse the agility and innovation characteristic of commercial digital services into the IRS. Our vision of digital transformation is not just about technology—it's about leveraging technology to significantly enhance the efficiency, accessibility, and user experience of services provided by the IRS.</p>
                </div>
            </div>
        </div>
        
        <div class="bg-deep-teal text-white">
            <div class="container">
                <div class="row justify-content-md-center">
                    <div class="col-md-10">
                        <h2 class="text-center py-5">Instead of wrestling with IRS protocols, <i>imagine a system where the IRS effortlessly aligns with your needs.</i></h2>
                    </div>
                </div>
            </div>
        </div>
		
        <div class="row-relative">
		<div class="container py-5">
            <div class="row justify-content-md-start">
                <div class="col-md-6 py-md-5">
                    <h3 class="text-deep-teal">What does a digitally transformed IRS look like?</h3>
                    <p>Genuine digital evolution within the IRS translates to direct, palpable advantages for taxpayers.</p>
                    <p>Imagine a world where the vast number of taxpayers engaging with the IRS can do so effortlessly, promptly, and perhaps even with a hint of excitement, right from their smartphones, tablets, and desktops.</p>
                    <p>Visualize the transformation of traditional, paper-laden procedures into streamlined, digital processes, accelerating the IRS's efficiency and ensuring every taxpayer's dollar is put to optimal use.</p>
                    <p>Envision an IRS where the technological backbone is robust, adaptable, and fortified, guaranteeing quicker and more dependable services.</p>
                </div>
            </div>
			<img src="@/assets/bg-triangle-pink.png" id="tax-forms-img" />
        </div>
		</div>
		
        <div class="py-5 bg-mint-green">
            <div class="container">
				<div class="container row" align="center">
	                <div class="col-md-4 justify-content-md-start text-center">
						<p class="metric">25</p>
	                    <p class="metric-label">Active IRS Projects</p>
	                </div>
	                <div class="col-md-4 justify-content-md-start text-center">
						<p class="metric">500+</p>
	                    <p class="metric-label">People Deployed at IRS</p>
	                </div>
	                <div class="col-md-4 justify-content-md-start text-center">
						<p class="metric">$5B+</p>
	                    <p class="metric-label">In IRS Awards</p>
	                </div>
				</div>
            </div>
        </div>
        
        <div class="bg-white">
            <div class="container py-5">
                <h1 class="text-deep-teal pt-4">United in Purpose.</h1>
                <p>The prevailing "large-scale" contractor approach often falls short in fostering the collaboration, transparency, and efficiency that nimble, progressive firms thrive on. Our ambition is unity over rivalry. We aim to unite visionary small to midsize enterprises, all driven by the shared objective of enhancing the IRS's operations for the benefit of every American taxpayer.</p>
                <h3 class="text-deep-teal mt-5">Our Pledge for a Digital IRS.</h3>
                <div class="row py-0">
                    <div class="col-md-4">
                        <h6 class="text-deep-teal mt-1 mb-1">Mission over Margin</h6>
                        <p>Our drive is the purpose, not the profit.</p> 	
                    </div>
                    <div class="col-md-4">
                        <h6 class="text-deep-teal mt-1 mb-1">Collaboration over Recognition</h6>
                        <p>Every milestone achieved propels us towards a digitally advanced IRS.</p>
                    </div>
                    <div class="col-md-4">
                        <h6 class="text-deep-teal mt-1 mb-1">Results over Efforts</h6>
                        <p>It's the impact that counts, not just the journey.</p>
                    </div>
                </div>
                <div class="row py-0">
                    <div class="col-md-4">
                        <h6 class="text-deep-teal mt-1 mb-1">Taxpayers over Bureaucracy</h6>
                        <p>Unless we cater to taxpayer needs, our objectives will remain unfulfilled.</p>
                    </div>
                    <div class="col-md-4">
                        <h6 class="text-deep-teal mt-1 mb-1">Progress over Preservation</h6>
                        <p>Innovation emerges from embracing the unknown.</p>
                    </div>
                    <div class="col-md-4">
                        <h6 class="text-blue mt-1 mb-1">Execution over Discussion</h6>
                        <p>True excellence is when taxpayers affirm its perfection.</p>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="bg-parallax tint-light-blue">
            <parallax :speed-factor=".1" sectionClass="parallax-outside-cover" containerClass="parallax-inside">
                <img src="@/assets/collaboration.jpg" />
            </parallax>
        </div>

    </section>
</template>



<script>
    import Parallax from 'vue-parallaxy'

    export default {
      components: {
        Parallax
      }
    }
</script>
