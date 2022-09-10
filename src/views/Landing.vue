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
                                <p class="display-2   text-white">Online Learning Designed For Real Life</p>
                            </div>
                        </div>
                        
                        <div class="row">
                            <div class="col-lg-5">
                                
                                
                                <div class="btn-wrapper">
                    <base-input placeholder="Search"
                                addon-left-icon="ni ni-zoom-split-in">
                    </base-input>
                                    
                                </div>
                            </div>
                            <div class="col-sm-3">
                                <base-button tag="a"
                                                 href=""
                                                 class="mb-3 mb-sm-0"
                                                 type="primary"
                                                 icon="ni ni-cloud-download-95">
                                        Search
                                    </base-button>
                                    
                            </div>
                        </div>
                        <h5 class="text-white">Explore all courses</h5>
                    </div>
                </div>
            </section>
            <!-- 1st Hero Variation -->
        </div>
        <section class="section section-lg pt-lg-0 mt--200">
            <div class="container">
                 <h2 class="display-3 mb-4 text-white">All Courses</h2>
                <div class="row justify-content-center">
                   
                    <div class="col-lg-12">
                        <div class="row row-grid">
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <img v-lazy="'img/theme/anj1.jpg'" class="card-img-top">
                                    <h6 class="text-primary text-uppercase mt-4">Fundamentals of DSLR Photography</h6>
                                    <p class="description mt-10">This introductory photography class is a smart, inspiring way to get up to speed quickly. Taught by photographer Justin Bridges, you'll learn how to manually balance shutter speed, aperture, and ISO to achieve perfect exposure.</p>
                                    <div>
                                        <badge type="primary" rounded>design</badge>
                                        <badge type="primary" rounded>system</badge>
                                        <badge type="primary" rounded>creative</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="primary" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <img v-lazy="'img/theme/anj2.jpg'" class="card-img-top">
                                    <h6 class="text-default text-uppercase mt-4">Plants at Home: Uplift Your Spirit & Your Space</h6>
                                    <p class="description mt-10">Step into Christopher Griffin’s urban oasis, a Brooklyn apartment that’s home to over 160 plants and counting. As Plant Kween on Instagram, Christopher shares their love of plants as a tool for finding community, creativity, and calm</p>
                                    <div>
                                        <badge type="default" rounded>design</badge>
                                        <badge type="default" rounded>system</badge>
                                        <badge type="default" rounded>creative</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="default" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <img v-lazy="'img/theme/anj3.jpg'" class="card-img-top">
                                    <h6 class="text-success text-uppercase mt-4">Dynamic Brand Identity: Designing Logos That Evolve</h6>
                                    <p class="description mt-10">Paula Scher, partner in the New York office of Pentagram, walks us through process of creating a liquid identity—a recognizable, dynamic branding system that can be adapted across mediums. this class,  about researching an organization’s goals</p>
                                    <div>
                                        <badge type="success" rounded>design</badge>
                                        <badge type="success" rounded>system</badge>
                                        <badge type="success" rounded>creative</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="success" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="container pt-100">
                <div class="row justify-content-center">
                    <div class="col-lg-12">
                        <div class="row row-grid">
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <img v-lazy="'img/theme/anj4.jpg'" class="card-img-top">
                                    <h6 class="text-info text-uppercase mt-4">The Staples of Branding: From Purpose to Product</h6>
                                    <p class="description mt-3">oin streetwear icon Jeff Staple as he shares first-hand experience and advice for building a brand from purpose to product — essential and tactical advice for entrepreneurs, and fashion aspirants.</p>
                                    <div>
                                        <badge type="info" rounded>design</badge>
                                        <badge type="info" rounded>system</badge>
                                        <badge type="info" rounded>creative</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="info" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <img v-lazy="'img/theme/anj5.jpg'" class="card-img-top">
                                    <h6 class="text-danger text-uppercase mt-4">Storytelling 101: Character, Conflict, Context & Craft</h6>
                                    <p class="description mt-3">How do you write a story that feels alive? What makes a story different from an anecdote?

