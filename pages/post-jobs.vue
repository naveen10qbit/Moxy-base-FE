<template>
  <div>
    <div class="page-body">
      <div class="container-xl">
        <div class="row row-cards">
          <div class="col-md-6">
            <div class="card">
              <div class="card-body">
                <div class="card-header">
                  <h3 class="card-title">Describe the service you're looking to purchase - please be as detailed as possible:</h3>
                </div>
                <form>
                  <div class="form-group mb-3">
                    <div class="mb-3">
                      <textarea class="form-control" name="example-textarea-input" rows="6" placeholder="i'm looking for..." style="margin-top: 0px; margin-bottom: 0px; height: 108px;"></textarea>
                    </div>
                  </div>
<!--                  <div class="mb-3">-->
<!--                    <input type="file" class="form-control">-->
<!--                  </div>-->
<!--                  <div class="card-header">-->
<!--                    <h3 class="card-title">Choose a category:</h3>-->
<!--                  </div>-->
<!--                  <div class="form-group mb-3 row">-->
<!--                    <div class="col">-->
<!--                      <select class="form-select">-->
<!--                        <option>Select...</option>-->
<!--                      </select>-->
<!--                    </div>-->
<!--                    <div class="col">-->
<!--                      <select class="form-select">-->
<!--                        <option>Select subcategory</option>-->
<!--                      </select>-->
<!--                    </div>-->
<!--                  </div>-->
<!--                  <div class="card-header">-->
<!--                    <h3 class="card-title">Once you place your order, when would you like your service delivered?</h3>-->
<!--                  </div>-->
<!--                  <div class="mb-3">-->
<!--                    <div class="btn-group w-100">-->
<!--                      <button type="button" class="btn">24 Hours</button>-->
<!--                      <button type="button" class="btn">3 Days</button>-->
<!--                      <button type="button" class="btn">7 Days</button>-->
<!--                      <button type="button" class="btn">Other</button>-->
<!--                    </div>-->
<!--                  </div>-->
                  <div class="card-header">
                    <h3 class="card-title">What is your budget for this service?</h3>
                  </div>
                  <div class="mb-3">
                    <input type="text" class="form-control" name="example-text-input" placeholder="$">
                  </div>
                  <div class="form-footer text-end">
                    <button type="submit" class="btn btn-success">Submit Request</button>
                  </div>
                </form>
              </div>
            </div>
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
