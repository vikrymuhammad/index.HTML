# index.HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Design</title>
    <link rel="stylesheet" href="tugasstyle.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />    

</head>
<body>
    <nav>
        <div class="logo">
            <h4> Moqups </h4>
        </div>
            <ul>
                <li><a href="">Home</a></li>
                <li><a href="">Our Package</a></li>
                <li><a href="">Call Us</a></li>
            </ul>     
    </nav>

    <div class="judul">
        <h1>Top Rated E-Groceries Shop in Indonesia</h1><br>
        <p>Every Day with best ingredients</p>
    </div>
    
    <div class="container">
        <div class="thumbnail">
            <img src="img1.png">
                <div class="caption">
                    <p><i>"Setiap hari beli sayur buah yang fresh disini"</i></p>
                </div>
                    <div class="user">
                        <i class="fa-solid fa-circle-user" id="icon"></i>
                            <div class="label">
                                <h5>Muhammad Vikry<br></h5>
                                <p><i> Software Engineer </i></p>
                            </div>
                    </div>
                    <div class="caption-1">
                        <h4>Use this space to provide users with more information about your offer. 
                            Consider it a follow-up to your headline an explain the benefit of your service of product</h4>
                    </div>
                <div class="benefit">
                    <div class="number-one">
                        <i class="fa-solid fa-1"></i>
                        <div class="label1">
                            <p>Your first feature, written in the form of a benefit statement.</p>
                        </div>
                    </div>
                    <div class="number-two">
                        <i class="fa-solid fa-2"></i>
                        <div class="label2">
                            <p>Your second feature, written in the form of a benefit statement.</p>
                        </div>
                    </div>
                    <div class="number-three">
                        <i class="fa-solid fa-3"></i>
                        <div class="label3">
                            <p>Your third feature, written in the form of a benefit statement.</p>
                        </div>
                    </div>
                </div>
        </div>
               
        <div class="form">
            <form>
                <h1>Contact Us</h1><br>
                <p>Sales akan menghubungi anda 1x24 jam setelah data kami terima</p><br>
                    <label for="name">Your Name </label>
                    <input id="name" type="text" required />
                    <br>
                    <label for="email">Email Address</label>
                    <input id="name" type="email" required />
                    <br>
                    <label for="interested">What are you interested in? </label>
                    <br>
                    <select>
                        <option>Buah</option>
                        <option>Sayur</option>
                        <option>Sayur dan Buah</option>
                        <option selected> Select Option</option>
                    </select><br>
                        <button type="submit" class="btn-login"><b>SEND</b></button>
            </form>
        </div> 
    </div>
                        
             
</body>
</html>
