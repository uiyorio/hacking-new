# hacking-new
  
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
    <script src="node_modules/three/build/three.js"></script>
    <script src="index.js"></script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Latihan Array</title>
    <style>
        .kotak {
            width: 30px;
            height: 30px;
            background-color: #BADA55;
            text-align: center;
            line-height: 30px;
            margin: 3px;
            float: left;
            transition: 1s;
        }
        .kotak:hover {
            transform: rotate(360deg);
            border-radius: 50%;
        }
        .clear {
            clear: both;
        }
    </style>
</head>
<body>

<?php 
$angka = [
    [1,2,3],
    [4,5,6],
    [7,8,9]
];
?>

<?php foreach( $angka as $a ) : ?>
    <?php foreach( $a as $b ) : ?>
        <div class="kotak"><?php echo $b; ?></div>
    <?php endforeach; ?>
    <div class="clear"></div>
<?php endforeach; ?>

<?php 


$data = file_get_contents('data/pizza.json');
$menu = json_decode($data, true);

$menu = $menu["menu"];

?>
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">

    <title>Menu Makanan</title>
  </head>
  <body>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container">
  <a class="navbar-brand" href="#">
    <img src="img/logo.png" width="120">
  </a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <a class="nav-link" href="#">All Menu</a>
      </li>
      
    </ul>
  </div>
  </div>
</nav>

<div class="container">
    <div class="row mt-3">
        <div class="col">
            <h1>All Menu</h1>
        </div>
    </div>
</div>

<?php 

// Assignment by Value
 $a = 20;
 $b = 15;
 $c = 5; 

 echo "$a = $a, $b = $b, $c = $c";
 echo "<br />";

 $a = $b = $c+5;
 echo "$a = $a, $b = $b, $c = $c";

</body>
</html> 
