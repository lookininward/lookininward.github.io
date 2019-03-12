<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <title>Michael Xavier | lookininward.github.io</title>

    <meta name="author" content="name">
    <meta name="description" content="description here">
    <meta name="keywords" content="keywords,here">
    <!-- <link rel="shortcut icon" href="favicon.ico" type="image/vnd.microsoft.icon"> -->
    <!-- <link rel="stylesheet" href="stylesheet.css" type="text/css"> -->

    <!-- Bootstrap ----------------------------------------------------------->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>

    <!-- Font Awesome -------------------------------------------------------->
    <script defer src="https://use.fontawesome.com/releases/v5.7.2/js/all.js" integrity="sha384-0pzryjIRos8mFBWMzSSZApWtPl/5++eIfzYmTgBBmXYdhvxPc+XcFEk+zJwDgWbP" crossorigin="anonymous"></script>
  </head>

  <body>

    <!-- Navigation ---------------------------------------------------------->
    {% include navigation.md %}

    {% if page.title %}
      <h1>{{ page.title }}</h1>
    {% endif %}

    <!-- Body Content -------------------------------------------------------->
    <div class="container mb-5" style="margin-top: 70px;">

      <div class="row mb-5">
        {{ content }}
      </div>

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

    <div
      class="buffer-footer"
      style="width:100%; height:40px;"
    >
    <div>

    <!-- Footer -------------------------------------------------------------->
    {% include footer.md %}

  </body>
</html>