Join renowned urban fantasy writer Daniel José Older for a 40-minute dive into the fundamentals of narrative storytelling! </p>
                                    <div>
                                        <badge type="danger" rounded>business</badge>
                                        <badge type="danger" rounded>vision</badge>
                                        <badge type="danger" rounded>success</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="danger" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <img v-lazy="'img/theme/anj2.jpg'" class="card-img-top">
                                    <h6 class="text-light text-uppercase mt-4">Creative Nonfiction: Write Truth with Style</h6>
                                    <p class="description mt-3">The rise of sites like Medium and Longreads have inspired a resurgence in creative nonfiction—that compelling, leisurely writing that weaves true ideas and characters into stories that reveal as much about its readers as its subject</p>
                                    <div>
                                        <badge type="light" rounded>marketing</badge>
                                        <badge type="light" rounded>product</badge>
                                        <badge type="light" rounded>launch</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="light" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                        </div>
                    </div>
                </div>
                
            </div>
        </section>
       
        <section class="section bg-secondary">
            <div class="container">
                <div class="row row-grid align-items-center">
                    <h1 class="font-weight-bold"> Discover Course</h1>
                    <span class="font-weight-900">Explore new skills, deepen existing passions, and get lost in creativity. What you find just might surprise and inspire you</span>
                </div>
                <div class="row row-grid align-items-center">
                    <div class="col-md-6">
                        <div class="card bg-default shadow border-0">
                            <img v-lazy="'img/theme/asahimg.png'" class="card-img-top" style="height: 450px;">
                            <blockquote class="card-blockquote">
                                <svg preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 583 95"
                                     class="svg-bg">
                                    <polygon points="0,52 583,95 0,95" class="fill-default"></polygon>
                                    <polygon points="0,42 583,95 683,0 0,95" opacity=".2" class="fill-default"></polygon>
                                </svg>
                                <h4 class="display-3 font-weight-bold text-white">Introduction to Blockchain</h4>
                                <p class="lead text-italic text-white">Discover why blockchain is such a disruptive force across business, government and society. Blockchain technology sparked the creation of Bitcoin, a decentralized digital payment system, as well as other popular cryptocurrency systems.</p>
                            </blockquote>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="pl-md-5">
                            <card shadow class="shadow-lg--hover mt-5">
                            <div class="d-flex px-3">
                                <div>
                                    <icon name="ni ni-satisfied" gradient="success" color="white" shadow
                                          rounded></icon>
                                </div>
                                <div class="pl-4">  
                                    <h5 class="title text-success">C Programming: Advanced Data Types</h5>
                                    <p>Master effective ways to store your data in the C programming language using advanced data types such as structures and linked lists. Receive instant feedback on your code right within your browser.</p>
                                    <a href="#" class="text-success">Learn more</a>
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
                                    <h5 class="title text-warning">C Programming: Language Foundations</h5>
                                    <p>Master foundational concepts in the C programming language such as logical statements and arrays.</p>
                                    <a href="#" class="text-warning">Learn more</a>
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
                                    <h5 class="title text-warning">C Programming: Modular Programming and Memory Management</h5>
                                    <p>Enhance your coding skills along your path to becoming a proficient C programmer</p>
                                    <a href="#" class="text-warning">Learn more</a>
                                </div>
                            </div>
                        </card>
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
             <section class="section section-lg pt-0">
            <div class="container">
                <card gradient="info"
                      no-body
                      shadow-size="lg"
                      class="border-0 mb-sm">
                    <div class="p-5">
                        <div class="row align-items-center">
                            <div class="col-lg-8">
                                <h3 class="text-white">Basic Package</h3>
                                <p class="lead text-white mt-3">Basic includes: Full-video access, Education articels, Research and Publications.</p>
                            <h3 class="display-3 text-white">Rp. 1000.000/Month</h3>
                            </div>
                            <div class="col-lg-3 ml-lg-auto">
                                <base-button tag="a" href=""
                                             type="white" block size="lg">
                                    Subscribe
                                </base-button>
                            </div>
                        </div>
                    </div>
                </card>

                <card gradient="warning"
                      no-body
                      shadow-size="lg"
                      class="border-0 mb-sm">
                    <div class="p-5">
                        <div class="row align-items-center">
                            <div class="col-lg-8">
                                <h3 class="text-white">Intermediate package</h3>
                                <p class="lead text-white mt-3">Intermediate includes: Access to the world’s largest library of research, publications and market reports .​</p>
                                <h3 class="display-3 text-white">Rp. 2000.000/Month</h3>
                            </div>
                            <div class="col-lg-3 ml-lg-auto">
                                <base-button tag="a" href=""
                                             type="white" block size="lg">
                                    Subscribe
                                </base-button>
                            </div>
                        </div>
                    </div>
                </card>
                <card gradient="danger"
                      no-body
                      shadow-size="lg"
                      class="border-0 mb-sm">
                    <div class="p-5">
                        <div class="row align-items-center">
                            <div class="col-lg-8">
                                <h3 class="text-white">Premium Package</h3>
                                <p class="lead text-white mt-3">Premium includes: All access Basic Features, All access Intermediate features. also, Get unlimited access to the latest updates on the developments in the global Islamic economy.</p>
                                <h3 class="display-3 text-white">Rp. 5000.000/Month</h3>
                            </div>
                            <div class="col-lg-3 ml-lg-auto">
                                <base-button tag="a" href=""
                                             type="white" block size="lg">
                                    Subscribe
                                </base-button>
                            </div>
                        </div>
                    </div>
                </card>
            </div>
        </section>
          
        </section>

              <section class="section section-lg pt-lg-0 mt--150">
            <div class="container">
                 <h2 class="display-3 mb-4 text-white">All Courses</h2>
                <div class="row justify-content-center">
                   
                    <div class="col-lg-12">
                        <div class="row row-grid">
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <img v-lazy="'img/theme/anj6.jpg'" class="card-img-top">
                                    <h6 class="text-primary text-uppercase mt-4">Fundamentals of DSLR Photography</h6>
                                    <p class="description mt-10">This introductory photography class is a smart, inspiring way to get up to speed quickly. Taught by photographer Justin Bridges, you'll learn how to manually balance shutter speed, aperture, and ISO to achieve perfect exposure.</p>
                                    <div>
                                        <badge type="primary" rounded>design</badge>
                                        <badge type="primary" rounded>system</badge>
                                        <badge type="primary" rounded>creative</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="primary" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <img v-lazy="'img/theme/anj7.jpg'" class="card-img-top">
                                    <h6 class="text-default text-uppercase mt-4">Plants at Home: Uplift Your Spirit & Your Space</h6>
                                    <p class="description mt-10">Step into Christopher Griffin’s urban oasis, a Brooklyn apartment that’s home to over 160 plants and counting. As Plant Kween on Instagram, Christopher shares their love of plants as a tool for finding community, creativity, and calm</p>
                                    <div>
                                        <badge type="default" rounded>design</badge>
                                        <badge type="default" rounded>system</badge>
                                        <badge type="default" rounded>creative</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="default" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <img v-lazy="'img/theme/anj8.jpg'" class="card-img-top">
                                    <h6 class="text-success text-uppercase mt-4">Dynamic Brand Identity: Designing Logos That Evolve</h6>
                                    <p class="description mt-10">Paula Scher, partner in the New York office of Pentagram, walks us through process of creating a liquid identity—a recognizable, dynamic branding system that can be adapted across mediums. this class,  about researching an organization’s goals</p>
                                    <div>
                                        <badge type="success" rounded>design</badge>
                                        <badge type="success" rounded>system</badge>
                                        <badge type="success" rounded>creative</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="success" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="container pt-100">
                <div class="row justify-content-center">
                    <div class="col-lg-12">
                        <div class="row row-grid">
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <img v-lazy="'img/theme/anj9.jpg'" class="card-img-top">
                                    <h6 class="text-info text-uppercase mt-4">The Staples of Branding: From Purpose to Product</h6>
                                    <p class="description mt-3">oin streetwear icon Jeff Staple as he shares first-hand experience and advice for building a brand from purpose to product — essential and tactical advice for entrepreneurs, and fashion aspirants.</p>
                                    <div>
                                        <badge type="info" rounded>design</badge>
                                        <badge type="info" rounded>system</badge>
                                        <badge type="info" rounded>creative</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="info" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <img v-lazy="'img/theme/anj10.jpg'" class="card-img-top">
                                    <h6 class="text-danger text-uppercase mt-4">Storytelling 101: Character, Conflict, Context & Craft</h6>
                                    <p class="description mt-3">How do you write a story that feels alive? What makes a story different from an anecdote?

