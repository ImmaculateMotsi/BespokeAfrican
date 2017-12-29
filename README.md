<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <style>
    /* Remove the navbar's default rounded borders and increase the bottom margin */ 
    .navbar {
      margin-bottom: 50px;
      border-radius: 0;
    }
    
    /* Remove the jumbotron's default bottom margin */ 
     .jumbotron {
      margin-bottom: 0;
    }
   
    /* Add a gray background color and some padding to the footer */
    footer {
      background-color: #f2f2f2;
      padding: 25px;
    }
  </style>
</head>
<body>

<div class="jumbotron">
  <div class="container text-center">
    <h1>BespokeAfrican</h1>      
    <p>BespokeAfrican specialises in unique, affordable, tailor-made African-inspired clothing and accesories for men and women. Whatever your fabrib and style preferences, BespokeAfrican will deliver quality, custom-made clothing for any occassion. </p>
  </div>
</div>

<nav class="navbar navbar-inverse">
  <div class="container-fluid">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>                        
      </button>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav">
        <li class="active"><a href="#">Home</a></li>
        <li><a href="#">Products</a></li>
        <li><a href="#">Deals</a></li>
        <li><a href="#">Stores</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#"><span class="glyphicon glyphicon-user"></span> Your Account</a></li>
        <li><a href="#"><span class="glyphicon glyphicon-shopping-cart"></span> Cart</a></li>
      </ul>
    </div>
  </div>
</nav>

<div class="container">    
  <div class="row">
    <div class="col-sm-4">
      <div class="panel panel-primary">
        <div class="panel-heading">WOMEN'S SMART-CASUAL</div>
        <div class="panel-body"><img src="http://weddingdigestkenya.com/wp-content/uploads/2015/07/african-ladies-clothing-ankara-peplum.jpg" class="img-responsive" style="width:100%" alt="Image"></div>
        <div class="panel-footer"> Ready-to-wear smart-casual clothing for women </div>
      </div>
    </div>
    <div class="col-sm-4"> 
      <div class="panel panel-danger">
        <div class="panel-heading">MEN'S SMART-CASUAL </div>
        <div class="panel-body"><img src="https://lh3.googleusercontent.com/-3rNTRlIr9_Q/VrU75K4ouRI/AAAAAAAAw68/zWobj8FzDQY/s0/img307814390f7d494cf7bd0ab96c1e07bb.jpg" style="width:100%" alt="Image"></div>
        <div class="panel-footer">Ready-to-wear smart-casual clothing for men</div>
      </div>
    </div>
    <div class="col-sm-4"> 
      <div class="panel panel-success">
        <div class="panel-heading">WOMEN'S BLACK TIE</div>
        <div class="panel-body"><img src="https://i.pinimg.com/736x/ca/0b/d1/ca0bd1825b8706b66a0d5378608c4fb5--nigerian-lace-dress-styles-african-fashion-ankara.jpg" class="img-responsive" style="width:100%" alt="Image"></div>
        <div class="panel-footer"> Women's Special Occassion Wear </div>
      </div>
    </div>
  </div>
</div><br>

<div class="container">    
  <div class="row">
    <div class="col-sm-4">
      <div class="panel panel-primary">
        <div class="panel-heading">MEN'S BLACK TIE</div>
        <div class="panel-body"><img src="https://4.bp.blogspot.com/-xwcd9JNxkJw/WU-wBqOwkAI/AAAAAAAACQQ/5ErzJvrwjLodgJfPf8HMNV1uAzZTGCIRwCLcBGAs/s1600/men%2527s%2Bankara%2Bjacket%2Bstyle%2B%252812%2529.jpg" style="width:100%" alt="Image"></div>
        <div class="panel-footer">Men's Special Occasion Wear </div>
      </div>
    </div>
    <div class="col-sm-4"> 
      <div class="panel panel-primary">
        <div class="panel-heading">COUPLE'S MATCHING OUTFITS</div>
        <div class="panel-body"><img src="http://ankaracollections.com/wp-content/uploads/2017/09/IMG_6973.jpg" class="img-responsive" style="width:100%" alt="Image"></div>
        <div class="panel-footer"> His and Her's matching outfit, casual or black tie </div>
      </div>
    </div>
    <div class="col-sm-4"> 
      <div class="panel panel-primary">
        <div class="panel-heading"> ACCESSORIES </div>
        <div class="panel-body"><img src="https://runstripe.com/wp-content/uploads/2016/11/ankara-shoes-and-bags-3.jpg" class="img-responsive" style="width:100%" alt="Image"></div>
        <div class="panel-footer">Complete your look with a wide range of African-inspired accesories for men and women </div>
      </div>
    </div>
  </div>
</div><br><br>

<footer class="container-fluid text-center">
  <p>Online Store Copyright</p>  
  <form class="form-inline">Get deals:
    <input type="email" class="form-control" size="50" placeholder="Email Address">
    <button type="button" class="btn btn-danger">Sign Up</button>
  </form>
</footer>

</body>
</html>

