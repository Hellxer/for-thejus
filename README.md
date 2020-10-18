# for-thejus
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MPAC</title>
    <link rel="stylesheet" href="style.css">
    <!--icons api-->
    <a href="https://icons8.com/icon/3260/sell"></a>
    <script src="https://kit.fontawesome.com/087042e108.js" crossorigin="anonymous"></script>
    <!--Jquery cdn-->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
</head>
<body>
    <!--Navbar-->
    <nav>
        <ul>
            <li class="logo">MPAC</li>
            <li class="items"><a href="#">Home</a></li>
            <li class="items"><a href="#">Dashboard</a></li>
            <li class="items"><a href="#">About Us..</a></li>
            <li class="items"><a href="#">Contact Us</a></li>
            <li class="toggle"><span class="bars"></span></li>
        </ul>
    </nav>

    <!-- forms -->

    <form>
        <div id="form-body">
            <h1>Textbooks</h1>
            <div class="book-name">
                Book Name <input type="text" class="input-box">
            </div>
            <div class="book-author">
                Author <input type="text"  class="input-box">
            </div>
            <div class="book-pages">
                Pages <input type="number"  class="input-box">
            </div>
            <div class="book-price">
                Price <input type="number"  class="input-box">
            </div>
            <div class="book-image">
                Image <input type="file" class="input-file" >
            </div>
            <div class="submit">
                <button class="sub-button">Submit</button>
            </div>

        </div>
    </form>

    <script src="main.js"></script>
    <script src='jquery.js'></script>
</body>
</html>
