# TESLA
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tesla Landing Page</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: Arial, sans-serif;
    }

    body{
      overflow-x:hidden;
    }

    /* HERO SECTION */
    .hero{
      width:100%;
      height:100vh;
      background:url('https://images.unsplash.com/photo-1617788138017-80ad40651399?q=80&w=1600&auto=format&fit=crop') center/cover no-repeat;
      position:relative;
      color:white;
    }

    /* DARK OVERLAY */
    .hero::before{
      content:"";
      position:absolute;
      inset:0;
      background:rgba(0,0,0,0.35);
    }

    /* NAVBAR */
    nav{
      position:relative;
      z-index:2;
      display:flex;
      justify-content:space-between;
      align-items:center;
      padding:25px 60px;
    }

    /* TESLA LOGO */
    .logo{
      display:flex;
      align-items:center;
      gap:12px;
    }

    .logo img{
      width:120px;
      filter: brightness(0) invert(1);
    }

    .nav-links{
      display:flex;
      gap:30px;
    }

    .nav-links a{
      color:white;
      text-decoration:none;
      font-size:15px;
      transition:0.3s;
    }

    .nav-links a:hover{
      opacity:0.7;
    }

    /* HERO CONTENT */
    .content{
      position:relative;
      z-index:2;
      height:calc(100vh - 100px);
      display:flex;
      flex-direction:column;
      justify-content:center;
      align-items:center;
      text-align:center;
      padding:20px;
    }

    .content h1{
      font-size:70px;
      margin-bottom:15px;
    }

    .content p{
      font-size:20px;
      margin-bottom:35px;
    }

    .buttons{
      display:flex;
      gap:20px;
      flex-wrap:wrap;
    }

    .btn{
      padding:14px 35px;
      border:none;
      border-radius:5px;
      font-size:16px;
      cursor:pointer;
      transition:0.3s;
    }

    .btn-dark{
      background:black;
      color:white;
    }

    .btn-light{
      background:white;
      color:black;
    }

    .btn:hover{
      transform:scale(1.05);
    }

    /* RESPONSIVE */
    @media(max-width:768px){

      nav{
        padding:20px;
      }

      .nav-links{
        display:none;
      }

      .logo img{
        width:90px;
      }

      .content h1{
        font-size:45px;
      }

      .content p{
        font-size:16px;
      }
    }
  </style>
</head>

<body>

  <section class="hero">

    <nav>

      <!-- TESLA ORIGINAL LOGO -->
      <div class="logo">
        <img 
          src="https://upload.wikimedia.org/wikipedia/commons/b/bd/Tesla_Motors.svg" 
          alt="Tesla Logo">
      </div>

      <div class="nav-links">
        <a href="#">Model S</a>
        <a href="#">Model 3</a>
        <a href="#">Model X</a>
        <a href="#">Model Y</a>
        <a href="#">Solar Roof</a>
      </div>

    </nav>

    <div class="content">
      <h1>Model Y</h1>
      <p>Experience Future Driving</p>

      <div class="buttons">
        <button class="btn btn-dark">Order Now</button>
        <button class="btn btn-light">Learn More</button>
      </div>
    </div>

  </section>

</body>
</html>