Join renowned urban fantasy writer Daniel José Older for a 40-minute dive into the fundamentals of narrative storytelling! </p>
                                    <div>
                                        <badge type="danger" rounded>business</badge>
                                        <badge type="danger" rounded>vision</badge>
                                        <badge type="danger" rounded>success</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="danger" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <img v-lazy="'img/theme/anj2.jpg'" class="card-img-top">
                                    <h6 class="text-light text-uppercase mt-4">Creative Nonfiction: Write Truth with Style</h6>
                                    <p class="description mt-3">The rise of sites like Medium and Longreads have inspired a resurgence in creative nonfiction—that compelling, leisurely writing that weaves true ideas and characters into stories that reveal as much about its readers as its subject</p>
                                    <div>
                                        <badge type="light" rounded>marketing</badge>
                                        <badge type="light" rounded>product</badge>
                                        <badge type="light" rounded>launch</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="light" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                        </div>
                    </div>
                </div>
                
            </div>
        </section>

        
        <section class="section section-lg">
            <div class="container">
                <div class="row justify-content-center text-center mb-lg">
                    <div class="col-lg-8">
                        <h2 class="display-3">About the instructors</h2>
                        <p class="lead text-muted">According to the National Oceanic and Atmospheric Administration,
                            Ted, Scambos, NSIDClead scentist, puts the potentially record maximum.</p>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy="'img/theme/team-1-800x800.jpg'"
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">Ryan Tompson</span>
                                    <small class="h6 text-muted">Professor, Harvard Business School</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="#" type="warning" icon="fa fa-twitter" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="#" type="warning" icon="fa fa-facebook" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="#" type="warning" icon="fa fa-dribbble" rounded
                                                 icon-only></base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy="'img/theme/team-2-800x800.jpg'"
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">Romina Hadid</span>
                                    <small class="h6 text-muted">Professor, Stanford University</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="#" type="primary" icon="fa fa-twitter" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="#" type="primary" icon="fa fa-facebook" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="#" type="primary" icon="fa fa-dribbble" rounded
                                                 icon-only></base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy="'img/theme/team-3-800x800.jpg'"
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">Alexander Smith</span>
                                    <small class="h6 text-muted">Professor, Telkom University</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="#" type="info" icon="fa fa-twitter" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="#" type="info" icon="fa fa-facebook" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="#" type="info" icon="fa fa-dribbble" rounded
                                                 icon-only></base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy="'img/theme/team-4-800x800.jpg'"
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">John Doe</span>
                                    <small class="h6 text-muted">Professor, Indonesia Education University</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="#" type="success" icon="fa fa-twitter" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="#" type="success" icon="fa fa-facebook" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="#" type="success" icon="fa fa-dribbble" rounded
                                                 icon-only></base-button>
                                </div>
                            </div>
                        </div>
                    </div>
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
                                <h3 class="text-white">Get critical career skills.</h3>
                                <p class="lead text-white mt-3">Executive Education courses from top universities offer the skills you need to pivot and expand your career.</p>
                            </div>
                            <div class="col-lg-3 ml-lg-auto">
                                <base-button tag="a" href="https://www.creative-tim.com/product/vue-argon-design-system"
                                             type="white" block size="lg">
                                    Find your course
                                </base-button>
                            </div>
                        </div>
                    </div>
                </card>
            </div>
        </section>
        
        <section class="section section-lg">
            <div class="container">
                <div class="row row-grid justify-content-center">
                    <div class="col-lg-8 text-center">
                        <h2 class="display-3">Interested in this course
                            <span class="text-success">Choose your path when you enroll.</span>
                        </h2>
                        <p class="lead">Your learning experience is grounded in cutting edge cognitive science. With more than two dozen distinct learning features to help you achieve your goals</p>
                        <div class="btn-wrapper">
                            <a href=""
                               class="btn btn-primary mb-3 mb-sm-0">Enroll now</a>
                        </div>
                        <div class="text-center">
                            <h4 class="display-4 mb-5 mt-5">Our Partnertship</h4>
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
