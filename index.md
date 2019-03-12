---
layout: default
---

<div class="col-12 col-md-6">

  <div class="row mb-3">

    <div class="col-md-4">
      <img
        src="/assets/profile.jpg"
        class="card-img"
        alt="..."
      />
    </div>

    <div class="col-12 col-md-8 mt-3 pl-4 pr-4 mt-4 mb-3">
      This photo proves that I am a 100% real human software developer. Nothing suspicious going on. If you want to talk, get in touch.
    </div>
  </div>

</div>

<div class="col-12 col-md-6">
  {% include
     card-row.md
     title="Skills & Toolset"
     description="Breakdown of the technology and techniques I use to craft software."
     src="https://images.pexels.com/photos/207666/pexels-photo-207666.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
     icon="fas fa-toolbox"
     url="/skills"
  %}

  {% include
     card-row.md
     title="Work & Experience"
     description="The road from noob to software developer, and where I'm planning to go from here."
     src="https://images.pexels.com/photos/546819/pexels-photo-546819.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
     icon="fas fa-project-diagram"
     url="/work"
  %}

  {% include
     card-row.md
     title="Articles & Inspirations"
     description="Things I've written and that which inspire me."
     src="https://images.pexels.com/photos/1496183/pexels-photo-1496183.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
     icon="far fa-newspaper"
     url="/articles"
  %}
</div>
