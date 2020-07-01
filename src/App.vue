<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light bg-light py-3 menu">
      <div class="container">
        <a class="navbar-brand" href="#">Food's Gallery</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link" href="#">Gallary</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <div class="jumbotron bg-light">
      <div class="container">
        <h1 class="display-4">Food's Gallery</h1>
        <p class="lead">Food is any substance consumed to provide nutritional support for an organism.</p>
        <hr class="my-4">
        <p>Food is usually of plant or animal origin, and contains essential nutrients, such as carbohydrates, fats, proteins, vitamins, or minerals. </p>
        <a class="btn btn-outline-danger btn-lg" href="#" role="button">Learn more</a>
      </div>
    </div>

    <div class="container">

      <!-- Popular Food -->
      <h1 class="text-center my-5">Popular Foods</h1>

      <div class="row row-cols-1 row-cols-sm-3 row-cols-md-4 my-5">

        <div class="col py-3">
          <div class="card">
            <img src="img/1.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Food One</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-outline-danger btn-block">Detail</a>
            </div>
          </div>
        </div>

        <div class="col py-3">
          <div class="card">
            <img src="img/2.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Food Two</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-outline-danger btn-block">Detail</a>
            </div>
          </div>
        </div>

        <div class="col py-3">
          <div class="card">
            <img src="img/3.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Food Three</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-outline-danger btn-block">Detail</a>
            </div>
          </div>
        </div>

        <div class="col py-3">
          <div class="card">
            <img src="img/4.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Food Four</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-outline-danger btn-block">Detail</a>
            </div>
          </div>
        </div>

        <div class="col py-3">
          <div class="card">
            <img src="img/5.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Food Five</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-outline-danger btn-block">Detail</a>
            </div>
          </div>
        </div>

        <div class="col py-3">
          <div class="card">
            <img src="img/6.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Food Six</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-outline-danger btn-block">Detail</a>
            </div>
          </div>
        </div>

        <div class="col py-3">
          <div class="card">
            <img src="img/7.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Food Seven</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-outline-danger btn-block">Detail</a>
            </div>
          </div>
        </div>

        <div class="col py-3">
          <div class="card">
            <img src="img/8.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Food Eight</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-outline-danger btn-block">Detail</a>
            </div>
          </div>
        </div>
      </div>

      <!-- Gallery -->
      <h1 class="text-center my-5">Gallary</h1>
      <div class="row row-cols-2 row-cols-md-3">
        <div class="col py-3"><img src="img/1.jpg" class="img-fluid"></div>
        <div class="col py-3"><img src="img/2.jpg" class="img-fluid"></div>
        <div class="col py-3"><img src="img/3.jpg" class="img-fluid"></div>
        <div class="col py-3"><img src="img/4.jpg" class="img-fluid"></div>
        <div class="col py-3"><img src="img/5.jpg" class="img-fluid"></div>
        <div class="col py-3"><img src="img/6.jpg" class="img-fluid"></div>
        <div class="col py-3"><img src="img/7.jpg" class="img-fluid"></div>
        <div class="col py-3"><img src="img/8.jpg" class="img-fluid"></div>
        <div class="col py-3"><img src="img/9.jpg" class="img-fluid"></div>
      </div>

      <div class="row my-5">
        <div class="col-md-4">
          <div class="row">
            <div class="col-md-12 p-0">
              <img src="img/gallery/1.jpg" class="img-fluid">
            </div>
            <div class="col-md-12 p-0">
              <img src="img/gallery/2.jpg" class="img-fluid">
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="row">
            <div class="col-md-12 p-0">
              <img src="img/gallery/3.jpg" class="img-fluid">
            </div>
            <div class="col-md-12 p-0">
              <img src="img/gallery/4.jpg" class="img-fluid">
            </div>
            <div class="col-md-12 p-0">
              <img src="img/gallery/7.jpg" class="img-fluid">
            </div>
            <div class="col-md-12 p-0">
              <img src="img/gallery/8.jpg" class="img-fluid">
            </div>
            
          </div>
        </div>
        <div class="col-md-4">
          <div class="row">
            <div class="col-md-12 p-0">
              <img src="img/gallery/5.jpg" class="img-fluid">
            </div>
            <div class="col-md-12 p-0">
              <img src="img/gallery/8.jpg" class="img-fluid">
            </div>
            <div class="col-md-12 p-0">
              <img src="img/gallery/2.jpg" class="img-fluid">
            </div>
            
            
          </div>
        </div>
      </div>

      <!-- About -->
      <h1 class="text-center my-5">About</h1>
      <div class="row row-cols-1 row-cols-md-2">
        <div class="col pb-3">
          <img src="img/9.jpg" class="img-fluid">
        </div>
        <div class="col">
          <h3>About of Food</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
            tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
            quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
            consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
            cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
          proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
            tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
            quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
          consequat. Duis aute irure dolor in reprehenderit in voluptate velit</p>
        </div>
      </div>

      <!-- Contact -->
      <div class="row row-cols-1 row-cols-md-3">
        <div class="col">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Phone</h5>
              <h6 class="card-subtitle mb-2 text-muted">098765432121</h6>
              
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Email</h5>
              <h6 class="card-subtitle mb-2 text-muted">foodgallery@gmail.com</h6>
              
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Address</h5>
              <h6 class="card-subtitle mb-2 text-muted">Than Street, Hlaing , Tangon</h6>
              
            </div>
          </div>
        </div>
      </div>
    </div>
    <footer class="bg-light mt-5">
      <div class="container">
        <div class="row py-4">
          <div class="col-md-6 text-left">
            <h6>Copyright &copy; HEIN Development   </h6>
            </div>
            <div class="col-md-6 text-right">
              <h6>Facebook | Instagram | Twintter</h6>
              </div>
            </div>
          </div>
        </footer>
      </div>
    </template>

    <script>

      export default {
        name: 'App',
        components: {
        }
      }
    </script>

  <style>
    .menu{
      background-color: #f8f9fa;
      box-shadow: 0 10px 20px rgba(0,0,0,.05);  
    }
  </style>
