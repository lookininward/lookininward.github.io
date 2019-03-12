<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <title>Michael Xavier | lookininward.github.io</title>
    <meta name="author" content="Michael Xavier">
    <meta name="description" content="Software Developer's home page">
    <meta name="keywords" content="Michael, Xavier, Software, Developer">

     <!-- Bootstrap ---------------------------------------------------------->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
  </head>

  <body>

    <!-- Navigation ---------------------------------------------------------->
    {% include navigation.md %}

    <!-- Title --------------------------------------------------------------->
    {% if page.title %}
      <h2 class="w-100 mt-3 mb-3 text-center">

        <!-- {% if page.icon %}
          <i class="{{ page.icon }} mr-2" aria-hidden="true"></i>
        {% endif %} -->

        {{ page.title }}
      </h2>
    {% endif %}

    <!-- Body ---------------------------------------------------------------->
    <div class="container mb-5">

      <!-- Content ----------------------------->
      <div class="row justify-content-center mb-5">
        {{ content }}
      </div>

      <!-- Social Media ------------------------>
      <div class="row justify-content-center">
        <div class="col-7">
          <div
            class="d-flex align-items-center justify-content-around"
            style="font-size: 32px;"
          >
            <i class="fab fa-linkedin"></i>
            <i class="fab fa-medium"></i>
            <i class="fab fa-github"></i>
          </div>
        </div>
      </div>
    </div>

    <!-- Footer -------------------------------------------------------------->
    {% include footer.md %}

  </body>
</html>