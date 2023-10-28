<template>
    <section id="story">

        <div class="bg-parallax-photo">
            <parallax :speed-factor="0.5" sectionClass="parallax-outside" containerClass="parallax-inside">
                <img src="@/assets/bg-triangle-pink2.png" class="float-right float-md-none" />
            </parallax>
        </div>

        <div class="container py-5">
            <div class="row justify-content-md-end">
                <div class="col-md-5 py-md-5">
                    <h1 class="text-blue my-md-5">Uniting for a Digital Future.</h1>
                    <p>The IRS is continuously evolving to meet the demands of the modern world. With initiatives like the Inflation Reduction Act Strategic Operating Plan, the IRS is committed to delivering transformational change, ensuring that taxpayers have a seamless and efficient experience.</p>
                    <p>Moreover, the IRS emphasizes the importance of being prepared for unforeseen circumstances, urging taxpayers to safeguard essential documents for emergencies. They also keep the public informed with special updates and news, ensuring transparency and trust.</p>
                    <p>In this context, the IRS Digital Coalition can play a pivotal role. By fostering a sense of community and collaboration, we can support and amplify these efforts. By pooling resources, sharing knowledge, and leveraging the expertise of tech firms, the coalition can drive the digital transformation the IRS envisions, ensuring that services are user-friendly, technologically advanced, and universally accessible.</p>
                    <p> Together, we can redefine the digital landscape of government services, making them more efficient, accessible, and user-centric.</p>
                </div>
            </div>
        </div>

        <div class="bg-parallax">
            <parallax :speed-factor="0.3" sectionClass="parallax-outside" containerClass="parallax-inside">
                <img src="@/assets/bg-triangle-gray.png" />
            </parallax>
        </div>

        <div class="container py-5">
            <div class="row">
                <div class="col-md-10">
                    <h2 class="text-gray mt-5">Our community</h2>
                    <p>The Coalition formed from the shared ideals of 2 companies and continues to grow as other firms join the call.</p>
                    <p><i>* = Founding member</i></p>
                </div>
            </div>

            <div class="row justify-content-md-between">
                <div class="col-md-5">
                    <MemberItem class="row mt-5" link-url="https://strateratech.com" img="strateratech.png" img-alt="540">
                      Stratera is a woman-owned small business delivering efficient, dependable, and cost-effective solutions for over 20 years. Over the years, we have carefully developed our processes and streamlined methodologies to provide great products and services. We believe diverse teams build better products, so our teams are made up of multidisciplinary professionals that hail from different places and industries. Our tools and processes allow us to collaborate and produce great work whether we’re working in the same room or at a distance.<i>*</i>
                    </MemberItem>
                </div>

                <div class="col-md-5">
                    <MemberItem class="row mt-5" link-url="https://yudrio.com/" img="yudrio.png" img-alt="Yudrio">
                        Yudrio, Inc. is a HUBZone certified boutique Information Technology (IT) solutions provider. We provide the depth of expertise and capabilities of a large company while maintaining the intimacy of a small business. Yudrio supports mission-critical applications by providing innovative, customized, end-to-end services that demonstrate measurable benefits.<i>*</i>
                    </MemberItem>
                    
                </div>
            </div>
        </div>

      
    </section>
</template>



<script>
import Parallax from "vue-parallaxy";
import MemberItem from "@/components/MemberItem.vue";

export default {
  components: {
    Parallax,
    MemberItem,
  },
};
</script>
