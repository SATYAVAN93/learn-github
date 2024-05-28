Auther - Satyavan Kumar
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap 5 Practic</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/index.js">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Anton&family=Poetsen+One&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
    
</head>
<body>
<!--===============================================================================================================
                                                  header section start
================================================================================================================= -->
    <header class="bg-success text-white">
        <nav class="navbar navbar-expand-lg py-4 ">
            <div class="container">
              <a class="navbar-brand text-white fs-4" href="#">Object</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ms-auto mb-2 mb-lg-0 fs-5 text-white">
                  <li class="nav-item">
                    <a class="nav-link active text-white" aria-current="page" href="#Home">Home</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link text-white-50" href="#about">About</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link text-white-50" href="#servics">Servics</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link text-white-50" href="#Portfolio">Porfolio</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link text-white-50" href="#">Team</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link text-white-50" href="#">Blog</a>
                  </li>
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle text-white-50" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                      Dropdown
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                      <li><a class="dropdown-item" href="#">Action</a></li>
                      <li><a class="dropdown-item" href="#">Another action</a></li>
                      <li><hr class="dropdown-divider"></li>
                      <li><a class="dropdown-item" href="#">Something else here</a></li>
                    </ul>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link text-white-50" href="#">Contact</a>
                  </li>
                </form>
              </div>
            </div>
          </nav>
          <section id="hero" class="hero my-5">
            <div class="container position-relative">
              <div class="row gy-5" data-aos="fade-in">
                <div class="col-lg-6 order-2 order-lg-1 d-flex flex-column justify-content-center text-center text-lg-start my-5">
                  <h2 class="">Welcome to <span>Technologie</span></h2>
                  <p class="text-white-50">Sed autem laudantium dolores. Voluptatem itaque ea consequatur eveniet. Eum quas beatae cumque eum quaerat.</p>
                  <div class="d-flex justify-content-center justify-content-lg-start">
                    <a href="#about" class="btn-get-started mt-3">Get Started</a>
                    <a href="https://www.youtube.com/watch?v=LXb3EKWsInQ" class="glightbox btn-watch-video d-flex align-items-center mt-3"><i class="bi bi-play-circle"></i><span>Watch Video</span></a>
                  </div>
                </div>
                <div class="col-lg-6 order-1 order-lg-2 p-4">
                  <img src="hero-img.svg" class="img-fluid" alt="" data-aos="zoom-out" data-aos-delay="100">
                </div>
              </div>
            </div>
            </div>
          </section>
          <!-- End Hero Section -->
          <section class="card-small">
            <div class="container">
              <div class="row">
                <div class="col-sm-12 col-md-6 col-lg-3 col-12">
                  <div class="card bg-success text-white text-center">
                    <div class="card-body ">
                      <h4 class="fs-5">Learn More</h4>
                    </div>
                  </div>
                </div>
                <div class="col-sm-12 col-md-6 col-lg-3 col-12">
                  <div class="card bg-success text-white text-center">
                    <div class="card-body">
                      <h4 class="fs-5">Bihar Travil</h4>
                    </div>
                  </div>
                </div>
                <div class="col-sm-12 col-md-6 col-lg-3 col-12">
                  <div class="card bg-success text-white text-center">
                    <div class="card-body">
                      <h4 class="fs-5">Chandigarh</h4>
                    </div>
                  </div>
                </div>
                <div class="col-sm-12 col-md-6 col-lg-3 col-12">
                  <div class="card bg-success text-white text-center">
                    <div class="card-body">
                      <h4 class="fs-5">Mumbai </h4>
                    </div>
                  </div>
                </div>
              </div>
            </div>
        </section>
</header>
<!--===============================================================================================================
                                                  header section end
================================================================================================================= -->

<!-- ====================================================================================================================
                                                  about section start
