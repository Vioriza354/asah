<template>
    <div>

        <div class="position-relative">
            <!-- shape Hero -->
            <section class="section-shaped my-0">
                <div class="shape shape-style-1 shape-default shape-skew">
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
                <div class="container shape-container d-flex">
                    <div class="col px-0">
                        <div class="row">
                            <div class="col-lg-6">
                                <img class=" img-fluid" src="img/brand/gwhite_asah.png" alt="" style="width: 300px;">
                                
                                <h1 class="display-3  text-white">
                                    <span>Education & Training</span>
                                    <span>Platform</span>
                                    
                                </h1>
                                <p class="lead  text-white">ASAH Company is a platform that providing online based vocational education training.</p>
                                <div class="btn-wrapper">
                                    <base-button tag="a"
                                                 href="#/register"
                                                 class="mb-3 mb-sm-0"
                                                 type="info"
                                                 icon="fa fa-code">
                                        GET STARTED 
                                    </base-button>
                                    <base-button tag="a"
                                                 href="#/login"
                                                 class="mb-3 mb-sm-0"
                                                 type="white"
                                                 icon="ni ni-cloud-download-95">
                                        SIGN UP
                                    </base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <!-- 1st Hero Variation -->
        </div>
        <section class="section section-lg pt-lg-0 mt--200">
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-lg-12">
                        <div class="row row-grid">
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-check-bold" type="primary" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-primary text-uppercase">How to be Web Developer</h6>
                                    <p class="description mt-3">will learn step-by-step starting from design UI/UX using photoshop creating website framework with HTML, CSS creating powerful front-end javascript and using boostrap and JQuery frameworks.</p>
                                    <div>
                                        <badge type="primary" rounded>design</badge>
                                        <badge type="primary" rounded>system</badge>
                                        <badge type="primary" rounded>creative</badge>
                                    </div>
                                    <base-button tag="a" href="#/landing" type="primary" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-istanbul" type="success" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-success text-uppercase">Learn to make Financial Report</h6>
                                    <p class="description mt-3">Every company has financial report, therefore we need learn it starting from recognizing the type make financial report</p>
                                    <div>
                                        <badge type="success" rounded>business</badge>
                                        <badge type="success" rounded>finance</badge>
                                        <badge type="success" rounded>report</badge>
                                    </div>
                                    <base-button tag="a" href="#/landing" type="success" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-planet" type="warning" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-warning text-uppercase">Learn to be Graphic Desaigner</h6>
                                    <p class="description mt-3">provide overview and ability to recognize and complete projects in the form of deskop publishing, digital illustration, digital imaging, web design, and multimedia.</p>
                                    <div>
                                        <badge type="warning" rounded>marketing</badge>
                                        <badge type="warning" rounded>product</badge>
                                        <badge type="warning" rounded>launch</badge>
                                    </div>
                                    <base-button tag="a" href="#/landing" type="warning" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section>
            <div class="container ">
                <h2 class="">Start learning from</h2>
                <h2 class="display-2 mb-5  "> the world’s best platform </h2>
            <div class="row">
                <div class="col-md-6 mb-5 mb-md-0">
                    <div class="card card-lift--hover shadow border-0">
                        <router-link to="/landing" title="Landing Page">
                            <img v-lazy="'img/theme/iklan1.png'" class="card-img">
                        </router-link>
                    </div>
                </div>
                <div class="col-md-6 mb-5 mb-lg-0">
                    <div class="card card-lift--hover shadow border-0">
                        <router-link to="/profile" title="Profile Page">
                            <img v-lazy="'img/theme/ikan2.png'" style="height: 390px;" class="card-img">
                        </router-link>
                    </div>
                </div>
            </div>
        </div>
        </section>
        
        

        <section class="section section-lg">
            <div class="container">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6 order-md-2">
                        <img src="img/theme/promo-1.png" class="img-fluid floating">
                    </div>
                    <div class="col-md-6 order-md-1">
                        <div class="pr-md-5">
                            <icon name="ni ni-settings-gear-65" class="mb-5" size="lg" type="success" shadow
                                  rounded></icon>
                            <h3>Why US?</h3>
                            <p>why to start with ASAH, because we have an advantage over other platforms.</p>
                            <ul class="list-unstyled mt-5">
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-settings-gear-65"></badge>
                                        <h6 class="mb-0">Connecting the Education Gap With Today's Industry</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-html5"></badge>
                                        <h6 class="mb-0">Providing Easy and Quality Education Access</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-satisfied"></badge>
                                        <h6 class="mb-0">Providing Classes at Affordable Prices</h6>
                                    </div>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section bg-secondary">
            <div class="container">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6">
                        <div class="card bg-default shadow border-0">
                            <img v-lazy="'img/theme/gedung.png'" class="card-img-top">
                            <blockquote class="card-blockquote">
                                <svg preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 583 95"
                                     class="svg-bg">
                                    <polygon points="0,52 583,95 0,95" class="fill-default"></polygon>
                                    <polygon points="0,42 583,95 683,0 0,95" opacity=".2" class="fill-default"></polygon>
                                </svg>
                                <h4 class="display-3 font-weight-bold text-white">ASAH COMPANY</h4>
                                <p class="lead text-italic text-white">ASAH is an online learning platform with thousands of course for creative and curious people, on topics including illustration, design, photography, accounting, financing, and more. On ASAH, members come together to find inspiration and take the next step in their creative journey.</p>
                            </blockquote>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="pl-md-5">
                            <icon name="ni ni-settings" class="mb-5" size="lg" type="warning" shadow rounded></icon>

                            <h3>Our Company</h3>
                           
                            <p>The pandemic is one reason we esthablised this company. beside we want to help other people to provide non-academic training. We also realize that not everyone can't go to formal school and in fact formal education has not been able to solve a problenm of unemployeement in Indonesia.</p>
                            
                            <a href="#" class="font-weight-bold text-warning mt-5">A beautiful UI Kit for impactful
                                websites</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section section-shaped my-0 overflow-hidden">
            <div class="shape shape-style-1 bg-gradient-success shape-skew">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container py-0">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6 order-lg-2 ml-lg-auto">
                        <div class="position-relative pl-md-5">
                            <img src="img/ill/ill-2.svg" class="img-center img-fluid">
                        </div>
                    </div>
                    <div class="col-lg-6 order-lg-1">
                        <div class="d-flex px-3">
                            <div>
                                <icon name="ni ni-building" size="lg" class="bg-gradient-white" color="primary" shadow
                                      rounded></icon>
                            </div>
                            <div class="pl-4">
                                <h4 class="display-3 text-white">Our Vission</h4>
                                <p class="text-white">The realization of training service with various learning methods that 
                                    are easy to understand and implemented both online and offline in accordance with the times with a broad scope
                                </p>
                            </div>
                            
                        </div>
                        <div class="d-flex px-3">
                            
                            
                        </div>
                        <div class="d-flex px-3">
                            <div>
                                <icon name="ni ni-building" size="lg" class="bg-gradient-white" color="primary" shadow
                                      rounded></icon>
                            </div>
                            <div class="pl-4">
                                <h4 class="display-3 text-white">Our Mission</h4>
                                
                            </div>
                            
                        </div>
                        <card shadow class="shadow-lg--hover mt-5">
                            <div class="d-flex px-3">
                                <div>
                                    <icon name="ni ni-satisfied" gradient="success" color="white" shadow
                                          rounded></icon>
                                </div>
                                <div class="pl-4">
                                    
                                    <p>provides a means where ASAH friends can experiment ,explore and collaborate to gain new experience and insight.</p>
                                    
                                </div>
                            </div>
                        </card>
                         <card shadow class="shadow-lg--hover mt-5">
                            <div class="d-flex px-3">
                                <div>
                                    <icon name="ni ni-satisfied" gradient="success" color="white" shadow
                                          rounded></icon>
                                </div>
                                <div class="pl-4">
                                    
                                    <p>create a variety of learning methods that are easy to understand.</p>
                                    
                                </div>
                            </div>
                        </card>
                        <card shadow class="shadow-lg--hover mt-5">
                            <div class="d-flex px-3">
                                <div>
                                    <icon name="ni ni-active-40" gradient="warning" color="white" shadow
                                          rounded></icon>
                                </div>
                                <div class="pl-4">
                                    
                                    <p>become a platform that can connect with various categories of non-formal learning.</p>
                               
                                </div>
                            </div>
                        </card>
                        <card shadow class="shadow-lg--hover mt-5">
                            <div class="d-flex px-3">
                                <div>
                                    <icon name="ni ni-active-40" gradient="warning" color="white" shadow
                                          rounded></icon>
                                </div>
                                <div class="pl-4">
                                    
                                    <p>provides classes that can accesed both online and offline.</p>
                               
                                </div>
                            </div>
                        </card>
                        
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg">
            <div class="container">
                <div class="row justify-content-center text-center mb-lg">
                    <div class="col-lg-8">
                        <h2 class="display-3">Marvelous company for talent and to build impactful solutions for you.</h2>
                        <p class="lead text-muted">Our service include programming, design, financing, and more. Our solutions are crafted to help you or business grow even more.</p>
                    </div>
                </div>
                <div class="row">
                   
                   
                   
                </div>
            </div>
        </section>
        <section class="section section-lg pt-0">
            <div class="container">
                <card gradient="warning"
                      no-body
                      shadow-size="lg"
                      class="border-0">
                    <div class="p-5">
                        <div class="row align-items-center">
                            <div class="col-lg-8">
                                <h3 class="text-white">Meet Our Team.</h3>
                                <p class="lead text-white mt-3">Highly professional and capable of running your business across all digital channels.</p>
                            </div>
                            <div class="col-lg-3 ml-lg-auto">
                                <base-button tag="a" href="#/profile"
                                             type="white" block size="lg">
                                   Our Team
                                </base-button>
                            </div>
                        </div>
                    </div>
                </card>
            </div>
        </section>
        <section class="section section-shaped my-0 overflow-hidden">
            <div class="shape shape-style-3 bg-gradient-default shape-skew">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container pt-lg pb-300">
                <div class="row text-center justify-content-center">
                    <div class="col-lg-10">
                        <h2 class="display-3 text-white">Start Now</h2>
                        <p class="lead text-white">Explore thousands of hands-on creative classes.
