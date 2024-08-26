<template>
  <div>

    <section class="site-hero site-hero-innerpage overlay" data-stellar-background-ratio="0.5"
      style="background-image: url(./images/big_image_1.jpg);">
      <div class="container">
        <div class="row align-items-center site-hero-inner justify-content-center">
          <div class="col-md-12 text-center">

            <div class="mb-5 element-animate">
              <h1>Reservation</h1>
              <p>Discover our world's #1 Luxury Hall For VIP.</p>
            </div>

          </div>
        </div>
      </div>
    </section>
    <!-- END section -->

    <section class="site-section">
      <div class="container">
        <div class="row">
          <div class="col-md-6">
            <h2 class="mb-5">Reservation Form</h2>
            <form action="#" method="post">
              <div class="row mb-3">
                <div class="col-sm-6 form-group">

                  <label for="">Arrival Date</label>
                  <div style="position: relative;">
                    <span class="fa fa-calendar icon" style="position: absolute; right: 10px; top: 10px;"></span>
                    <input class="form-group form-group-lg" type='date' id='arrival_date' />
                  </div>
                </div>

                <div class="col-sm-6 form-group mb-3">

                  <label for="">Departure Date</label>
                  <div style="position: relative;">
                    <span class="fa fa-calendar icon" style="position: absolute; right: 10px; top: 10px;"></span>
                    <input class="form-group form-group-lg" type='date' id='departure_date' />
                    <!-- <b-form-datepicker id="example-datepicker" class="mb-2"></b-form-datepicker> -->
                  </div>
                </div>

              </div>


              <div class="row mb-3">
                <div class="col-md-6 form-group">
                  <label for="room">Room</label>
                  <select name="" id="room" class="form-control form-control">
                    <option value="">1 Room</option>
                    <option value="">2 Rooms</option>
                    <option value="">3 Rooms</option>
                    <option value="">4 Rooms</option>
                    <option value="">5 Rooms</option>
                  </select>
                </div>

                <div class="col-md-6 form-group mb-3">
                  <label for="room">Guests</label>
                  <select name="" id="room" class="form-control form-control">
                    <option value="">1 Guest</option>
                    <option value="">2 Guests</option>
                    <option value="">3 Guests</option>
                    <option value="">4 Guests</option>
                    <option value="">5+ Guests</option>
                  </select>
                </div>
              </div>
              <div class="row mb-3">
                <div class="col-md-12 form-group">
                  <label for="email">Email</label>
                  <input type="email" id="email" class="form-control ">
                </div>
              </div>
              <div class="row mb-3">
                <div class="col-md-12 form-group">
                  <label for="message">Write a Note</label>
                  <textarea name="message" id="message" class="form-control " cols="30" rows="8"></textarea>
                </div>
              </div>
              <div class="row">
                <div class="col-md-6 form-group">
                  <input type="submit" value="Reserve Now" class="btn btn-primary">
                </div>
              </div>
            </form>
          </div>
          <div class="col-md-1"></div>
          <div class="col-md-5">
            <h3 class="mb-5">Featured Hall</h3>
            <div class="media d-block room mb-0">
              <figure>
                <img src="../images/img_1.jpg" alt="Generic placeholder image" class="img-fluid">
                <div class="overlap-text">
                  <span>
                    Featured Hall
                    <span class="ion-ios-star"></span>
                    <span class="ion-ios-star"></span>
                    <span class="ion-ios-star"></span>
                  </span>
                </div>
              </figure>
              <div class="media-body">
                <h3 class="mt-0"><a href="#">Presidential Room</a></h3>
                <ul class="room-specs">
                  <li><span class="ion-ios-people-outline"></span> 2 Guests</li>
                  <li><span class="ion-ios-crop"></span> 22 ft <sup>2</sup></li>
                </ul>
                <p>Nulla vel metus scelerisque ante sollicitudin. Fusce condimentum nunc ac nisi vulputate fringilla.
                </p>
                <p><a href="#" class="btn btn-primary btn-sm">Book Now From $20</a></p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- END section -->





    <section class="section-cover" data-stellar-background-ratio="0.5" style="background-image: url(images/img_5.jpg);">
      <div class="container">
        <div class="row justify-content-center align-items-center intro">
          <div class="col-md-9 text-center element-animate">
            <h2>Relax and Enjoy your Holiday</h2>
            <p class="lead mb-5">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto quidem tempore
              expedita facere facilis, dolores!</p>
            <div class="btn-play-wrap"><a href="https://vimeo.com/channels/staffpicks/93951774"
                class="btn-play popup-vimeo "><span class="ion-ios-play"></span></a></div>
          </div>
        </div>
      </div>
    </section>
    <!-- END section -->

    <footer class="site-footer">
      <div class="container">
        <div class="row mb-5">
          <div class="col-md-4">
            <h3>Phone Support</h3>
            <p>24/7 Call us now.</p>
            <p class="lead"><a href="tel://">+ 1 332 3093 323</a></p>
          </div>
          <div class="col-md-4">
            <h3>Connect With Us</h3>
            <p>We are socialized. Follow us</p>
            <p>
              <a href="#" class="pl-0 p-3"><span class="fa fa-facebook"></span></a>
              <a href="#" class="p-3"><span class="fa fa-twitter"></span></a>
              <a href="#" class="p-3"><span class="fa fa-instagram"></span></a>
              <a href="#" class="p-3"><span class="fa fa-vimeo"></span></a>
              <a href="#" class="p-3"><span class="fa fa-youtube-play"></span></a>
            </p>
          </div>
          <div class="col-md-4">
            <h3>Connect With Us</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Maxime, odio.</p>
            <form action="#" class="subscribe">
              <div class="form-group">
                <button type="submit"><span class="ion-ios-arrow-thin-right"></span></button>
                <input type="email" class="form-control" placeholder="Enter email">
              </div>

            </form>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>


