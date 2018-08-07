# practice
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>

  <link rel="stylesheet" href="bootstrap.min.css">
  <link rel="stylesheet" href="001css.css">
  <script src="https://cdn.bootcss.com/jquery/3.2.1/jquery.min.js"></script>
  <script src="https://cdn.bootcss.com/popper.js/1.12.5/umd/popper.min.js"></script>
  <script src="https://cdn.bootcss.com/bootstrap/4.1.0/js/bootstrap.min.js"></script>
  <link href="//netdna.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">

</head>
<body>

<div class="container part1">
  <div class="row justify-content-between">
    <div class="col-md-4 col-4">
      <a href="#"><img src="image/og_Ms_logo.png" height="100%" width="100%"/></a>
    </div>
    <div class="col-md-4 col-4">
      <div style=" background-color: black;opacity: 0.5; border-radius: 20px;margin-top: 5%;height: 25px;width: 200px">

      <i class="fa fa-search" style="width: 20px;height: 20px;float: left;color: red;margin-left: 4%;margin-top: 3%"></i>
      <input id="search" type="text" class="form_input" placeholder="Search"/>
      <i id="clear" class="fa fa-close" style="width: 20px;height: 20px;color: white;float: right;margin-right: 4%;margin-top: 3%"></i>
      </div>
      </div>
      <script type="text/javascript">
        var text = $('#search');
        var ccc  = $('#clear');

        text.focus(function(){
          if(text != ""){
            ccc.show();
          }else {
            ccc.hide()
          }
          text.attr('placeholder','')
        });
        text.blur(function () {
          text.attr('placeholder','Search')
        });
        ccc.click(function(){
          text.val('');//清空
        });
      $(function () {
        ccc.hide();

      });




      </script>


    </div>

  </div>
</div>

<div class="container part2">
  <div class="row">
    <div class="col-md-2 col-2" style="font-size:20px;">
      <span><strong>Home</strong></span>

    </div>
    <div class="col-md-2 col-2" style="font-size:20px">
      <span><strong>About Us</strong></span>

    </div>
    <div class="col-md-2 col-2" style="font-size:20px">
      <span><strong>Portfolio</strong></span>

    </div>
    <div class="col-md-2 col-2" style="font-size:20px">
      <span><strong>Solutions</strong></span>

    </div>
    <div class="col-md-2 col-2" style="font-size:20px">
      <span><strong>Case Studies</strong></span>

    </div>
    <div class="col-md-2 col-2" style="font-size:20px">
      <span><strong>Get a Quote</strong></span>
    </div>
  </div>

</div>

<div class="container part3" style="margin-top: 1%; padding: 0;">
  <div id="demo" class="carousel slide" data-ride="carousel">
    <!-- 指示符 -->
    <ul class="carousel-indicators">
      <li data-target="#demo" data-slide-to="0" class="active"></li>
      <li data-target="#demo" data-slide-to="1"></li>
      <li data-target="#demo" data-slide-to="2"></li>
      <li data-target="#demo" data-slide-to="3"></li>
    </ul>

    <!-- 轮播图片 -->
    <div class="carousel-inner">
      <div class="carousel-item active carousel-bg1">
        <img  src="image/ogMs_banner.jpg" style="width: 100%;">
      </div>
      <div class="carousel-item carousel-bg2">
        <img src="image/ogMs_banner.jpg" style="width: 100%;">
      </div>
      <div class="carousel-item carousel-bg3">
        <img src="image/ogMs_banner.jpg" style="width: 100%;">
      </div>
      <div class="carousel-item carousel-bg4">
        <img src="image/ogMs_banner.jpg" style="width: 100%;">
      </div>
    </div>
    <!-- 左右切换按钮 -->
    <a class="carousel-control-prev" href="#demo" data-slide="prev">
      <span class="carousel-control-prev-icon"></span>
    </a>
    <a class="carousel-control-next" href="#demo" data-slide="next">
      <span class="carousel-control-next-icon"></span>
    </a>
  </div>

</div>

<div class="container part4">
  <div class="row">
    <div class="col-md-4 col-sm-12 left">
      <div height="100%" width="100%">
      <strong style="font-size: 20px"> Welcome to the Orange Monster</strong>
      <p>The draft calls for efforts to lower the  <a href="#">this year. By 2030</a>, the rate of myopia among six-year-old children should be controlled at around 3 percent. For primary school students it should be no higher than 38 percent, and held at less than 60 percent for middle school students and 70 percent for high school students.</p>

     <p>d improve the provision of physical education classes and limit the use of screen-based teaching time to no more than 30 percent of class time.</p>
    <a href="#"><button id="but">Click Me</button></a>
      </div>
    </div>

    <div class="col-md-4 col-sm-12 center ">

        <div class="col-md-12 col-sm-12 col-6">
        <img src="image/ogMs_feat1.png" height="100%" width="100%"/></div>

      <div class="col-md-12 col-sm-12 col-6" style="margin-top: 2%">
        <img src="image/ogMs_feat2.png" height="100%" width="100%"/></div>
    </div>

    <div class="col-md-4 col-sm-12 right">
      <p style="color: yellow">calls for efforts</p>
      <p>The draft calls for efforts to lower the rate of myopia among children and adolescents by 0.5 percent a year by 2023, starting this year. By 2030, the rate of myopia among six-year-old children should be controlled at around 3 percent. For primary school students it should be no higher than 38 percent, and held at less than 60 percent for middle school students and 70 percent for high school students.</p>

      <p>d improve the provision of physical education classes and limit the use of screen-based teaching time to no more than 30 percent of class time.</p>
    </div>


  </div>
</div>
<div class="container-fluid part5">
  <div class="container">
  <div class="row">
    <div class="col-md-9 col-9">
      <div class="row" style="margin-top: 3%">
        <div class="col-md-3 col-3">
          <h5>About Us</h5>
          vision of physica
          <br>
          vision of physica
        </div>
        <div class="col-md-3 col-3">
          <h5>Portfolio</h5>
          vision of physica
          <br>
          vision of physica
          <br>
          vision of physica
        </div>
        <div class="col-md-3 col-3">
          <h5>Solutions</h5>
          vision of physica
          <br>
          vision of physica
        </div>
        <div class="col-md-3  col-3">
          <h5>Case Studies</h5>
          vision of physica
          <br>
          vision of physica
        </div>

      </div>



      <div style="margin-top: 3%">
        To order a book one first had to get permission from the monastery that held t
        <br>
        To order a book one first had to get permission fr
      </div>

    </div>





    <div class="col-md-3">
<div>
      <img style="width: 204px; height: 174px" src="image/ogMs_eye.png" ></div>
    </div>
  </div>
</div>
</div>


</body>
</html>
