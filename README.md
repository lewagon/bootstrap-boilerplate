You can quickly get started with Bootstrap with nothing do download using the following template:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <title>--- TODO ---</title>

    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.1.0/css/font-awesome.min.css">

    <!-- HTML5 Shim and Respond.js IE8 support of HTML5 elements and media queries -->
    <!-- Leave those next 4 lines if you care about users using IE8 -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
  </head>
  <body>


    <!-- This is a sample container, you can get rid of it. -->
    <!-- Do not forget to always use the "container -> row -> col" pattern when using the grid -->
    <div class="container">
      <div class="row">
        <div class="col-xs-4 col-xs-offset-4">
          <ul class="list-unstyled"> <!-- Using class "list-unstyled" to get rid of bullet points -->
            <li>
              <i class="fa fa-check-square-o"></i> Bootstrap is ready (see line 10, 39 and 40)
            </li>
            <li>
              <i class="fa fa-check-square-o"></i> Font Awesome is ready (see line 11)
            </li>
            <li>
              <i class="fa fa-square-o"></i> Set your title line 8 and go!
            </li>
          </ul>
        </div>
      </div>
    </div>


    <!-- Including Bootstrap JS (with its jQuery dependency) so that dynamic components work -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
  </body>
</html>
```

Just create an index.html file in your new folder project, copy paste
ours and start hacking!