=================================================================================================================-->
<section id="about" class="about">
  <div class="container">
   <div class="section-header my-5">
    <h2 class="text-center">About<span class="text-primary"></span></h2>
    <hr / class="w-25 m-auto">
    <p class="text-center mt-3">Aperiam dolorum et et wuia molestias qui eveniet numquam nihil porro incidunt dolores placeat</p>
   </div>
   <div class="row">
    <div class="col-sm-12 col-md-6 col-lg-6 col-12">
      <div class="card mb-3">
        <img src="about.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Voluptatem dignissimos</h5>
          <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
          <p class="card-text"><small class="text-muted"></small></p>
        </div>
      </div>
    </div>
    <div class="col-sm-12 col-md-6 col-lg-6 col-12">
      <div class="card mb-3">
        <img src="about-2.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Ullamco laboris </h5>
          <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
          <p class="card-text"><small class="text-muted"></small></p>
        </div>
      </div>
    </div>
   </div>
   <div class="row">
   <div class="col-sm-12 col-md-6 col-lg-6 col-12 my-5">
    <div class="img my-5">
    <img src="stats-img.svg" alt="">
    </div>
   </div>
   <div class="col-sm-12 col-md-6 col-lg-6 col-12">
    <div class="caption">
      <p class="fw-normal"><span class="fs-2 bold fw-bold ">232</span> Happy Clients consequuntur quae diredo para mesta</p>
      <p class="fw-normal"><span class="fs-2 bold fw-bold">521</span> Projects adipisci atque cum quia aut</p>
      <p class="fw-normal"><span class="fs-2 bold fw-bold">453</span> Hours Of Support aut commodi quaerat</p>
    </div>
   </div>
   </div>
 </div>
 <div class="container-fluid">
  <div class="row ms-5">
    <div class="col-sm-12 col-md-6 col-lg-6 col-12 ">
      <div class="caption caption-to-call py-5 mt-5">
        <h5 class="fs-3 text-white">Call To Action</h5>
        <p class="border-0 text-white-50 py-4">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        <a href="" class="mt-4">Call To Action</a>
      </div>
    </div>
    <div class="col-sm-12 col-md-6 col-lg-6 col-12">
      <div class="img my-5">
        <img src="call-action-removebg-preview.png" alt="">
        </div>
    </div>
   </div>
 </div>
</section>
<!--=================================================================================================================
                                                  about section end
=================================================================================================================-->

<!--=================================================================================================================
                                                  Servics section end
=================================================================================================================-->
<section class="servics our-services bg-light py-5 " id="servics">
    <div class="container">
      <h2 class="text-center">Our<span class="text-primary">Services</span></h2>
      <hr / class="w-25 m-auto">
      <div class="row">
        <div class="col-sm-12 col-md-4 col-lg-4 col-12 my-5 p-4">
          <div class="card border rounded-2 bg-white text-right py-4 ps-4">
            <img src="icon/activity.png" alt="">
            <h4 class="mt-3">Nesciunt Mete</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod, possimus numquam maiores praesentium voluptatum architecto?</p>
            <a href="#" class="py-2 ">Learn More</a>
          </div>
        </div>
        <div class="col-sm-12 col-md-4 col-lg-4 col-12 my-5 p-4">
          <div class="card border rounded-2 bg-white text-right py-4 ps-4">
            <img src="icon/radio.png" alt="">
            <h4 class="mt-3">Nesciunt Mete</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod, possimus numquam maiores praesentium voluptatum architecto?</p>
            <a href="#" class="py-2 ">Learn More</a>
          </div>
        </div>
        <div class="col-sm-12 col-md-4 col-lg-4 col-12 my-5 p-4">
          <div class="card border rounded-2 bg-white text-right py-4 ps-4">
            <img src="icon/live.png" alt="">
            <h4 class="mt-3">Nesciunt Mete</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod, possimus numquam maiores praesentium voluptatum architecto?</p>
            <a href="#" class="py-2 ">Learn More</a>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-sm-12 col-md-4 col-lg-4 col-12  p-4">
          <div class="card border rounded-2 bg-white text-right py-4 ps-4">
            <img src="icon/message.png" alt="">
            <h4 class="mt-3">Nesciunt Mete</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod, possimus numquam maiores praesentium voluptatum architecto?</p>
            <a href="#" class="py-2 ">Learn More</a>
          </div>
        </div>
        <div class="col-sm-12 col-md-4 col-lg-4 col-12 p-4">
          <div class="card border rounded-2 bg-white text-right py-4 ps-4">
            <img src="icon/radio.png" alt="">
            <h4 class="mt-3">Nesciunt Mete</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod, possimus numquam maiores praesentium voluptatum architecto?</p>
            <a href="#" class="py-2 ">Learn More</a>
          </div>
        </div>
        <div class="col-sm-12 col-md-4 col-lg-4 col-12 p-4">
          <div class="card border rounded-2 bg-white text-right py-4 ps-4">
            <img src="icon/calendar.png" alt="">
            <h4 class="mt-3">Nesciunt Mete</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod, possimus numquam maiores praesentium voluptatum architecto?</p>
            <a href="#" class="py-2 ">Learn More</a>
          </div>
        </div>
      </div>
    </div>
</section>
<!--=================================================================================================================
                                                  Servics section end
=================================================================================================================-->


