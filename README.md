# goshipdemo.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-9ndCyUaIbzAi2FUVXJi0CjmCapSmO7SnpJef0486qhLnuZ2cdeRhO02iuK6FUUVM" crossorigin="anonymous">
    <link href="styles.css" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Gasoek+One&family=Noto+Serif:ital,wght@1,900&display=swap" rel="stylesheet">
    <title>GoShip</title>
</head>

<style>
    /* styles.css */
    @import url('https://fonts.googleapis.com/css2?family=Audiowide&display=swap');

    body {
        background-color: #F8F9FA;
        color: #333333;
    }

    nav.navbar {
        background-color: #4C5B7F;
        border: 1px solid 		#F8F9FA   ;
        border-top: none;
        border-left: none;
        border-right: none;
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 7%;
        z-index: 999;
        float: left;
    }


    nav.navbar .navbar-brand {
        color: #F8F9FA;
        font-family: 'Audiowide', cursive;
        font-weight: bold;
        font-size: 32px;
    }

    nav.navbar .navbar-brand .go {
        color: #FF6E31;
    }


    nav.navbar .navbar-brand span.ship-letter {
        color: #FFA41B;
    }


    nav.navbar .nav-link {
        color: 	#F8F9FA ;
        font-weight: Medium;
        position: relative;
        z-index: 1;
        margin-left: 18px;
    }

    .dropdown {
        position: relative;
        display: inline-block;
    }

    .dropdown-content {
        display: none;
        position: absolute;
        background-color: #f9f9f9;
        min-width: 100px;
        box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
        z-index: 1;
        top: 100%; /* 将下拉菜单显示在触发元素下方 */
        left: 0; /* 将下拉菜单与触发元素左对齐 */
    }

    .dropdown-content a {
        display: block; /* 使菜单项独占一行 */
        padding: 6px 18px; /* 调整菜单项的内边距 */
        text-decoration: none;
        color: #333333;
    }

    .dropdown:hover .dropdown-content {
        display: block;
    }

    nav.navbar .nav-link:hover {
        color:#F8F9FA;
    }

    nav.navbar .nav-link.join {
        position: relative;
    }

    nav.navbar .nav-link.join::after {
        content: "";
        position: absolute;
        bottom: 0;
        left: -10px;
        width: calc(100% + 20px);
        height: 38px;
        border-radius: 10px;
        background-color: #FFA41B;
        z-index: -1;
    }


    footer {
        padding: 50px 0;
        background-color: #4C5B7F;
    }

    footer h5 {
        color: #FFFFFF;
    }

    footer p {
        color: #FFFFFF;
    }

    footer input[type="email"] {
        width: 100%;
        padding: 10px;
    }

    footer button.btn-primary {
        margin-top: 10px;
    }

    .button {
    border: none;
    border-radius: 8px;
    padding: 16px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-family: Comfortaa;
    font-size: 16px;
    margin: 4px 2px;
    background-color: #FFA41B; 
    color: #F8F9FA; 
    -webkit-transition-duration: 0.4s;
    transition-duration: 0.4s;
    cursor: pointer;
    }

    .button2 {
        background-color: #FFA41B; 
        color: #F8F9FA; 
        font-weight: bold;
        border: 2px solid #F8F9FA;
    }

    .button2:hover {
        background-color: #F8F9FA;
        color: #FFA41B;
    }

    .sidebar {
    width: 80px;
    background-color: #fff;
    position: fixed;
    transform: translateY(-50%);
    background-color: #4D67A5;
    border: none; /* 去掉边框 */
    outline: none; /* 去掉外边框 */
    box-shadow: none; /* 去掉阴影效果 */
    }

    .sidebar ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
    }

    .sidebar li a {
    padding: 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 1px solid transparent;
    text-align: center;
    text-decoration: none;
    color: #fff;
    font-size: 14px; /* 调整文字大小 */
    border-bottom: 2px solid transparent;
    }


    .sidebar li a:hover {
    background-color: #333;
    }

    .sidebar li img {
    width: 34px;
    height: 34px;
    }

    .sidebar li span {
    text-decoration: none;
    font-size: 12px; /* 调整文字大小 */
    white-space: nowrap; /* 禁止文本换行 */
    }

    .indented {
            margin-left: 1em;
        }





