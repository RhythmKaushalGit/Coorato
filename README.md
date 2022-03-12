# Coorato
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scales=1.0">
<title>Coorato</title>
<link rel="icon" type="image/svg+xml" href="https://yt3.ggpht.com/28IAp_74MfTFp90f8m9cszMFXqMIWHKE4WYdAbv-nPg4_aF1BZ8fAVeqmw8Z1Da9KZu2G9MFGw=s600-c-k-c0x00ffffff-no-rj-rp-mo">

        <!--=============== BOXICONS ===============-->
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/boxicons@latest/css/boxicons.min.css">

        <!--=============== CSS ===============-->
        <link rel="stylesheet" href="C:\Users\Marcos\Documents/style.css">

</head>
<body>
          <!--=============== HEADER ===============-->
          <header class="header" id="header">
            <nav class="nav container">
                <div class="nav__menu" id="nav-menu">
                    <ul class="nav__list">
                        <li class="nav__item">
                            <a href="#home" class="nav__link">
                                <i class='bx bx-cube-alt nav__icon'></i>
                                <span class="nav__name">Trending</span>
                            </a>
                        </li>
                        
                        <li class="nav__item">
                            <a href="#about" class="nav__link">
                                <i class='bx bx-user nav__icon'></i>
                                <span class="nav__name">Subscription</span>
                            </a>
                        </li>

                        <li class="nav__item">
                            <a href="#home" class="nav__link active-link">
                                <i class='bx bx-home-alt nav__icon'></i>
                                <span class="nav__name">Home</span>
                            </a>
                        </li>

                        <li class="nav__item">
                            <a href="#notifiaction" class="nav__link">
                                <i class='bx bx-message-alt nav__icon'></i>
                                <span class="nav__name">Notifiaction</span>
                            </a>
                        </li>

                        <li class="nav__item">
                            <a href="#library" class="nav__link">
                                <i class='bx bx-message-square-detail nav__icon'></i>
                                <span class="nav__name">Library</span>
                            </a>
                        </li>
                    </ul>
                </div>

                <img src="C:\Users\Marcos\Documents/Icon.png" alt="" class="nav__img">
            </nav>
        </header>

        <main>
            <!--=============== TRENDING ===============-->
            <section class="container section section__height" id="trending">
                <h2 class="section__title">Home</h2>
            </section>

            <!--=============== SUBSCRIPTIONS ===============-->
            <section class="container section section__height" id="subscription">
                <h2 class="section__title">About</h2>
            </section>

            <!--=============== HOME ===============-->
            <section class="container section section__height" id="home">
                <h1 class="section__title">Home</h1>
            </section>

            <!--=============== NOTIFICATION ===============-->
            <section class="container section section__height" id="notifications">
                <h2 class="section__title">Portfolio</h2>
            </section>

            <!--=============== LIBRARY ===============-->
            <section class="container section section__height" id="library">
                <h2 class="section__title">Contactme</h2>
            </section>
        </main>
        

        <!--=============== MAIN JS ===============-->
        <script src="C:\Users\Marcos\Documents/main.js"></script>
<ul id="list">

</ul>

<script>
var firebaseConfig = {
  apiKey: "AIzaSyBUBGDu0j5luR50lJlvqa0eyG7ocJ1JXHs",
  authDomain: "utuberhythm.firebaseapp.com",
  databaseURL: "https://coorato-rhythm-default-rtdb.firebaseio.com",
  projectId: "coorato-rhythm",
  storageBucket: "coorato-rhythm.appspot.com/",
  messagingSenderId: "692560087045",
  appId: "1:692560087045:web:f1737cb3c4b8322d76346c"
};
firebase
.initializeApp(firebaseConfig);

function addItemsToList(){
var ul=document.getElementById('list');
var header= document.createElement('h2');

var _title= document.createElement('li');
var _image= document.createElement('li');
var _post_type= document.createElement('li');
var _time= document.createElement('li');
var _date= document.createElement('li');
}

</script>

</body>
</html>
