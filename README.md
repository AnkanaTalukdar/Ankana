<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Products | Market place for Handmade Crafts</title>
<link rel="Stylesheet" href="Style.css">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.2/css/fontawesome.min.css">
    </head>
    <body>
        <div class="container">
            <div class="navbar">
                <div class="logo">
                    <img src="/html code/images/logo 123.png" width="125px"> 

                </div>
                <nav>
                    <ul id="MenuItems"> 
                        <li><a href="HANDMADE.html">Home</a></li>
                        <li><a href="products.html">Products</a></li>
                        <li><a href="">About</a></li>
                        <li><a href="">Contact</a></li>
                        <li><a href="">Account</a></li>
                    </ul>
                </nav>
                <img src="/html code/images/cart.png" width="30px" height="30px">
                <img src="/html code/images/menu.png" class="menu-icon" onclick="menutoggle()">
            </div>
            </div>


<!-------single product details------->>
<div class="small-container single-product">
    <div class="row">
        <div class="col-2">
            <img src="/html code/images/product 1.jpg" width="50%" id="ProductImg">
            
            <div class="small-img-row">
                <div class="small-img-col">
                    <img src="/html code/images/trayy.jpg" width="50%" class="small-img">
                </div>
                <div class="small-img-row">
                    <div class="small-img-col">
                        <img src="/html code/images/trayyyy.jpg" width="50%" class="small-img">
                    </div>
                </div>
            </div>

        </div>
        <div class="col-2">
            <p>HOME DECOR</p>
            <h1>Old school Charpahi style tray</h1>
            <h4>₹1500.00</h4>
            <input type="number" value="1">
            <a href="" class="btn">Add to Cart</a>

            <h4>Product details <i class="fa fa-indent"></i></h4>
            <br>
            <p> Crafted in wood and hand-painted by Indian awardee artisans, this beautiful tray is ideal for when guests are over. 
                Enjoy every delicately etched detail as you serve coffee or snacks, or display it as table decor.

            </p>
            <br>
            <h4>Design</h4>
            <p>
                This beautiful hand painted wooden tray is significant of exquisite Indian workmanship. 
                The designs are nature-inspired, and feature bright hues that give it undeniable traditional allure. 

            </p>
        </div>
    </div>
</div>
<!----title---->
<div class="small-container">
    <div class="row row-2">
        <h2>Related Products</h2>
        <p>view more</p>
    </div>
</div>

<!----products----->
    <div class="small-container">
    <div class="row">
        <div class="col-4">
            <img src="/html code/images/product d(1).jpg">
            <h4>Peesangan Brass Earrings</h4>
            <div class="rating">
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-half-o"></i>
            </div>
        <p>₹2060.00</p> 
    </div>
    <div class="col-4">
        <img src="/html code/images/product e(1).jpg">
        <h4>Eternal Love Brass Engraved Statue</h4>
        <div class="rating">
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star-half-o"></i>
        </div>
        <p>₹1500.00</p> 
    </div>
    <div class="col-4">
        <img src="/html code/images/ring napkin.jpg">
        <h4>Silver Waves Napkin Ring</h4>
        <div class="rating">
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star-half-o"></i>
            <i class="fa fa-star-o"></i>
        </div>
        <p>₹599.00</p> 
    </div>
    <div class="col-4">
        <img src="/html code/images/product f(1).jpg">
        <h4>Regal Heritage Wall Clock</h4>
        <div class="rating">
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star-o"></i>
        </div>
        <p>₹4480.00</p> 
        </div>
    </div>
    

</div>

<!---------------------------footer--------------->
    <div class="footer">
        <div class="container">
            <div class="row">
                <div class="footer-col-1">
                    <h3>Download Our App </h3>
                    <p>Download App for Android and IOS mobile phone.</p>
                    <div class="app-logo">
                        <img src="/html code/images/play-store.png">
                        <img src="/html code/images/app-store.png">
                    </div>
                </div>
                <div class="footer-col-2">
                    <img src="/html code/images/logo 122.png"> 
                    <p>Our purpose Is to sustainably make the pleasure and 
                        benefits of hand crafts to the many.</p>
                </div>
                <div class="footer-col-3">
                    <h3>Useful links</h3>
                    <ul>
                        <li>Coupons</li>
                        <li>Blog Post</li>
                        <li>Return Policy</li>
                        <li>Join Affliliate</li>
                    </ul>
                </div>
                <div class="footer-col-4">
                    <h3>FOllow Us</h3>
                    <ul>
                        <li>Instagram</li>
                        <li>Twitter</li>
                        <li>Facebook</li>
                        <li>YouTube</li>
                    </ul>
                </div>
            </div>
            <hr>
            <p class="Copyright">Copyright 2023 - Hand Made Crafts</p>
        </div>
    </div>

    <!-----------js for toggle menu--------------->
<script>
    var MenuItems = document.getElementById("MenuItems");

    MenuItems.style.maxHeight = "0px";

    function menutoggle(){
            if(MenuItems.style.maxHeight == "0px")
                {
                    MenuItems.style.maxHeight = "200px";
                }
            else
                {
                    MenuItems.style.maxHeight = "0px";
                }
    }
</script>


<!------js for product----->
<script>
    var ProductImg = document.getElementById("ProductImg");
    var SmallImg = document.getElementsByClassName("small-img");

    SmallImg[0].onclick = function()
    {
        ProductImg.src = SmallImg[0].src;
    }
    SmallImg[1].onclick = function()
    {
        ProductImg.src = SmallImg[1].src;
    }
    SmallImg[2].onclick = function()
    {
        ProductImg.src = SmallImg[2].src;
    }
</script>

    </body>
</html>
# Ankana