<!--========================================testimonial section start=========================================== -->
<section class="testimonial text-center">
  <div class="container">
      <div class="heading white-heading">
          Testimonial
      </div>
      <div id="testimonial4" class="carousel slide testimonial4_indicators testimonial4_control_button thumb_scroll_x swipe_x" data-ride="carousel" data-pause="hover" data-interval="5000" data-duration="2000">
       
          <div class="carousel-inner" role="listbox">
              <div class="carousel-item active">
                  <div class="testimonial4_slide">
                      <img src="team4.jpg" class="img-circle img-responsive\">
                      <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. </p>
                      <h4>Client 1</h4>
                  </div>
              </div>
              <div class="carousel-item">
                  <div class="testimonial4_slide">
                      <img src="s2.jpg" class="img-circle img-responsive" /><p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. </p>
                      <h4>Client 2</h4>
                  </div>
              </div>
              <div class="carousel-item">
                  <div class="testimonial4_slide">
                      <img src="team4.jpg" class="img-circle img-responsive" />
                      <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. </p>
                      <h4>Client 3</h4>
                  </div>
              </div>
          </div>
      </div>
  </div>
</section>
<!--========================================testimonial section end=========================================== -->


<!--========================================Portfolio section end=========================================== -->
<section id="Portfolio" class="Portfolio my-5 bg-white" >
<div class="container">
  <h2 class="text-center">Our<span class="text-primary">Portfolio</span></h2>
  <hr / class="w-25 m-auto">
  <div class="row">
    <div class="col-sm-12 col-md-4 col-lg-4 col-12  p-4">
      <div class="card border rounded-2 bg-white text-right my-5">
        <img src="img/app-1.jpg " alt="">
        <h5 class="mt-3 ms-4">App 1</h5>
        <p class="mt-2 ms-4">Lorem ipsum dolor sit amet consectetur</p>
      </div>
    </div>
    <div class="col-sm-12 col-md-4 col-lg-4 col-12  p-4">
      <div class="card border rounded-2 bg-white text-right my-5">
        <img src="img/app-2.jpg " alt="">
        <h5 class="mt-3 ms-4">App 2</h5>
        <p class="mt-2 ms-4">Lorem ipsum dolor sit amet consectetur</p>
      </div>
    </div>
    <div class="col-sm-12 col-md-4 col-lg-4 col-12  p-4">
      <div class="card border rounded-2 bg-white text-right my-5">
        <img src="img/app-3.jpg " alt="">
        <h5 class="mt-3 ms-4">App 3</h5>
        <p class="mt-2 ms-4">Lorem ipsum dolor sit amet consectetur</p>
      </div>
    </div>
  </div>

  <div class="row">
    <div class="col-sm-12 col-md-4 col-lg-4 col-12  p-4">
      <div class="card border rounded-2 bg-white text-right my-1">
        <img src="img/books-1.jpg " alt="">
        <h5 class="mt-3 ms-4">Books 1</h5>
        <p class="mt-2 ms-4">Lorem ipsum dolor sit amet consectetur</p>
      </div>
    </div>
    <div class="col-sm-12 col-md-4 col-lg-4 col-12  p-4">
      <div class="card border rounded-2 bg-white text-right my-1">
        <img src="img/books-3.jpg " alt="">
        <h5 class="mt-3 ms-4">Books 2</h5>
        <p class="mt-2 ms-4">Lorem ipsum dolor sit amet consectetur</p>
      </div>
    </div>
    <div class="col-sm-12 col-md-4 col-lg-4 col-12  p-4">
      <div class="card border rounded-2 bg-white text-right my-1">
        <img src="img/branding-1.jpg" alt="">
        <h5 class="mt-3 ms-4">Branding 1</h5>
        <p class="mt-2 ms-4">Lorem ipsum dolor sit amet consectetur</p>
      </div>
    </div>
  </div>

  <div class="row">
    <div class="col-sm-12 col-md-4 col-lg-4 col-12  p-4">
      <div class="card border rounded-2 bg-white text-right my-1">
        <img src="img/branding-3.jpg" alt="">
        <h5 class="mt-3 ms-4">Branding 1</h5>
        <p class="mt-2 ms-4">Lorem ipsum dolor sit amet consectetur</p>
      </div>
    </div>
    <div class="col-sm-12 col-md-4 col-lg-4 col-12  p-4">
      <div class="card border rounded-2 bg-white text-right my-1">
        <img src="img/product-1.jpg" alt="">
        <h5 class="mt-3 ms-4">Product 1</h5>
        <p class="mt-2 ms-4">Lorem ipsum dolor sit amet consectetur</p>
      </div>
    </div>
    <div class="col-sm-12 col-md-4 col-lg-4 col-12  p-4">
      <div class="card border rounded-2 bg-white text-right my-1">
        <img src="img/product-2.jpg" alt="">
        <h5 class="mt-3 ms-4">Product 1</h5>
        <p class="mt-2 ms-4">Lorem ipsum dolor sit amet consectetur</p>
      </div>
    </div>
  </div>
</div>
</section>

