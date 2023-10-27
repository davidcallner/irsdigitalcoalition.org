<template>
    <section>
        <div class="bg-parallax-photo">
            <parallax :speed-factor="0.8" sectionClass="parallax-outside" containerClass="parallax-inside">
                <img src="@/assets/bg-triangle-pink3.png" class="float-right" />
            </parallax>
        </div>
        <div class="container py-5">
            <div class="row justify-content-md-between">
                <div class="col-md-6 py-md-5">
                    <h1 class="text-deep-teal my-md-5">Join the coalition</h1>
                    <div class="alert alert-success" role="alert">
                        <h2 class="h4"><b>Announcement</b></h2>
                        <b>We are now accepting applications for membership.<br/><br/>Prior to filling out an application, please review the guidelines below: </b><br/><br/>
                        <b>Email your companies interest here at info@strateratech.com</a></b>
                    </div>
                    <div class="who-can-join">
                        <h2 class="text-gray mt-5">Who can join</h2>
                        <p class="list-items">Small-sized or mid-tier businesses who perform digital work for the IRS or Federal Financial institutions. Large firms will only be considered with IRS experience.</p>
                        <ol type="i">
                            <li>Small businesses: revenue less than $30M ( 5 year running average)</li>
                            <li>Mid-tier firms: revenue less than $55M (5 year running average)</li>
                            <li>Large firms: revenue greater than $55M (5 year running average)</li>
                            <li>Confirmation of size standard will be conducted in on-boarding activities using sam.gov. </li>
                        </ol>
                        <p class="list-items">Digital service work is defined as services supporting the development, implementation, or maintenance of:</p>
                        <ol type="i">
                            <li>A service that is delivered via the internet or electronic network</li>
                            <li>Automated and requires little to no human intervention</li>
                        </ol>
                        <p class="list-items">Digital transformations are efforts that have fundamentally improved the technologies, data, processes, and organizational change necessary to deliver successful outcomes for users and customers</p>
                        <p class="list-items">Firms who are committed to the IRS Mission.</p>
                    </div>
                    <div class="membership-benefits">
                        <h2 class="text-gray mt-5">Membership benefits</h2>
                        <p>This organization is committed to the growth and development of the digital service industry. Members in the IDC have access to business resources, mentorship from companies and individuals with similar experiences, exclusive and impactful networking, education, and advocacy opportunities, and business development resources.</p>
                        <div>
                            <b>Education:</b>
                            <p>IDC offers varied education opportunities including: </p>
                            <ul>
                                <li>Webinars and workshops based on topics of interest to both the government and industry with ability to earn continuous education units (CEUs) which support professional development &amp;amp; certification.</li>
                                <li>Brown Bag discussions and Ask Me Anything with subject matter experts to provide collaborative experiences that are shared among multiple companies</li>
                                <li>Hands-on or strategic training sessions one-on-one with member companies</li>
                                <li>Opportunities to speak on behalf of the IDC and its community at trade shows, meet-ups, and other external events</li>
                            </ul>
                        </div>
                        <div>
                            <b>Events:</b>
                            <p>Networking is the lifeblood of the digital service community and we provides many events - both in-person and online to connect and reinforce relationships, including:</p>
                            <ul>
                                <li>Yearly all hands meetings for overall IDC updates</li>
                                <li>IDC member happy hours and networking events </li>
                                <li>Networking and education events with government partners</li>
                                <li>Fun events &mdash; such as IDC hikes, picnics, and holiday parties</li>
                                <li>Virtual happy hours and events to ensure the distributed members have the ability to connect and network.</li>                                
                            </ul>
                        </div>
                        <div>
                            <b>Policy &amp Advocacy:</b>
                            <p>The IRS Digital Coalition champions the interests of its members in the face of governmental legislation, policies, and regulations impacting our domain: </p>
                            <ul>
                                <li>Engages in legislative evaluations concerning upcoming or amended proposals, especially in light of the recent Inflation Reduction Act (IRA) which offers a historic opportunity to transform tax administration and services for taxpayers and tax professionals. </li>
                                <li>Assists in the implementation and understanding of the IRA, which aims to improve how the IRS serves the public and tax professionals. This includes updating technology capabilities, investing in employees with new tools and skills, and enforcing tax laws more effectively.</li>
                                <li>Stands as a voice for the government on pivotal matters like accessibility, diversity, equity, and inclusion, aligning with the IRS's commitment to deliver transformational change for taxpayers as outlined in their Strategic Operating Plan.</li>
                                <li>Undertakes initiatives to amplify opportunities for socio-economic groups and marginalized talent in the tech realm, in line with the IRS's focus on enhancing taxpayer services and experiences.</li>
                            </ul>
                        </div>
                        <div>
                            <b>Market Intelligence and Business Development:</b>
                            <p>Conducts activities to understand and grow the industry opportunities for digital service firms: </p>
                            <ul>
                                <li>Collaborates with similar organizations and trade associations to grow the community and ecosystem as a means to build and maintain influence for digital service work</li>
                                <li>Reviews RFI’s, RFQs, and other government opportunities to formulate teams to tackle some of the IRS's biggest challenges.</li>
                                <li>Provides strategy or advice on large government contract actions such as GSA Schedules, GWACs, agency contracts, etc.</li>
                                <li>Networks with potential large or other partners in other industries to keep up a partnering network for member companies available.</li>
                                <li>Socioeconomic categories are well represented and special programming exists for each specific category to support set asides and marketing.</li>
                            </ul>
                        </div>
                       
                    </div>
                    <div>
                        <h2 class="text-gray mt-5">How to join</h2>
                        <p>Each existing charter member firm can evaluate and agree to sponsor one prospective new member firm per year. The charter member firm is responsible for mentoring and guiding the sponsored firm in the mission and values of the coalition. Sponsored firms must provide at least two references and pass a review by the coalition onboarding panel.</p>
                    </div>
                    
                </div>
            </div>
        </div>
        <div class="bg-parallax">
            <parallax :speed-factor=".15" sectionClass="parallax-outside-cover" containerClass="parallax-inside">
                <img src="@/assets/bg-rectangle-purple.png" />
            </parallax>
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
