<div class="card">

  <!-- Card Header ----------------------------------------------------------->
  <div class="p-2 bg-white">
    <h5 class="mb-0">
      <button
        class="btn btn-link w-100 text-dark text-decoration-none text-left"
        type="button"
        data-toggle="collapse"
        data-target="#{{ include.id }}"
        aria-expanded="false"
        aria-controls="{{ include.id }}"
      >
        {{ include.title}}
      </button>
    </h5>
  </div>

  <!-- Card Body ------------------------------------------------------------->
  <div
    id="{{ include.id }}"
    class="collapse"
    data-parent="#accordion"
  >
    <div class="card-body pt-0 pb-2">

      <!-- Description ------------------------->
      <div class="mb-2">
        {{ include.description }}
      </div>

      <!-- Project URL ------------------------->
      <div class="text-right mb-2 mr-2">
        <a
          href="{{ include.url }}"
          target="_blank"
          >
          Visit
        </a>
      </div>

      <!-- Images ------------------------------>
      <!-- <img
        src="{{ include.img1 }}"
        class="card-img"
        alt="..."
      /> -->

      <!-- <img
        src="{{ include.img2 }}"
        class="card-img"
        alt="..."
      /> -->

    </div>
  </div>
</div>
