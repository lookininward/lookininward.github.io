<nav class="navbar fixed-top navbar-expand-lg navbar-dark bg-dark">

  <!-- Logo ------------------------------------------------------------------>
  <a class="navbar-brand font-weight-bold" href="/">
    <i class="fas fa-user-circle mr-2"></i>
    Michael Xavier
  </a>

  <!-- Toggle ---------------------------------------------------------------->
  <button
    class="navbar-toggler"
    type="button"
    data-toggle="collapse"
    data-target="#navbar-primary"
    aria-controls="navbar-primary"
    aria-expanded="false"
    aria-label="Toggle navigation"
  >
    <span class="navbar-toggler-icon"></span>
  </button>

  <!-- Nav Items ------------------------------------------------------------->
  <div class="collapse navbar-collapse" id="navbar-primary">
    <ul class="navbar-nav ml-auto">

      <li
        class="nav-item
               d-lg-none
               {% if page.url == "/" %} active {% endif %}"
      >
        <a class="nav-link" href="/">
          Home
        </a>
      </li>

      <li
        class="nav-item
               {% if page.url == "/skills/" %} active {% endif %}"
      >
        <a class="nav-link" href="/skills">
          Skills & Toolset
        </a>
      </li>

      {% comment %}
        <li
          class="nav-item
                 {% if page.url == "/work/" %} active {% endif %}"
        >
          <a class="nav-link" href="/work">
            Work & Experience
          </a>
        </li>
      {% endcomment %}
      <li
        class="nav-item
               {% if page.url == "/articles/" %} active {% endif %}"
      >
        <a class="nav-link" href="/articles">
          Articles
        </a>
      </li>

      {% comment %}
        <li
          class="nav-item
                 {% if page.url == "/contact/" %} active {% endif %}"
        >
          <a class="nav-link">
            Contact
          </a>
        </li>
      {% endcomment %}

    </ul>
  </div>
</nav>

<!-- Buffer ------------------------------------------------------------------>
<div
  class="buffer-navigation w-100"
  style="height:80px;"
>
</div>