<!--========================================Portfolio section end=========================================== -->

<!--========================================blog section st================================================= -->
<section id="blog" class="blog blog-item">
  <div class="container">
    <h2 class="text-center">Our<span class="text-primary"> Blogs </span></h2>
    <hr / class="w-25 m-auto">
    <div class="row">
      <div class="col-sm-12 col-md-4 col-lg-4 col-12 my-5">
        <div class="card border rounded-2 bg-white text-right my-1">
          <img src="blog/s3.jpg" alt="">
          <p class=" ms-4">Politics</p>
          <h5 class="ms-4 mygeading">Dolorum optio tempore voluptas dignissimos</h5>
          <img src="blog/s3.jpg" class="auther-img ms-4" alt="">
          <p class="mx-4">Maria Doe</p>
        </div>
      </div>
      <div class="col-sm-12 col-md-4 col-lg-4 col-12 my-5">
        <div class="card border rounded-2 bg-white text-right my-1">
          <img src="blog/team2.jpg" alt="">
          <p class=" ms-4">Politics</p>
          <h5 class="ms-4 mygeading">Dolorum optio tempore voluptas dignissimos</h5>
          <img src="blog/team6.jpg" class="auther-img ms-4" alt="">
          <p class="mx-4">Maria Doe</p>
        </div>
      </div>
      <div class="col-sm-12 col-md-4 col-lg-4 col-12 my-5">
        <div class="card border rounded-2 bg-white text-right my-1">
          <img src="blog/team6.jpg" alt="">
          <p class=" ms-4">Politics</p>
          <h5 class="ms-4 mygeading">Dolorum optio tempore voluptas dignissimos</h5>
          <img src="blog/team2.jpg" class="auther-img ms-4" alt="">
          <p class="mx-4">Maria Doe</p>
        </div>
      </div>
    </div>
  </div>
</section>
<!--========================================blog section end================================================ -->

    <!-- ======= Contact Section ======= -->
    <section id="contact" class="contact">
      <div class="container" data-aos="fade-up">

        <div class="section-header">
          <h2 class="text-center">Our<span class="text-primary"> Contact </span></h2>
          <hr / class="w-25 m-auto">
          <p>Nulla dolorum nulla nesciunt rerum facere sed ut inventore quam porro nihil id ratione ea sunt quis dolorem dolore earum</p>
        </div>

        <div class="row gx-lg-0 gy-4">

          <div class="col-lg-4">

            <div class="info-container d-flex flex-column align-items-center justify-content-center">
              <div class="info-item d-flex">
                <i class="bi bi-geo-alt flex-shrink-0"></i>
                <div>
                  <h4>Location:</h4>
                  <p>A108 Adam Street, New York, NY 535022</p>
                </div>
              </div><!-- End Info Item -->

              <div class="info-item d-flex">
                <i class="bi bi-envelope flex-shrink-0"></i>
                <div>
                  <h4>Email:</h4>
                  <p><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="8ae3e4ece5caeff2ebe7fae6efa4e9e5e7">[email&#160;protected]</a></p>
                </div>
              </div><!-- End Info Item -->

              <div class="info-item d-flex">
                <i class="bi bi-phone flex-shrink-0"></i>
                <div>
                  <h4>Call:</h4>
                  <p>+1 5589 55488 55</p>
                </div>
              </div><!-- End Info Item -->

              <div class="info-item d-flex">
                <i class="bi bi-clock flex-shrink-0"></i>
                <div>
                  <h4>Open Hours:</h4>
                  <p>Mon-Sat: 11AM - 23PM</p>
                </div>
              </div><!-- End Info Item -->
            </div>

          </div>

          <div class="col-lg-8">
            <form action="forms/contact.php" method="post" role="form" class="php-email-form">
              <div class="row">
                <div class="col-md-6 form-group">
                  <input type="text" name="name" class="form-control" id="name" placeholder="Your Name" required>
                </div>
                <div class="col-md-6 form-group mt-3 mt-md-0">
                  <input type="email" class="form-control" name="email" id="email" placeholder="Your Email" required>
                </div>
              </div>
              <div class="form-group mt-3">
                <input type="text" class="form-control" name="subject" id="subject" placeholder="Subject" required>
              </div>
              <div class="form-group mt-3">
                <textarea class="form-control" name="message" rows="7" placeholder="Message" required></textarea>
              </div>
              <div class="my-3">
                <div class="loading">Loading</div>
                <div class="error-message"></div>
                <div class="sent-message">Your message has been sent. Thank you!</div>
              </div>
              <div class="text-center"><button type="submit">Send Message</button></div>
            </form>
          </div><!-- End Contact Form -->

        </div>

      </div>
    </section><!-- End Contact Section -->
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
 <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
</body>
</html>
