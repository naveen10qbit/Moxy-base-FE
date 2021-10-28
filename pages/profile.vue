<template>
  <div class="container-xl mt-3">
    <!-- Page title -->
    <div class="page-header d-print-none">
      <div class="row align-items-center">
        <div class="col mb-3">
          <h2 class="page-title">
            Profile
          </h2>
          <a href="#" class="btn btn-white btn-square btn-sm" role="button">Find Mentors</a>
          <a href="#" class="btn btn-white btn-square btn-sm" role="button">Find Jobs</a>
        </div>
        <!-- Page title actions -->
        <div class="col-auto ms-auto d-print-none">
          <div class="d-flex">
            <div class="me-0">
              <div class="input-icon">
                <input type="text" class="form-control" placeholder="Search Mentors...">
                <span class="input-icon-addon">
                        <!-- Download SVG icon from http://tabler-icons.io/i/search -->
                        <svg xmlns="http://www.w3.org/2000/svg" class="icon" width="24" height="24" viewBox="0 0 24 24"
                             stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round"
                             stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"></path><circle
                          cx="10" cy="10" r="7"></circle><line x1="21" y1="21" x2="15" y2="15"></line></svg>
                      </span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="card">
      <div class="card-body">
        <div class="page-wrapper">
          <div class="page-body">
            <div class="row">
              <div class="col-3">
                <div class="card">
                  <img
                    src="@/assets/avator.png"
                    class="card-img-top border"
                    alt="..."
                  />
                  <div class="card-body">
                    <h1 class="card-title">Jonathan Jecob</h1>
                    <p>Kandy, Sri Lanka</p>
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-star icon-filled text-yellow" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                      <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                      <path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z"></path>
                    </svg> <span> <a href="#">4.3 (Reviews)</a></span>
                    <button type="button" class="btn btn-secondary mt-2 col-12">
                      <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-settings" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                        <path d="M10.325 4.317c.426 -1.756 2.924 -1.756 3.35 0a1.724 1.724 0 0 0 2.573 1.066c1.543 -.94 3.31 .826 2.37 2.37a1.724 1.724 0 0 0 1.065 2.572c1.756 .426 1.756 2.924 0 3.35a1.724 1.724 0 0 0 -1.066 2.573c.94 1.543 -.826 3.31 -2.37 2.37a1.724 1.724 0 0 0 -2.572 1.065c-.426 1.756 -2.924 1.756 -3.35 0a1.724 1.724 0 0 0 -2.573 -1.066c-1.543 .94 -3.31 -.826 -2.37 -2.37a1.724 1.724 0 0 0 -1.065 -2.572c-1.756 -.426 -1.756 -2.924 0 -3.35a1.724 1.724 0 0 0 1.066 -2.573c-.94 -1.543 .826 -3.31 2.37 -2.37c1 .608 2.296 .07 2.572 -1.065z"></path>
                        <circle cx="12" cy="12" r="3"></circle>
                      </svg>
                    </button>
                  </div>
                </div>
                <div class="card mt-2">
                  <div class="card-body">
                    <h2 class="card-title">Bio</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aperiam deleniti fugit incidunt, iste,
                      itaque minima
                      neque pariatur perferendis sed suscipit velit vitae voluptatem.</p>
                    <button type="button" class="btn btn-success col-12">Contact me</button>
                  </div>
                </div>

                <hr>

                <div class="mt-2">
                  <h3>Social Links</h3>
                  <a href="#" class="btn btn-facebook btn-icon" aria-label="Button">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-facebook" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                      <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                      <path d="M7 10v4h3v7h4v-7h3l1 -4h-4v-2a1 1 0 0 1 1 -1h3v-4h-3a5 5 0 0 0 -5 5v2h-3"></path>
                    </svg>
                  </a>
                  <a href="#" class="btn btn-twitter btn-icon" aria-label="Button">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-twitter" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                      <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                      <path d="M22 4.01c-1 .49 -1.98 .689 -3 .99c-1.121 -1.265 -2.783 -1.335 -4.38 -.737s-2.643 2.06 -2.62 3.737v1c-3.245 .083 -6.135 -1.395 -8 -4c0 0 -4.182 7.433 4 11c-1.872 1.247 -3.739 2.088 -6 2c3.308 1.803 6.913 2.423 10.034 1.517c3.58 -1.04 6.522 -3.723 7.651 -7.742a13.84 13.84 0 0 0 .497 -3.753c-.002 -.249 1.51 -2.772 1.818 -4.013z"></path>
                    </svg>
                  </a>
                  <a href="#" class="btn btn-github btn-icon" aria-label="Button">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-github" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                      <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                      <path d="M9 19c-4.3 1.4 -4.3 -2.5 -6 -3m12 5v-3.5c0 -1 .1 -1.4 -.5 -2c2.8 -.3 5.5 -1.4 5.5 -6a4.6 4.6 0 0 0 -1.3 -3.2a4.2 4.2 0 0 0 -.1 -3.2s-1.1 -.3 -3.5 1.3a12.3 12.3 0 0 0 -6.2 0c-2.4 -1.6 -3.5 -1.3 -3.5 -1.3a4.2 4.2 0 0 0 -.1 3.2a4.6 4.6 0 0 0 -1.3 3.2c0 4.6 2.7 5.7 5.5 6c-.6 .6 -.6 1.2 -.5 2v3.5"></path>
                    </svg>
                  </a>
                </div>
              </div>
              <div class="col-9">
                <div class="row col-md-12 mt-0">
                  <div class="card">
                    <div class="card-header">
                      <h3 class="card-title">About</h3>
                      <a href="#" style="margin-left: auto" role="button">
                        <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-edit" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                          <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                          <path d="M9 7h-3a2 2 0 0 0 -2 2v9a2 2 0 0 0 2 2h9a2 2 0 0 0 2 -2v-3"></path>
                          <path d="M9 15h3l8.5 -8.5a1.5 1.5 0 0 0 -3 -3l-8.5 8.5v3"></path>
                          <line x1="16" y1="5" x2="19" y2="8"></line>
                        </svg>
                      </a>
                    </div>
                    <div class="card-body">
                      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aperiam deleniti fugit incidunt,
                        iste, itaque minima
                        neque pariatur perferendis sed suscipit velit vitae voluptatem.</p>
                    </div>
                  </div>
                </div>

                <div class="row col-md-12 mt-2">
                  <div class="card">
                    <div class="card-header">
                      <h3 class="card-title">Experience</h3>
                      <a href="#" style="margin-left: auto" role="button">
                        <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-edit" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                          <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                          <path d="M9 7h-3a2 2 0 0 0 -2 2v9a2 2 0 0 0 2 2h9a2 2 0 0 0 2 -2v-3"></path>
                          <path d="M9 15h3l8.5 -8.5a1.5 1.5 0 0 0 -3 -3l-8.5 8.5v3"></path>
                          <line x1="16" y1="5" x2="19" y2="8"></line>
                        </svg>
                      </a>
                    </div>
                    <div class="card-body">
                      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aperiam deleniti fugit incidunt,
                        iste, itaque minima
                        neque pariatur perferendis sed suscipit velit vitae voluptatem.</p>
                    </div>
                  </div>
                </div>

                <div class="row col-md-12 mt-2">
                  <div class="card">
                    <div class="card-header">
                      <h3 class="card-title"><a href="#">Reviews (25)</a></h3>
                    </div>
                    <div class="card-body">
                      <ReviewsSingleReview/>
                      <ReviewsSingleReview/>
                      <ReviewsSingleReview/>
                    </div>

                    <div style="margin-left: auto;margin-right: auto">
                     <a href="#"><p>See more</p></a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
