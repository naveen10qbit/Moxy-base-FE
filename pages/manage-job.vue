<template>
  <div class="page-body">
    <div class="container-xl">
      <!-- Page title -->
      <div class="page-header d-print-none">
        <div class="row align-items-center">
          <div class="col">
            <!-- Page pre-title -->
            <h1 class="page-title">
              Manage Requests
            </h1>
          </div>
          <!-- Page title actions -->
          <div class="col-auto ms-auto d-print-none">
            <div class="btn-list">
              <a href="#" class="btn btn-primary d-none d-sm-inline-block" data-bs-toggle="modal" data-bs-target="#modal-report">
                Post a Job
              </a>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-12 mt-3">
        <div class="card">
          <ul class="nav nav-tabs" data-bs-toggle="tabs">
            <li class="nav-item">
              <a href="#tabs-active-17" class="nav-link active" data-bs-toggle="tab">ACTIVE</a>
            </li>
<!--            <li class="nav-item">-->
<!--              <a href="#tabs-active-17" class="nav-link" data-bs-toggle="tab">PAUSED</a>-->
<!--            </li>-->
<!--            <li class="nav-item">-->
<!--              <a href="#tabs-active-17" class="nav-link" data-bs-toggle="tab">PENDING</a>-->
<!--            </li>-->
<!--            <li class="nav-item">-->
<!--              <a href="#tabs-active-17" class="nav-link" data-bs-toggle="tab">UNAPPROVED</a>-->
<!--            </li>-->
          </ul>
          <div class="card-body">
            <div class="tab-content">
              <div class="tab-pane fade active show" id="tabs-active-17">
                <div class="col-12">
                  <div class="card">
                    <div class="table-responsive">
                      <table class="table table-vcenter card-table">
                        <thead>
                        <tr>
                          <th>DATE</th>
                          <th>REQUEST</th>
                          <th>OFFERS</th>
                          <th>ACTION</th>
                          <th class="w-1"></th>
                        </tr>
                        </thead>
                        <tbody>
                        <tr>
                          <td>15 Dec 2017</td>
                          <td class="text-muted">
                            Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                          </td>
                          <td>
                            <span class="d-none d-sm-inline">
                    <a href="#" class="btn btn-white disabled">
                      Review Offers
                    </a>
                  </span>
                          </td>
                          <td>
                            <div class="dropdown">
                              <button class="btn dropdown-toggle align-text-top" data-bs-boundary="viewport" data-bs-toggle="dropdown" aria-expanded="false">
                                Actions
                              </button>
                              <div class="dropdown-menu dropdown-menu-end" style="">
                                <a class="dropdown-item" href="#">
                                  Action
                                </a>
                                <a class="dropdown-item" href="#">
                                  Another action
                                </a>
                              </div>
                            </div>
                          </td>
                        </tr>
                        <tr>
                          <td>15 Dec 2017</td>
                          <td class="text-muted">
                            Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                          </td>
                          <td>
                            <span class="d-none d-sm-inline">
                    <a href="#" class="btn btn-white disabled">
                      Review Offers
                    </a>
                  </span>
                          </td>
                          <td>
                            <div class="dropdown">
                              <button class="btn dropdown-toggle align-text-top" data-bs-boundary="viewport" data-bs-toggle="dropdown" aria-expanded="false">
                                Actions
                              </button>
                              <div class="dropdown-menu dropdown-menu-end" style="">
                                <a class="dropdown-item" href="#">
                                  Action
                                </a>
                                <a class="dropdown-item" href="#">
                                  Another action
                                </a>
                              </div>
                            </div>
                          </td>
                        </tr>
                        <tr>
                          <td>15 Dec 2017</td>
                          <td class="text-muted">
                            Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                          </td>
                          <td>
                            <span class="d-none d-sm-inline">
                    <a href="#" class="btn btn-white disabled">
                      Review Offers
                    </a>
                  </span>
                          </td>
                          <td>
                            <div class="dropdown">
                              <button class="btn dropdown-toggle align-text-top" data-bs-boundary="viewport" data-bs-toggle="dropdown" aria-expanded="false">
                                Actions
                              </button>
                              <div class="dropdown-menu dropdown-menu-end" style="">
                                <a class="dropdown-item" href="#">
                                  Action
                                </a>
                                <a class="dropdown-item" href="#">
                                  Another action
                                </a>
                              </div>
                            </div>
                          </td>
                        </tr>
                        </tbody>
                      </table>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="card-footer d-flex align-items-center">
            <p class="m-0 text-muted">Showing <span>1</span> to <span>8</span> of <span>16</span> entries</p>
            <ul class="pagination m-0 ms-auto">
              <li class="page-item disabled">
                <a class="page-link" href="#" tabindex="-1" aria-disabled="true">
                  <!-- Download SVG icon from http://tabler-icons.io/i/chevron-left -->
                  <svg xmlns="http://www.w3.org/2000/svg" class="icon" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"></path><polyline points="15 6 9 12 15 18"></polyline></svg>
                  prev
                </a>
              </li>
              <li class="page-item active"><a class="page-link" href="#">1</a></li>
              <li class="page-item"><a class="page-link" href="#">2</a></li>
              <li class="page-item"><a class="page-link" href="#">3</a></li>
              <li class="page-item"><a class="page-link" href="#">4</a></li>
              <li class="page-item"><a class="page-link" href="#">5</a></li>
              <li class="page-item">
                <a class="page-link" href="#">
                  next <!-- Download SVG icon from http://tabler-icons.io/i/chevron-right -->
                  <svg xmlns="http://www.w3.org/2000/svg" class="icon" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"></path><polyline points="9 6 15 12 9 18"></polyline></svg>
                </a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>

</style>
