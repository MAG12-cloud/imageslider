<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Image Slider</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        
        .carousel-inner img {
            width: 100%;
            height: 400px; 
            object-fit: cover; 
            margin: 0 auto;
        }
    </style>
</head>
<body>

<div class="container">
    <h1 class="text-center">Image Slider</h1>

    <div id="imageCarousel" class="carousel slide" data-ride="carousel">
        <!-- Indicators -->
        <ol class="carousel-indicators">
            <li data-target="#imageCarousel" data-slide-to="0" class="active"></li>
            <li data-target="#imageCarousel" data-slide-to="1"></li>
            <li data-target="#imageCarousel" data-slide-to="2"></li>
            <li data-target="#imageCarousel" data-slide-to="3"></li>
            <li data-target="#imageCarousel" data-slide-to="4"></li>
            <li data-target="#imageCarousel" data-slide-to="5"></li>
            
        </ol>

        <!-- Slides -->
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="image/background1.jpeg" alt="Image 1">
            </div>
            <div class="carousel-item">
                <img src="image/background2.jpeg" alt="Image 2">
            </div>
            <div class="carousel-item">
                <img src="image/background3.jpeg" alt="Image 3">
            </div>
            <div class="carousel-item">
                <img src="image/background4.jpeg" alt="Image 4">
            </div>
            <div class="carousel-item">
                <img src="image/design 2.jpeg" alt="Image 5">
            </div>
            <div class="carousel-item">
                <img src="image/design 1.jpeg" alt="Image 6">
            </div>
            
        </div>

        <!-- Controls -->
        <a class="carousel-control-prev" href="#imageCarousel" data-slide="prev">
            <span class="carousel-control-prev-icon"></span>
        </a>
        <a class="carousel-control-next" href="#imageCarousel" data-slide="next">
            <span class="carousel-control-next-icon"></span>
        </a>
    </div>
</div>

<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
