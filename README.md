
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Lavishly+Yours&family=Margarine&family=Montserrat:ital,wght@0,100..900;1,100..900&family=Mozilla+Headline:wght@200..700&family=PT+Sans+Narrow:wght@400;700&family=Satisfy&family=Sora:wght@100..800&family=Yellowtail&display=swap');

@import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Lavishly+Yours&family=Margarine&family=Montserrat:ital,wght@0,100..900;1,100..900&family=Mozilla+Headline:wght@200..700&family=PT+Sans+Narrow:wght@400;700&family=Satisfy&family=Sora:wght@100..800&family=Yellowtail&display=swap');
</style>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper/swiper-bundle.min.css" />
  <title>VVJK HOME SERVICES</title>
 </head>
  <style>

  
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Sora',sans-serif , 'Inter', sans-serif;
    }

    /* Navbar container */
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 40px;
      background: #fff;
      border-bottom: 1px solid #eee;
    }

    /* Logo */
    .logo {
      display: flex;
      align-items: center;
    }
    .logo img {
      height: 50px;
    }

    /* Menu */
    .nav-links {
      display: flex;
      list-style: none;
      gap: 30px;
    }

    .nav-links li  {
      text-decoration: none;
      color: white;
      font-size: 16px;
      transition: 0.3s;
    }

    .nav-links a  {
      text-decoration: none;
      color: #333;
      font-size: 16px;
      transition: 0.3s;
    }

    .nav-links li a:hover {
      color: #a82582;
    }



    /* Dropdown */
    .dropdown {
      position: relative;
    }
    .dropdown-content {
      display: none;
      position: absolute;
      top: 20px;
      left: 0;
      background: #a82582;
      min-width: 150px;
      box-shadow: 0px 4px 6px rgba(0,0,0,0.1);
      z-index: 100;
    }
    
    .dropdown-content a {
      display: block;
      padding: 10px;
      text-decoration: none;
      color: #ffffff;
    }
    .dropdown-content a:hover {
      background: #ffffff;
    }

    .dropdown:hover .dropdown-content {
      display: block;
    }

    /* Hamburger (hidden on desktop) */
    .hamburger {
      display: none;
      font-size: 26px;
      cursor: pointer;
    }

    /* Mobile */
    @media (max-width: 768px) {
      .nav-links {
        display: none;
        position: absolute;
        top: 70px;
        right: 0;
        background: #fff;
        flex-direction: column;
        width: 200px;
        box-shadow: 0px 4px 6px rgba(0,0,0,0.1);
        padding: 20px;
      }

      .nav-links.active {
        display: flex;
      }

      .hamburger {
        display: block;
      }
    }





 
    body {
      background: #f4f4f4;
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    .carousel {
      position: relative;
      max-width: 100%;
      margin: auto;
      overflow: hidden;
    }

    /* Slides */
    .carousel-slide {
      display: flex;
      transition: transform 0.5s ease-in-out;
    }

    .carousel-slide img {
      width: 100%;
      flex-shrink: 0;
    }

    /* Navigation buttons */
    .prev, .next {
      position: absolute;
      top: 50%;
      transform: translateY(-50%);
      font-size: 30px;
      font-weight: bold;
      background: rgba(0,0,0,0.5);
      color: white;
      padding: 10px;
      cursor: pointer;
      border: none;
      border-radius: 50%;
      user-select: none;
    }

    .prev { left: 15px; }
    .next { right: 15px; }

    /* Dots */
    .dots {
      text-align: center;
      position: absolute;
      bottom: 15px;
      width: 100%;
    }

    .dot {
      display: inline-block;
      height: 12px;
      width: 12px;
      margin: 0 5px;
      background: #bbb;
      border-radius: 50%;
      cursor: pointer;
    }

    .dot.active {
      background: #333;
    }

    /* Responsive */
    @media (max-width: 768px) {
      .prev, .next {
        font-size: 22px;
        padding: 8px;
      }
    }






   /* About us */  

    body {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      line-height: 1.6;
      background: #fff;
      color: #333;
    }

    .about-section {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 40px;
      padding: 60px 10%;
      flex-wrap: wrap;
    }

    /* Left image */
    .about-img {
      flex: 1;
      min-width: 300px;
    }
    .about-img img {
      width: 100%;
      border-radius: 8px;
    }

    /* Right content */
    .about-content {
      flex: 1.2;
      min-width: 300px;
    }


    .about-content h5 {
      font-size: 14px;
      letter-spacing: 2px;
      color: #9c0a75;
      text-transform: uppercase;
      margin-bottom: 10px;
    }

    .about-content h2 {
      color:#002060;
      font-size: 36px;
      font-weight: 700;
      margin-bottom: 20px;
    }

    .about-content p {
      font-size: 16px;
      margin-bottom: 20px;
      color: #555;
      text-align:justify;
    }

    .about-content .btn {
      margin-left:0;
      display: inline-block;
      background: #9c0a75;
      color: #fff;
      padding: 12px 28px;
      border-radius: 4px;
      text-decoration: none;
      font-weight: 600;
      transition: 0.3s;
    }
    .about-content .btn:hover {
      background: #002060;
    }

    /* Responsive */
    @media (max-width: 992px) {
      .about-section {
        flex-direction: column;
        text-align: center;
      }

      .about-content h2 {
        font-size: 28px;
      }
    }



    /* Service list */


body {
      background: #f7f8fc;
      margin: 0;
      padding:0;    
    }

    h4 {
      text-align: center;
      font-size: 35px;
      color: #002060;
      margin-bottom: 30px;
    }

    .swiper {
      width: 80%;
      padding-bottom: 50px;
    }

    .swiper-slide {
      background: #fff;
      border-radius: 16px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      transition: transform 0.3s ease;
    }

    .swiper-slide:hover {
      transform: translateY(-5px);
    }

    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .card-content {
      padding: 20px;
    }

    .card-content h3 {
      font-size: 20px;
      margin-bottom: 10px;
      color: #9c0a75;
    }

    .card-content p {
      text-align:justify;
      font-size: 0.9rem;
      color: #555;
      line-height: 1.4;
    }

    .btn {
      position:center;
      display: inline-block;
      margin-left:120px;
      background: #a92581;
      color: #fff;
      padding: 10px 15px;
      border-radius: 25px;
      text-decoration: none;
      font-size: 14px;
      transition: background 0.3s ease;
    }

    .btn:hover {
      background:#002060;
    }

    /* Swiper Pagination */
    .swiper-pagination-bullet {
      background: #999;
      opacity: 1;
    }

    .swiper-pagination-bullet-active {
      background: #a92581;
    }

    @media (max-width: 768px) {
      .card img {
        height: 160px;
      }
    }





/* how-we-work*/

body {
      margin: 0;
      background-color: #fff;
    }

    .how-we-work {
      background-color: #a92581;
      padding: 10px 20px;
      text-align: center;
      color: white;
      margin-top:80px;
    }

    .how-we-work h2 {
      font-size: 35px;
      margin-top: 20px;
      margin-left:5px;
      color:#fccd0a;
      position: relative;
    }

    .steps {
      display: flex;
      justify-content: center;
      align-items: flex-start;
      gap: 50px;
      flex-wrap: wrap;
    }

    .step {
      flex: 1;
      max-width: 250px;
      text-align: center;
    }

    .step img {
      width: 40px;
      height: 40px;
      margin-top: 25px;
      color:white;
    }

    .step h3 {
      font-size: 20px;
      margin-bottom: 25px;
      color: #fff;
      text-align: center;
    }

    .step p {
      font-size: 14px;
      color: #ffffff;
      line-height: 1.5;
    }

    .arrow {
      font-size: 24px;
      color: #fff;
      align-self: center;
      margin-bottom: 20px;
    }

    @media (max-width: 768px) {
      .steps {
        flex-direction: column;
        align-items: center;
      }
    
      .arrow {
        
        color:;
      }
    }

/* footer */
 
.footer {
  background-color:#002060;
  color: white;
  position: bottom;
  padding: 20px 20px;
  
}

.footer-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.footer-col {
  flex: 1 1 200px;
  margin: 10px;
}


.footer-col h3{
  color:#fccd0a;
  margin-bottom: 15px;
}

.footer-col ul {
  list-style: none;
  padding: 0;
}

.footer-col ul li {
  margin: 7px 0;
}

.brand p {
  margin: 10px 0;
  color: white;
  margin-top: 10px;
}

.social-icons {
  margin-top: 15px;
}

.social-icons i {
  font-size: 20px;
  margin-right: 15px;
  color: white;
  cursor: pointer;
}

.contact p {
  margin: 10px 0;
  color: white;
}

.footer-bottom {
  text-align: center;
  padding: 15px;
  background-color: #000033;
  color: white;
  margin-top: 40px;
}



</style>
</head>
<body>

  <nav class="navbar">
    <!-- Logo -->
    <div class="logo">
      <img src="file:///D:/VVJK%20LOGO%20-%20services%20.jpg" alt="Logo"> <!-- replace with your logo -->
    </div>

    <!-- Hamburger -->
    <div class="hamburger" onclick="toggleMenu()">☰</div>

    <!-- Menu Links -->
    <ul class="nav-links" id="navLinks">
      <li><a href="VVJK.HTML">Home</a></li>
      <li><a href="ABOUT.HTML">About Us</a></li>
      <li class="dropdown">
        <a href="#">Our Service ▼</a>
        <div class="dropdown-content">
          <a href="DEEP CLEANING SERVICE.HTML">Deep Cleaning</a>
          <a href="Painting Service.HTML">Painting</a>
          <a href="Interior Service.HTML">Interior</a>
          <a href="Electrical Service.HTML">Electrical</a>
          <a href="Plumbing Service.HTML">Plumbing</a>
          <a href="Renovation works.HTML">Renovation</a>
          <a href="Pest Control Service.html">Pest Control</a>
        </div>
      </li>
      <li><a href="BLOG.HTML">Blog</a></li>
      <li><a href="BOOK A SERVICE.HTML">Book Now</a></li>
    </ul>
  </nav>

  <script>
    function toggleMenu() {
      document.getElementById("navLinks").classList.toggle("active");
    }
  </script>






<!-- banner -->

  <div class="carousel">
    <div class="carousel-slide" id="slides">
      <img src="file:///D:/WEBSITE/Html%20&%20Css/HOME.jpg" alt="Slide 1">
      <img src="file:///D:/WEBSITE/Html%20&%20Css/HOME%202.jpg" alt="Slide 2">
      <img src="file:///D:/WEBSITE/Html%20&%20Css/HOME%203.jpg" alt="Slide 3">
    </div>

    <!-- Navigation -->
    <button class="prev" onclick="moveSlide(-1)">&#10094;</button>
    <button class="next" onclick="moveSlide(1)">&#10095;</button>

    <!-- Dots -->
    <div class="dots">
      <span class="dot active" onclick="currentSlide(0)"></span>
      <span class="dot" onclick="currentSlide(1)"></span>
      <span class="dot" onclick="currentSlide(2)"></span>
    </div>
  </div>

  <script>
    let index = 0;
    const slides = document.getElementById("slides");
    const dots = document.querySelectorAll(".dot");
    const totalSlides = slides.children.length;

    function showSlide(i) {
      index = (i + totalSlides) % totalSlides;
      slides.style.transform = `translateX(${-index * 100}%)`;
      dots.forEach(dot => dot.classList.remove("active"));
      dots[index].classList.add("active");
    }

    function moveSlide(step) {
      showSlide(index + step);
    }

    function currentSlide(i) {
      showSlide(i);
    }

    // Auto Slide
    setInterval(() => {
      moveSlide(1);
    }, 4000); // every 4 seconds
  </script>









  <section class="about-section">
    <!-- Image -->
    <div class="about-img">
      <img src="file:///H:/.shortcut-targets-by-id/1lVFdpOPMM_LI62yejNLoy5iDDbWzgtLO/VVJK/INTERIOR/COMMERCIAL/VVJK%20OFFICE/WhatsApp%20Image%202024-05-07%20at%2020.08.27_a5735d10.jpg" alt="About Us"> <!-- replace with your image -->
    </div>

    <!-- Content -->
    <div class="about-content">
      <h5>About VVJK</h5>
      <h2>Your Friendly Home Improvement Partner</h2>
      <p>
        <b>VVJK Home Services,</b> your trusted partner for transforming houses into homes. With 
        a commitment  to excellence , we offer a comprehensive  range of professional services,
        including interior works ,renovations ,electrical ,plumbing ,carpentry ,painting ,flooring
        & more.
      </p>
      <p>
        At VVJK, we take pride in being a one-stop solution for all your home needs, ensuring convenience and satisfaction.
      </p>
      <a href="ABOUT.HTML" class="btn">Read More</a>
    </div>
  </section>




<!-- Service list-->

  <h4 style="text-align:center; margin-bottom:20px;">Our Services</h2>

  <div class="swiper mySwiper">
    <div class="swiper-wrapper">
      
      <!-- 9 Service Cards -->
      <div class="swiper-slide">
        <div class="card">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQvfKVBGtb_qtU_nTrPbfcHEMVQalEAQS5sTA&s" alt="Service 1">
          <div class="card-content">
            <h3>Deep Cleaning</h3>
            <p>A complete cleaning solution that removes dirt, dust, and germs, keeping your home or office fresh, hygienic, and spotless.</p>
            <br><a href="DEEP CLEANING SERVICE.HTML" class="btn">Book Now</a>
          </div>

        </div>
      </div>

      <div class="swiper-slide">
        <div class="card">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRqY8Iq0opXUrO5egCGhx6WSUWpPndCf-NoSQ&s" alt="Service 2">
          <div class="card-content">
            <h3>Painting</h3>
            <p>Transform your walls with professional painting services that add color, life, and lasting style to interiors and exteriors.</p>
            <br><a href="Painting Service.HTML" class="btn">Book Now</a>
          </div>
        </div>
      </div>

      <div class="swiper-slide">
        <div class="card">
          <img src="  https://chiedesign.in/wp-content/uploads/2022/09/Luxury-Interiors-Living-Room-1080x675.jpg" alt="Service 3">
          <div class="card-content">
            <h3>Interior</h3>
            <p>Modern interior solutions designed to maximize comfort, space, and beauty. Stylish designs tailored to your lifestyle.</p>
            <br><a href="Interior Service.HTML" class="btn">Book Now</a>
          </div>
        </div>
      </div>

      <div class="swiper-slide">
        <div class="card">
          <img src="https://t4.ftcdn.net/jpg/01/70/17/97/360_F_170179753_piUSFjn4xlwAKaIU14gs6FnCVij2wckc.jpg" alt="Service 4">
          <div class="card-content">
            <h3>Electrical</h3>
            <p>Safe and reliable electrical services for installation, repair, and maintenance. Ensure uninterrupted power with expert solutions.</p>
            <br><a href="Electrical Service.HTML" class="btn">Book Now</a>
          </div>
        </div>
      </div>

      <div class="swiper-slide">
        <div class="card">
          <img src="https://img.freepik.com/premium-photo/plumber-tool…ir-service-assemble-install-concept_887079-53.jpg" alt="Service 5">
          <div class="card-content">
            <h3>Plumbing</h3>
            <p>Quick and efficient plumbing solutions, from leak repairs to full pipeline installations keeping your water flow hassle-free.</p>
            <br><a href="Plumbing Service.HTML" class="btn">Book Now</a>
          </div>
        </div>
      </div>

      <div class="swiper-slide">
        <div class="card">
          <img src="https://img.freepik.com/premium-photo/bright-indoo…ght_886588-78900.jpg?semt=ais_incoming&w=740&q=80" alt="Service 7">
          <div class="card-content">
            <h3>Renovation</h3>
            <p>Upgrade your home or office with customized renovation services. We bring new life to old spaces with modern finishes.</p>
            <br><a href="Renovation works.HTML" class="btn">Book Now</a>
          </div>
        </div>
      </div>

      <div class="swiper-slide">
        <div class="card">
          <img src="https://t3.ftcdn.net/jpg/10/08/60/00/360_F_1008600060_ZkyIm1v1tGIIeFyx2DyewYBdtizZX044.jpg" alt="Service 8">
          <div class="card-content">
            <h3>Pest Control</h3>
            <p>Protect your home from termites, rodents, and insects with safe, long-lasting pest control for a healthier environment.</p>
            <br><a href="Pest Control Service.html" class="btn">Book Now</a>
          </div>
        </div>
      </div>

    </div>

    <!-- Pagination -->
    <div class="swiper-pagination"></div>
  </div>

  <!-- Swiper JS -->
  <script src="https://cdn.jsdelivr.net/npm/swiper/swiper-bundle.min.js"></script>

  <script>
    var swiper = new Swiper(".mySwiper", {
      slidesPerView: 3,
      spaceBetween: 20,
      pagination: {
        el: ".swiper-pagination",
        clickable: true,
      },
      breakpoints: {
        0: {
          slidesPerView: 1
        },
        768: {
          slidesPerView: 2
        },
        1024: {
          slidesPerView: 3
        }
      }
    });
  </script>







<!-- how-we-work -->

<section class="how-we-work">

    <h2>How We Work</h2>
    <div class="steps">
      <!-- Step 1 -->
      <div class="step">
        <img src="https://img.icons8.com/ios-filled/100/ffffff/phone.png" alt="Register Icon">
        <h3>Book your service</h3>
        <p>
          Schedule your Service Request on the Call<br/>
        </p>
      </div>

      <div class="arrow">→</div>

      <!-- Step 2 -->
      <div class="step">
        <img src="https://img.icons8.com/ios-filled/100/ffffff/clock--v1.png" alt="Clock Icon">
        <h3>Site Visit & Quotation</h3>
        <p>
          We visit the site to assess its condition, then provide a quotation
        </p>
      </div>

      <div class="arrow">→</div>

      <!-- Step 3 -->
      <div class="step">
        <img src="https://img.icons8.com/ios-filled/100/ffffff/home.png" alt="Home Icon">
        <h3>Execution</h3>
        <p>
          Efficiently executing site work with precision, safety, and timely delivery
        </p>
      </div>
    
    <div class="arrow">→</div>

      <!-- Step 4 -->
      <div class="step">
        <img src="https://img.icons8.com/ios-filled/50/ffffff/settings.png" alt="Solution Icon">
        <h3>Hand over</h3>
        <p>
          Site work has been completed and formally handed over for your use
        </p>
      </div>
  </div>
  </section>



<!-- footer design -->
 

<footer class="footer">
    <div class="footer-container">
      <div class="footer-col brand">
        <p>VVJK Home Services, your<br>trusted partner for transforming<br> houses into homes.</p>
        <div class="social-icons">
          <i class="fab fa-facebook-f"></i>
          <i class="fab fa-twitter"></i>
          <i class="fab fa-youtube"></i>
          <i class="fab fa-linkedin-in"></i>
        </div>
      </div>

      <div class="footer-col">
        <h3>Services</h3>
        <ul>
          <li>Deep Cleaning Services</li>
          <li>Painting Service</li>
          <li>Interior Service</li>
          <li>Electrical Service</li>
          <li>Plumbing Service</li>
          <li>Carpentry Service</li>
          <li>Renovation works</li>
          <li>Pest Control Service</li>
        </ul>
      </div>

      <div class="footer-col">
        <h3>Company</h3>
        <ul>
          <li>Home</li>
          <li>About us</li>
          <li>Services</li>
          <li>Blog</li>
        </ul>
      </div>

      <div class="footer-col contact">
        <h3>Contact</h3>
        <p><i class="fas fa-envelope"></i> info@vvjkhomeservices.com</p>
        <p><i class="fas fa-phone"></i> Call: +91 70100 75201</p>
        <p><i class="fas fa-map-marker-alt"></i> No.4, Ground Floor, D-Block,<br> 2nd Avenue (Extn),
        Anna Nagar East,<br>Chennai-600 102</p>
      </div>
    </div>

    <div class="footer-bottom">
      <p>Copyright 2025. All Rights Reserved.</p>
    </div>
  </footer>

</body>
</html>
