<template>
  <header class="navbar navbar-expand-md navbar-light d-print-none shadow-lg">
    <div class="container-xl">
      <h1
        class="
          navbar-brand navbar-brand-autodark
          d-none-navbar-horizontal
          pe-0 pe-md-2
        "
      >
        <a href=".">
          <img
            src="@/assets/logo.png"
            width="100"
            height="35"
            alt="Tabler"
            class="navbar-brand-image"
          />
        </a>
      </h1>
      <div class="navbar-nav flex-row order-md-last">
        <div class="nav-item d-none d-md-flex me-0">
          <div class="btn-list">
            <div class="my-2 my-md-0 flex-grow-1 flex-md-grow-0 order-first">
              <form action="." method="get">
                <div class="input-icon">
                  <span class="input-icon-addon">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="icon"
                      width="24"
                      height="24"
                      viewBox="0 0 24 24"
                      stroke-width="2"
                      stroke="currentColor"
                      fill="none"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    >
                      <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                      <circle cx="10" cy="10" r="7"></circle>
                      <line x1="21" y1="21" x2="15" y2="15"></line>
                    </svg>
                  </span>
                  <input
                    type="text"
                    class="form-control"
                    placeholder="Search…"
                    aria-label="Search in website"
                  />
                </div>
              </form>
            </div>
            <a href="#" class="btn btn-outline-white"> Login </a>
            <a href="#" class="btn btn-outline-white"> Signup </a>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>
