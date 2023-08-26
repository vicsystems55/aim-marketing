<script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main>
    <div class="preloader">
    <div>
      <div class="spinner spinner-3"></div>
    </div>
  </div>
  <!-- preloader end -->
  <!-- header -->
  <header id="stickyHeader">
    <div class="container">
      <div class="top-bar">
        <div class="logo">
          <a href="#">
            <img alt="logo" src="assets/img/logo-b.png">
          </a>
        </div>
        <nav class="d-none">
          <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#team">Team</a></li>
            <li><a href="#pricing">Pricing</a></li>
            <li><a href="#faq’s">Faq’s</a></li>
          </ul>
        </nav>
        <a href="callto:+12344502086"><i>
            <svg height="112" viewBox="0 0 24 24" width="112" xmlns="http://www.w3.org/2000/svg">
              <g clip-rule="evenodd" fill="rgb(255255,255)" fill-rule="evenodd">
                <path
                  d="m7 2.75c-.41421 0-.75.33579-.75.75v17c0 .4142.33579.75.75.75h10c.4142 0 .75-.3358.75-.75v-17c0-.41421-.3358-.75-.75-.75zm-2.25.75c0-1.24264 1.00736-2.25 2.25-2.25h10c1.2426 0 2.25 1.00736 2.25 2.25v17c0 1.2426-1.0074 2.25-2.25 2.25h-10c-1.24264 0-2.25-1.0074-2.25-2.25z">
                </path>
                <path
                  d="m10.25 5c0-.41421.3358-.75.75-.75h2c.4142 0 .75.33579.75.75s-.3358.75-.75.75h-2c-.4142 0-.75-.33579-.75-.75z">
                </path>
                <path
                  d="m9.25 19c0-.4142.33579-.75.75-.75h4c.4142 0 .75.3358.75.75s-.3358.75-.75.75h-4c-.41421 0-.75-.3358-.75-.75z">
                </path>
              </g>
            </svg>
          </i><b> +234 803 783 5670</b></a>
      </div>
    </div>
  </header>
  <!-- header end -->
  <section class="hero-sectio  " style="padding-top: 140px;">
    <div class="container">
      <div class="row ">
        <div class="col-lg-5">
          <div class="hero-text">
            <h2 calss="text-capitalize">Global Project  <span>International Initiative</span></h2>
            <p class="pt-0">The vision is to empower the african 🌍 youth globally. With this globally initiative selected partners can control global market share, without manufacturing, producing, logistics, international certificates or road marketing</p>
            <div class="review d-none">
              <img alt="img" src="assets/img/google-b.png">
              <h6>4.9 <span>out of 5</span></h6>
              <ul class="star">
                <li><i class="fa-solid fa-star"></i></li>
                <li><i class="fa-solid fa-star"></i></li>
                <li><i class="fa-solid fa-star"></i></li>
                <li><i class="fa-solid fa-star"></i></li>
                <li><i class="fa-solid fa-star"></i></li>
              </ul>
            </div>
          </div>
        </div>
        <div class="col-lg-7">
          
          <div class="">
            <!-- <iframe width="853" height="480"
              src="https://www.youtube.com/embed/i4QoHO89HqI"
              title="Get Started Today"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
              allowfullscreen></iframe> -->

              <video width="100%" controls autoplay loop class="z-index: 20;">
                <source :src="'assets/img/paulsmarketing.mp4'" type="video/mp4" />
                <source :src="'assets/img/paulsmarketing.mp4'" type="video/webm" />
                Your browser does not support the video tag.
            </video>
            </div>
          <img alt="shadow" class="shado" src="assets/img/shadow.png">
        </div>
      </div>
    </div>
  </section>
 

  <section class="gap ">

    <h3 class="text-center py-2">Get Started today</h3>

    <div style="max-width: 500px;" class=" mx-auto px-5">
      <div class="form-group py-2">
        <label for="">1. Fullname</label>
        <input type="text" class="form-control">
      </div>

      <div class="form-group py-2">
        <label for="">2. Phone number</label>
        <input type="text" class="form-control">
      </div>


      <div class="form-group py-2">
        <label for="">3. Email</label>
        <input type="text" class="form-control">
      </div>

      <div class="form-group py-2">
        <label for="">4. Would you like to be in business for yourself or work for someone else?</label>

        <div class="form-check">
          <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option1" checked>
          <label class="form-check-label" for="exampleRadios1">
            Yes
          </label>
        </div>
        <div class="form-check">
          <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios2" value="option2">
          <label class="form-check-label" for="exampleRadios2">
            No
          </label>
        </div>
      </div>

      <div class="form-group py-2">
        <label for="">5. The economy today has change do you believe that?</label>

        <div class="form-check">
          <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option1" checked>
          <label class="form-check-label" for="exampleRadios1">
            Yes
          </label>
        </div>
        <div class="form-check">
          <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios2" value="option2">
          <label class="form-check-label" for="exampleRadios2">
            No
          </label>
        </div>
      </div>

      <div class="form-group py-2">
        <label for="">6. Statistically every minute 3 to 5 Africans dies of poverty, the vision is to reduce that ratio.
          If our organisation consider you do you think you will be fit for this initiative.</label>

        <div class="form-check">
          <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option1" checked>
          <label class="form-check-label" for="exampleRadios1">
            Yes
          </label>
        </div>
        <div class="form-check">
          <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios2" value="option2">
          <label class="form-check-label" for="exampleRadios2">
            No
          </label>
        </div>
      </div>

      <div class="form-group py-2">
        <label for="">7. This is a Global Initiative across Africa if you are selected as one of our candidates for
          trips across the globe 🌎 do you have problems flying?.</label>

        <div class="form-check">
          <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option1" checked>
          <label class="form-check-label" for="exampleRadios1">
            Yes
          </label>
        </div>
        <div class="form-check">
          <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios2" value="option2">
          <label class="form-check-label" for="exampleRadios2">
            No
          </label>
        </div>
      </div>

      <div class="form-group py-2">
        <label for="">8. What kind of Business will you go into if finance was not the problem.</label>

        <input type="text" class="form-control" placeholder="Enter respponse here">
      </div>

      <div class="form-group py-2">
        <label>
        9. Have you been to any vacation for the past 12 months? </label>

        <div class="form-check">
          <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option1" checked>
          <label class="form-check-label" for="exampleRadios1">
            Yes
          </label>
        </div>
        <div class="form-check">
          <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios2" value="option2">
          <label class="form-check-label" for="exampleRadios2">
            No
          </label>
        </div>

      </div>

      <div class="form-group py-2">
        <label>
        10. If you are eligible and selected, you will be contacted by our senior consultant within 72hours are you ok with that ?.</label>

        <div class="form-check">
          <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option1" checked>
          <label class="form-check-label" for="exampleRadios1">
            Yes
          </label>
        </div>
        <div class="form-check">
          <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios2" value="option2">
          <label class="form-check-label" for="exampleRadios2">
            No
          </label>
        </div>

      </div>

      <div class="form-group py-3 text-center">

        <button class="btn batton   text-center"> <span class="text-center">Submit</span> </button>

      </div>


    </div>
      


  </section>
  <section class="gap no-top">
    <div class="container">
      <div class="heading">
        <span>Transformed lives</span>
        <h2>Testimonies</h2>
      </div>
      <div class="row clients-slider owl-carousel owl-theme">
        <div class="col-lg-12 item">
          <div class="clients">
            <p>"Global Project International Initiative secured my retirement. Their expertise and ethical approach to investments gave me peace of mind and financial stability in my golden years. Highly recommended!”</p>
            <div class="d-flex align-items-center mt-4">
              <div><i><img alt="quote" src="assets/img/quote.png"></i></div>
              <div>
                <h6>Deji Segun</h6>
                <span>Retired General</span>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-12 item">
          <div class="clients two">
            <p>"GPII transformed my retirement journey. As an elderly Nigerian investor, its global approach and expert guidance secured my financial future. A rewarding choice that I cherish.”</p>
            <div class="d-flex align-items-center mt-4">
              <div><i><img alt="quote" src="assets/img/quote.png"></i></div>
              <div>
                <h6>Igwe Chisom</h6>
                <span>Civil Servant</span>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-12 item">
          <div class="clients">
            <p>"Joining Global Project International Initiative was the smartest choice. They've safeguarded my retirement, delivering consistent returns and peace of mind. A truly dependable investment partner for seniors like me.”</p>
            <div class="d-flex align-items-center mt-4">
              <div><i><img alt="quote" src="assets/img/quote.png"></i></div>
              <div>
                <h6>Attah Gideon</h6>
                <span>Retired Accountant</span>
              </div>
            </div>
          </div>
        </div>
       
      </div>
    </div>
  </section>
  <footer class="gap no-bottom">
    <div class="container">
      <div class="row">
        <div class="col-lg-4 col-md-6">
          <div class="logo">
            <a href="#">
              <img alt="logo" src="assets/img/logo-b.png">
            </a>
          </div>
        </div>
        <div class="col-lg-4 col-md-6">
          <div class="links d-none">
            <h5>Information</h5>
            <div class="line"></div>
            <p>Enim ad minim veniam, quis rem ipsor sit amet ao Enim ad minim venianim veniam dolor sit amet ao.</p>
          </div>
        </div>
        <div class="col-lg-4 col-md-6">
          <div class="links">
            <h5>Contact Us</h5>
            <div class="line"></div>
            <span>Phone:<a href="callto:214-432-5905">+234 803 783 5670</a></span>
            <span class="mt-3 d-flex">Email:<a href="mailto:username@domain.com">support@vicsystems.com.ng</a></span>
          </div>
        </div>
      </div>
      <div class="footer-bottom d-none">
        <h3>Start a Free Trial</h3>
        <p>we help business innovate & growth company with 18 Years Perfessional Experience</p>
        <a href="#" class="btn"><span>Start Free Trial</span></a>
      </div>
      <div class="footer-end">
        <p>2023 © Global Project International Initiative</p>
      </div>
    </div>
    <div class="footer-shaps">
    </div>
  </footer>
  <!-- progress -->
  <div id="progress">
    <span id="progress-value"><i class="fa-solid fa-arrow-up"></i></span>
  </div>
  </main>
</template>
