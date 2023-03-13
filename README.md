# shopper
shopper ui design
<!DOCTYPE html>
<html>
    <head>
        <title>Shoperstop-online store</title>
        <link rel="stylesheet" href="../node_modules/bootstrap-icons/font/bootstrap-icons.css">
        <style>
            header {
                display: flex;
                justify-content: space-between;
                font-family: Arial;
                background-color:blue;
                color:white;
                padding: 20px;
            }
            header span {
          
                margin-right: 20px;
                font-size: 20px;
            }
            .brand {
                font-size: 24px;
                font-weight: bold;
            }
            section { 
                height: 800px;
                width: 50px;
            }
            footer {
                background-color:blue;
                color: white;
                height: 300px;
                padding: 20px;
                display: grid;
                grid-template-columns: 6fr 6fr;
                font-family: Arial;
            }
            .left-panel {
                display: grid;
                grid-template-columns:3fr 3fr 3fr 3fr;
            }
            .right-panel {
                display: flex;
                grid-template-columns: 6fr 6fr;
                border-left: 2px solid white;
                padding-left: 20px;
            }
            
            .footer-title {
                font-weight: bold;
                margin-bottom: 10px;
                color: rgb(128, 128, 128);
            }
            .footer-title~div {
                margin-bottom: 10px;
            }
            .back-to-top {
                background-color: slategrey;
                color:white;
                text-align: center;
                padding: 5px;
                font-size: 20px;
            }
        </style>
    </head>
    <body>
        <header>
            <div class="brand">
                Shoper.
            </div>
            <div>
              <nav>
                <span>Home</span>
                <span>Catalog</span>
                <span>Shop</span>
                <span>Page</span>
                <span>Blog</span>
                <span>Docs</span>
              </nav>
            </div>
            <div>
                <span class="bi bi-search"></span>
                <span class="bi bi-basket"></span>
                <span></span>
                <span class="bi bi-person"></span>
                <span class="bi bi-heart"></span>
                <span class="bi bi-cart"></span>
            </div>
        </header>
        <section class="50px">
          
            <div><img src="/Public/Images/Shoper.jpg.png" alt=""></div>

        </section>
        <div class="back-to-top">
            Back to top
        </div>
        <footer>
            <div class="left-panel">
                <div>
                    <div class="footer-title">ABOUT</div>
                    <div>Contact Us</div>
                    <div>About Us</div>
                    <div>Careers</div>
                    <div>Flipkart Stories</div>
                    <div>Press</div>
                    <div>Flipkart Wholesale</div>
                    <div>Corporate Information</div>
                </div>
                <div>
                   <div class="footer-title">HELP</div>
                    <div>Payments</div>
                    <div>Shipping</div>
                    <div>Cancellation & Returns</div>
                    <div>FAQ</div>
                    <div>Report Infringement</div>
                </div>
                <div>
                    <div class="footer-title">POLICY</div>
                    <div>Return Policy</div>
                    <div>Terms Of Use</div>
                    <div>Security</div>
                    <div>Privacy</div>
                </div>
                <div>
                    <div class="footer-title">SOCIAL</div>
                    <div> <span class="bi bi-facebook"></span> Facebook</div>
                    <div> <span class="bi bi-twitter"></span> Twitter</div>
                    <div> <span class="bi bi-youtube"></span> YouTube</div>
                </div>
            </div>
            <div class="right-panel">
                <div>
                    <div class="footer-title">Mail Us:</div>
                    Flipkart Internet Private Limited,

                    Buildings Alyssa, Begonia &

                    Clove Embassy Tech Village,

                    Outer Ring Road, Devarabeesanahalli Village,

                    Bengaluru, 560103,

                    Karnataka, India
                </div>
                <div>
                   <div class="footer-title"> Registered Office Address:</div>
                        Flipkart Internet Private Limited,

                        Buildings Alyssa, Begonia &

                        Clove Embassy Tech Village,

                        Outer Ring Road, Devarabeesanahalli Village,

                        Bengaluru, 560103,

                        Karnataka, India

                        CIN : U51109KA2012PTC066107

                        Telephone: 044-45614700
                </div>
            </div>
        </footer>
    </body>
</html>
