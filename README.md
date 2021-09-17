# bootstrap-practice-101
startlearningBS====================********=============
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
    <title>My BootStrap Sample</title>
</head>
<body>
    <!--navbar-->
<nav class="navbar navbar-expand-lg bg-dark navbar-dark py-3">
<div class="container">
    <a href="#" class="navbar-brand">it'sMyLogo</a>

    <Button
    type="button"
    class="navbar-toggler"
    data-bs-toggle="collapse"
    data-bs-target="#navmenu"
    style="background-color: rgb(55, 87, 23);"
    >
    <span class="navbar navbar-toggler-icon"></span>
    </Button>

<div class="collapse navbar-collapse" id="navmenu">
<ul class="navbar-nav ms-auto">
    <li class="nav-item ">
        <a href="#learn" class="nav-link">What you'll learn</a>
    </li>
    <li class="nav-item">
    <a href="#question" class="nav-link">Questions</a>
</li>
<li class="nav-item">
    <a href="#instructors" class="nav-link">Instructors</a>
</li>
</ul>
</div>
</div>
    </nav>

<!--showcase-->
<section class="bg-success text-light p-5 text-center" >
    <div class="container">
      <div class="d-sm-flex">
       <div>
           <h1>Become a <span class="text-warning"> <em> SpongeBob </em> </span>  Buddy</h1>
           <p class="lead my-2">Sometimes you meet a person and you just click—you’re comfortable with them, 
            like you’ve known them your whole life, and you don’t have to pretend to be 
            anyone or anything.
           </p>
           <button class="btn btn-primary btn-lg">Lets be friend</button>
       </div>
       <img class="img-fluid w-50 " src="/images/sponge.png" alt="spongebob picture">
      </div>
    </div>
</section>

<!--News Letter-->

<section class="bg-primary text-light p-5">
    <div class="container">
       <div class="d-md-flex justify-content-between align-items-center">
        <h3 class="mb-3 mb-md-0">Sign Up For Our Newsletter</h3>

         <div class="input-group news-input">
             <input type="text"
              class="form-control"
              placeholder="Enter Email"            
              />

            <button
              class="btn btn-dark btn-lg"
              type="button"      
            >
            Button
            </button>
         </div>
       </div>
    </div>
</section>

<!-- Boxes -->

<section class="p-5">
    <div class="container">
      <div class="row text-center">
          <div class="col-md">1234</div>
          <div class="col-md">1234</div>
          <div class="col-md">1234</div>        
      </div>

    </div>


</section>




<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>



</body>
</html>

