<div class="row mt-md-3">
  <div class="col-12">
    <div
      class="card mb-2 mb-md-3"
    >
      <div class="row no-gutters">
       <!--  <div class="col-2 col-md-4" style="background: url({{ include.src }}); background-size: cover;"> -->
       <!--  <div
          class="col-2 col-md-4 d-flex align-items-center justify-content-center"
          style="font-size: 1.5rem;"
        >
          <i class="{{include.icon}}"></i>
        </div> -->
        <div class="col-10 col-md-8">
          <div class="card-body">
            <h5 class="card-title">
              <i class="{{include.icon}} mr-2"></i>
              {{ include.title }}
            </h5>
            <p class="card-text">{{ include.description }}</p>
            <!-- <p class="card-text">
              <small class="text-muted">Last updated 3 mins ago</small>
            </p> -->
          </div>
        </div>
      </div>
    </div>
  </div>
</div>