Start learning for free.</p>
                    </div>
                </div>
                <div class="row row-grid mt-5">
                    <div class="col-lg-4">
                        <icon name="ni ni-settings" size="lg" gradient="white" shadow round color="primary"></icon>
                        <h5 class="text-white mt-3">Get unlimited access to every class</h5>
                        
                    </div>
                    <div class="col-lg-4">
                        <icon name="ni ni-ruler-pencil" size="lg" gradient="white" shadow round color="primary"></icon>
                        <h5 class="text-white mt-3">Topics include illustration, design, photography, and more</h5>
                        
                    </div>
                    <div class="col-lg-4">
                        <icon name="ni ni-atom" size="lg" gradient="white" shadow round color="primary"></icon>
                        <h5 class="text-white mt-3">Taught by industry leaders & working professionals</h5>
                       
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg pt-lg-0 section-contact-us">
            <div class="container">
                <div class="row justify-content-center mt--300">
                    <div class="col-lg-8">
                        <card gradient="secondary" shadow body-classes="p-lg-5">
                            <h4 class="mb-1">Want to work with us?</h4>
                            <p class="mt-0">Your project is very important to us.</p>
                            <base-input class="mt-5"
                                        alternative
                                        placeholder="Your name"
                                        addon-left-icon="ni ni-user-run">
                            </base-input>
                            <base-input alternative
                                        placeholder="Email address"
                                        addon-left-icon="ni ni-email-83">
                            </base-input>
                            <base-input class="mb-4">
                                    <textarea class="form-control form-control-alternative" name="name" rows="4"
                                              cols="80" placeholder="Type a message..."></textarea>
                            </base-input>
                            <base-button type="default" round block size="lg">
                                Send Message
                            </base-button>
                        </card>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg">
            <div class="container">
                <div class="row row-grid justify-content-center">
                    <div class="col-lg-8 text-center">
                        <h2 class="display-3">Classes Taught by Experienced Tutor
                            <span class="text-success">Are you ready to improve your skills?</span>
                        </h2>
                        <p class="lead">Cause if you do, it can be yours for FREE. Hit the button below to navigate to
                           register page where you can join our membershop plan. Start a new classes and subcribe your favourite class!</p>
                        <div class="btn-wrapper">
                            <a href="#/register"
                               class="btn btn-primary mb-3 mb-sm-0">Join Membership</a>
                        </div>
                        <div class="text-center">
                            <h4 class="display-4 mb-5 mt-5">Our partnership</h4>
                            <div class="row justify-content-center">
                                <div class="col-lg-2 col-4">
                                    <a href="" target="_blank" data-toggle="tooltip"
                                       data-original-title="Bootstrap 4 - Most popular front-end component library">
                                        <img v-lazy="'https://s3.amazonaws.com/creativetim_bucket/tim_static_images/presentation-page/bootstrap.jpg'"
                                             class="img-fluid">
                                    </a>
                                </div>
                                <div class="col-lg-2 col-4">
                                    <a href="" target="_blank" data-toggle="tooltip"
                                       data-original-title="[Coming Soon] Sketch - Digital design toolkit">
                                        <img v-lazy="'https://s3.amazonaws.com/creativetim_bucket/tim_static_images/presentation-page/sketch.jpg'"
                                             class="img-fluid opacity-5">
                                    </a>
                                </div>
                                <div class="col-lg-2 col-4">
                                    <a href="" data-toggle="tooltip"
                                       data-original-title="[Coming Soon] Adobe Photoshop - Software for digital images manipulation">
                                        <img v-lazy="'https://s3.amazonaws.com/creativetim_bucket/tim_static_images/presentation-page/ps.jpg'"
                                             class="img-fluid  opacity-5">
                                    </a>
                                </div>
                                <div class="col-lg-2 col-4">
                                    <a href="" target="_blank" data-toggle="tooltip"
                                       data-original-title="Vue.js - The progressive javascript framework">
                                        <img v-lazy="'https://s3.amazonaws.com/creativetim_bucket/tim_static_images/presentation-page/vue.jpg'"
                                             class="img-fluid">
                                    </a>
                                </div>
                                <div class="col-lg-2 col-4">
                                    <a href="" target="_blank" data-toggle="tooltip"
                                       data-original-title="[Coming Soon] Angular - One framework. Mobile &amp; desktop">
                                        <img v-lazy="'https://s3.amazonaws.com/creativetim_bucket/tim_static_images/presentation-page/angular.jpg'"
                                             class="img-fluid opacity-5">
                                    </a>
                                </div>
                                <div class="col-lg-2 col-4">
                                    <a href="" target="_blank" data-toggle="tooltip"
                                       data-original-title="[Coming Soon] React - A JavaScript library for building user interfaces">
                                        <img v-lazy="'https://s3.amazonaws.com/creativetim_bucket/tim_static_images/presentation-page/react.jpg'"
                                             class="img-fluid opacity-5">
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </div>
</template>

<script>
export default {
  name: "home",
  components: {}
};


</script>
