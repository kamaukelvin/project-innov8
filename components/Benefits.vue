<template>
<div id="benefits" class="card-jaribu">
  <section class="bg-color" >
    <div class="container " style="display:flex">
      <div class="row mt-3 ">
  <div class="col-6 col-md-3 card-s mb-3 mt-5 col-lg-3 ">
    <div class="card text-card text-center">
      <div class="card-body">
        <h5 class="card-title">Challenge <strong>Benefits</strong></h5>
      </div>
    </div>
  </div>
  <div class="col-6 col-md-3 card-s mb-3 mt-5 col-lg-3">
    <div class="card text-center">
      <div class="card-body">
          <img class="logo" src="~assets/images/Svg/icons Q2.svg" alt="Logo">
        <p>One week of learning experience in building innovative solutions</p>
      </div>
    </div>
  </div>
  <div class="col-6 col-md-3 card-s mb-3 mt-5 col-lg-3" >
    <div class="card text-center">
      <div class="card-body">
          <img class="logo" src="~assets/images/Svg/Layer 2.svg" alt="Logo">
          <p>Personalised mentorship for all participating teams and their idea validation needs.</p>
      </div>
    </div>
  </div>
  <div class="col-6 col-md-3 card-s mb-3 mt-5 col-lg-3" >
    <div class="card text-center">
      <div class="card-body">
         <img class="logo" src="~assets/images/Svg/Layer -1.svg" alt="Logo">
          <p>Access to legal, accounting, financial planning and tech support;</p>
      </div>
    </div>
  </div>
   <div class="col-6 col-md-3 card-s mb-3 mt-5 col-lg-3">
    <div class="card text-center">
      <div class="card-body">
          <img class="logo" src="~assets/images/Svg/Layer -3.svg" alt="Logo">
         <p>Access to networking opportunities with fellow successful applicants and</p>

      </div>
    </div>
   </div>
   <div class="col-6 col-md-3 card-s mb-3 mt-5 col-lg-3">
    <div class="card text-center">
      <div class="card-body">
           <img class="logo" src="~assets/images/Svg/Layer -2.svg" alt="Logo">
         <p>$10,000 prize for the winning team, and $5,000 and $2,500 for the 1st</p>
      </div>
    </div>
  </div>
  <div class="col-6 col-md-3 card-s mb-3 mt-5 col-lg-3">
    <div class="card text-center">
      <div class="card-body">
           <img class="logo" src="~assets/images/Svg/Mail Box.svg" alt="Logo">
         <p>4-weeks of ongoing support from Stanbic Bank Zambia and a network of coaches and mentors to assist with go-to market strategies ang</p>
      </div>
    </div>
  </div>
    <div class="col-6 col-md-3 card-s mb-3 mt-5 col-lg-3" >
    <div class="card text-center">
      <div class="card-body">
          <img class="logo" src="~assets/images/Svg/Path 14.svg" alt="Logo">
          <p>An opportunity to join a supportive innovators network</p>
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

  }
</script>

<style>

.bg-color{
   background: linear-gradient(to top right,#E30F93, #4B38A9);
   min-height: 42em;
}



.logo{
  height: 40%;
  width: 4rem;
  object-fit: fill;
}

.card-body{
  height: 15rem;
}
.row:hover .card-s{
      filter: blur(1px);
    }
    .row .card-s:hover{
       filter: blur(0px);
    }
@media (max-width: 500px) {
  .card-jaribu {
    overflow: hidden;
    width: 100%;
  }
  /* .row {
     width: 100%;
    display: flex;
  }
  .card-s {
    position: relative;
  } */
  /* .text-center .card-body p {
    visibility: hidden;
  } */
  .bottom-links {
    width: 100%;
  }
  p {
  font-size: 13px;
}
}


</style>
