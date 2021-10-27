<template>
  <div class="container-xl">
    <div class="d-inline-block mx-3 mt-4">
      <a href="#" class="link-secondary">Find mentors </a>|
      <a href="#" class="link-secondary">Find jobs</a>
    </div>
    <div class="card-body">
      <div id="carousel-captions" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item">
            <img class="d-block" width="1500" height="232" alt="" src="/sample.png">
            
            <div class="carousel-caption d-none d-md-block">
              <h3 style="color:black;">Slide 1</h3>
              <p>Nulla vitae elit libero, a pharetra augue mollis interdum.</p>
            </div>
          </div>
          <div class="carousel-item">
            <img class="d-block" width="1500" height="232" alt="" src="/sample.png">
            
            <div class="carousel-caption d-none d-md-block">
              <h3 style="color:black;">Slide 2</h3>
              <p>Nulla vitae elit libero, a pharetra augue mollis interdum.</p>
            </div>
          </div>
          <div class="carousel-item active">
            <img class="d-block" width="1500" height="232" alt="" src="/sample.png">
            
            <div class="carousel-caption d-none d-md-block">
              <h3 style="color:black;">Slide 3</h3>
              <p>Nulla vitae elit libero, a pharetra augue mollis interdum.</p>
            </div>
          </div>
          <div class="carousel-item">
            <img class="d-block" width="1500" height="232" alt="" src="/sample.png">
            
            <div class="carousel-caption d-none d-md-block">
              <h3 style="color:black;">Slide 4</h3>
              <p>Nulla vitae elit libero, a pharetra augue mollis interdum.</p>
            </div>
          </div>
          <div class="carousel-item">
            <img class="d-block" width="1500" height="232" alt="" src="/sample.png">
            
            <div class="carousel-caption d-none d-md-block">
              <h3 style="color:black;" >Slide 5</h3>
              <p>Nulla vitae elit libero, a pharetra augue mollis interdum.</p>
            </div>
          </div>
        </div>
        <a class="carousel-control-prev" href="#carousel-captions" role="button" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carousel-captions" role="button" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </a>
      </div>
    </div>
    <div>
      <h2 class="mb-15 mb-md-20 mx-3 mt-2">Find your mentor...</h2>
      <div>
        <div class="card mt-1 mx-3">
        <div id="carouselExampleControls" class="carousel slide" data-bs-interval="false">
          <div class="carousel-inner">
            <div class="carousel-item active">
              <div class="d-flex flex-row bd-highlight mt-4 ms-4">
                <MentorsSingleMentor />
                <MentorsSingleMentor />
                <MentorsSingleMentor />
                <MentorsSingleMentor />
                <MentorsSingleMentor />
              </div>
            </div>
          </div>
          <button
            class="carousel-control-prev"
            type="button"
            data-bs-target="#carouselExampleDark"
            data-bs-slide="prev"
          >
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button
            class="carousel-control-next"
            type="button"
            data-bs-target="#carouselExampleDark"
            data-bs-slide="next"
          >
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
        </div>
      </div>
    </div>
    <div>
      <h2 class="mb-15 mb-md-20 mx-3 mt-4">Find new jobs...</h2>
      <div class="card mt-1 mx-3">
        <div
          id="carouselExampleControls"
          class="carousel slide"
          data-bs-interval="false"
        >
          <div class="carousel-inner">
            <div class="carousel-item active">
              <div class="d-flex flex-row bd-highlight">
                <div class="card ms-4 mt-4 mb-4" style="width: 18rem">
                  <JobsSingleJob />
                </div>
                <div class="card ms-3 mt-4 mb-4" style="width: 18rem">
                  <JobsSingleJob />
                </div>
                <div class="card ms-3 mt-4 mb-4" style="width: 18rem">
                  <JobsSingleJob />
                </div>
                <div class="card ms-3 mt-4 mb-4" style="width: 18rem">
                  <JobsSingleJob />
                </div>
              </div>
            </div>
          </div>
          <button
            class="carousel-control-prev"
            type="button"
            data-bs-target="#carouselExampleDark"
            data-bs-slide="prev"
          >
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button
            class="carousel-control-next"
            type="button"
            data-bs-target="#carouselExampleDark"
            data-bs-slide="next"
          >
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style lang="scss" scoped>

</style>