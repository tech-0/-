<!DOCTYPE html>
<html lang="en" dir="ltr">

<head>
  <meta charset="utf-8">
  <meta content='maximum-scale=1.0, initial-scale=1.0, width=device-width' name='viewport'>
  <title>COVID 19</title>
  <link rel="icon" href="/favicon.ico">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">

</head>

<body>
  <style media="screen">
    #logo {
      margin-left: 5px;
    }

    #row1 {
      margin-top: 20px;
    }
    #switch{
      margin-right: 10px;
    }
    h6{
      font-weight: 500;

    }
    #iraq{
      margin-top: -10px;
      font-weight: 500;
      font-size: 20px;
    }
  </style>

  <div class="navbar-fixed ">
    <nav class="green">
      <div class="nav-wrapper ">
        <a href="#!" class="brand-logo left" id="logo">COVID 19</a>
        <ul class="right">
          <div class="switch " id="switch">
            <label class="white-text">
              English
              <input type="checkbox" class="check">
              <span class="lever white"></span>
              Ú©ÙØ±Ø¯Û
            </label>
          </div>
        </ul>
      </div>
    </nav>
  </div>
  <div class="container">
    <div class="row" id="row1">
      <div class="col l12 m12 s12 center-align">
        <h1 id="home">Stay Home</h1>
      </div>
    </div>
      <div class="row">
        <div class="col l12 m12 s12 center-align">
          <img src="world.png" width="25%" alt="">
        </div>
      </div>
    <div class="row">
      <div class="col l12 m12 s12 center-align" >

        <h2 id="case">Coronavirus Cases</h2>
        <h4> 6,399,945 </h4>

      </div>
    </div>
    <div class="row">
      <div class="col l12 m12 s12 center-align" >
        <h2 id="death">Deaths</h2>
        <h4 class="red-text"> 378,065 </h4>
      </div>
    </div>
    <div class="row">
      <div class="col l12 m12 s12 center-align" >
        <h2 id="recover">Recovered</h2>
        <h4 class="green-text text-darken-2"> 2,930,443 </h4>
      </div>
    </div>
    <div class="row">
      <div class="col l12 m12 s12 center-align">
        <div class="card grey lighten-1">
          <div class="card-content ">
            <h5 id="ncase">New Cases</h5>
            <h6>36,749</h6>
            <h5 id="ndeath">New Deaths</h5>
            <h6 class="red-text ">875</h6>
            <h5 id="acase">Active Cases</h5>
            <h6>3,091,437</h6>
          </div>
        </div>
      </div>
    </div>
  <div class="row">
    <div class="col l12 m12 s12 center-align">
    <h4 id="click">Click here to see corona virus stats of Iraq</h4>
      <a href="/iraq" class="red-text" id="iraq" >

    Click Here
      </a>
    </div>
  </div>

  </div>




  <script type="text/javascript">
    let checkbox = document.querySelector(".check");
    checkbox.addEventListener('change', function(){
      if(this.checked){
        //kurdi
        document.querySelector("#home").innerHTML = "ÙÛÙØ§ÚµÛÙÛ Ø¨ÙÛÙÛØ±ÛÙÛ";
        document.querySelector("#case").innerHTML = "ØªÙØ´Ø¨ÙÙ";
        document.querySelector("#death").innerHTML = "ÙØ±Ø¯Ù"
        document.querySelector("#recover").innerHTML = "ÚØ§Ú©Ø¨ÙÙÛÙÛ";
        document.querySelector("#ncase").innerHTML = "ØªÙØ´Ø¨ÙØ§ÙÛ Ø¦ÛÙÚÛ";
        document.querySelector("#ndeath").innerHTML = "ÙØ±Ø¯ÙØ§ÙÛ Ø¦ÛÙÚÛ";
        document.querySelector("#acase").innerHTML = "ÚØ§ÙØ§Ú©";
        document.querySelector("#click").innerHTML = "Ú©ÙÛÚ© ÙÛØ±Û Ø¨Ú©Û Ø¨Û Ø¨ÛÙÛÙÛ Ø±ÛÚÛÛ ØªÙÙØ´ Ø¨ÙÙÙ Ù ÚØ§Ú©Ø¨ÙÙÙÛÙÛÛ Ø¹Ø±Ø§Ù";
        document.querySelector("#iraq").innerHTML = "Ú©ÙÛÚ© ÙÛØ±ÛØ¨Ú©Û";

      }else{
        document.querySelector("#home").innerHTML = "Stay Home";
        document.querySelector("#case").innerHTML = "Coronavirus Cases";
        document.querySelector("#death").innerHTML = "Deaths"
        document.querySelector("#recover").innerHTML = "Recovered";
        document.querySelector("#ncase").innerHTML = "New Cases";
        document.querySelector("#ndeath").innerHTML = "New Deaths";
        document.querySelector("#acase").innerHTML = "Active Cases";
        document.querySelector("#click").innerHTML = "Click here to see corona virus stats of Iraq";
        document.querySelector("#iraq").innerHTML = "Click Here";
      }
    })
  </script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
</body>

</html>
