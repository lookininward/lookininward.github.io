<!DOCTYPE html>
<html class="h-100">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <title>Michael Xavier | lookininward.github.io</title>
    <meta name="author" content="Michael Xavier">
    <meta name="description" content="Software Developer's home page">
    <meta name="keywords" content="Michael, Xavier, Software, Developer">

     <!-- Bootstrap ---------------------------------------------------------->
    <link
      rel="stylesheet"
      href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
      integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T"
      crossorigin="anonymous"
    >
  </head>

  <body class="d-flex flex-column">

    <!-- Navigation ---------------------------------------------------------->
    {% include navigation.md %}

    <!-- Title --------------------------------------------------------------->
    {% if page.title %}
      <h3 class="w-100 mt-3 mb-4 mb-lg-5 text-center">
        {{ page.title }}
      </h3>
    {% endif %}

    <!-- Body ---------------------------------------------------------------->
    <div
      class="container d-flex align-items-center justify-content-center"
      style="flex: 1 1 auto;"
    >

      <!-- Content ----------------------------->
      <div class="row justify-content-center w-100">
        {{ content }}
      </div>

    </div>

    <!-- Footer -------------------------------------------------------------->
    {% include footer.md %}

  </body>
</html>