</style>



<body>

    <nav class="navbar navbar-expand-lg navbar-light" style="background-color: #4C5B7F;">
        <div class="container">
            <a class="navbar-brand" href="http://127.0.0.1:5500/main.html">
                <span class="go">Go</span><span class="ship-letter">Ship</span>
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li>
                        <a class="nav-link" href="#" style="color: #F8F9FA"></a>
                    </li>
                    <li>
                        <a class="nav-link" href="http://127.0.0.1:5500/RequestService1.html">Book</a>
                    </li>
                    <li>
                        <a class="nav-link" href="#our-service">Track</a>
                    </li>
                    <li>
                        <a class="nav-link" href="#faq">Service</a>
                    </li>
                    <li>
                        <a class="nav-link" href="http://127.0.0.1:5500/aboutus2.html">About Us</a>
                    </li>
                </ul>
            </div>
            <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="dropdown">
                        <a class="nav-link" href="#" style="color: #F8F9FA">
                            English
                            <div class="dropdown-content">
                                <a href="#">Français</a>
                                <a href="#">简体中文</a>
                            </div>
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link join" href="#" style="color: #F8F9FA">Join</a>
                    </li>
                    </li>
                </ul>
            </div> 
        </div>
    </nav>


    <div>
        <div class="sidebar" style = "top: 41%; right: 0;">
            <ul>
              <li>
                <a href="#">
                  <img src="https://i.postimg.cc/L5R9gzvW/online-FAQ.png">
                  <span>Online chat</span>
                </a>
              </li>
            </ul>
        </div>
        <div class="sidebar" style = "top: 50%; right: 0;">
            <ul>
              <li>
                <a href="#">
                  <img src="https://i.postimg.cc/cLsN7xRv/hotline.png" alt="图片描述">
                  <span>Hotline</span>
                </a>
              </li>
            </ul>
        </div>
        <div class="sidebar" style = "top: 59%; right: 0;">
            <ul>
              <li>
                <a href="#">
                   <img src="https://i.postimg.cc/RhrkW4CV/branch.png" alt="图片描述">
                   <span>Branch</span>
                </a>
              </li>
            </ul>
        </div>
    </div>

      


    <br>
    <br>
    <br>
    <br>
    <br>
    <br>

    <br>
    <br>

    <br>
    <br>

    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>

    <br>
    <br>

    <br>
    <br>

    <br>
    <br>
    
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>

    <br>
    <br>

    <br>
    <br>

    <br>
    <br>
    
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>

    <br>
    <br>

    <br>
    <br>

    <br>
    <br>
    
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>

    <br>
    <br>

    <br>
    <br>

    <br>
    <br>


    <footer class="footer">
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <h5>Service</h5>
                    <p class="indented"> Book</p>
                    <p class="indented"> Track</p>
                    <p class="indented"> Price Inquiry</p>
                    <p class="indented"> Coverage Area Check</p>
                </div>
                <div class="col-md-4">
                    <h5>Our Company</h5>
                    <p class="indented">About GoShip</p>
                    <p class="indented">News</p>    
                    <p class="indented">Announcements</p> 
                    <p class="indented">Career</p> 
                    <p class="indented">Branch Locator</p>
                </div>
                <div class="col-md-4">
                    <h5>Contact Us</h5>
                    <p>24-Hour Hotline: </p>
                    <p class="indented"> (Canada) +1 289 155 6893</p>    
                    <p class="indented"> (China) +86 183 293 1900</p> 
                    <br>
                    <h5>Newsletter</h5>
                    <input type="email" placeholder="Your email here..." class="form-control mb-2">
                    <button class="btn btn-primary">Subscribe</button>
                    <br>
                    <br>
                    <p class="text-left">By submitting this form, you agree to our Terms of Use and acknowledge our Privacy Statement.</p>
                </div>
            </div>
        </div>
    </footer>





    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-geWF76RCwLtnZ8qwWowPQNguL3RmwHVBC9FhGdlKrxdiJJigb/j/68SIy3Te4Bkz" crossorigin="anonymous"></script>
</body>
</html>
