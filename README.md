# netflixclone
clone website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>netflix</title>
</head>
<body>
    <div class="header">
        <nav>
            <img src="logo.png" class="logo">
            <div class="signinbtn">
                <select name="lang" id="lang">
                    <option value="eng">&#127758;ENGLISH</option>
                    <option value="HIN">&#127758;HINDI</option>
                </select>
                <button>Sign in</button>
            </div>
        </nav>
        <div class="header-content">
            <h1>Laughter. Tears. Thrills. Find it all on Netflix.</h1>
            <h3>Endless entertainment starts at just ₹ 149. Cancel anytime.</h3> 
            <p>Ready to watch? Enter your email to create or restart your membership.</p>  
            <form class="header-inputbtn">
                <input type="text" name="email" id="email" placeholder="Email ID" required>
                <button id="gsbtn">Get started</button>
            </form>         
        </div>

    </div>
    <div class="main">
        <div class="row1">
            <div class="textdata">

            </div>
            <div class="imagedata">

            </div>
        </div>
        <div class="row2">
            <div class="textdata">

            </div>
            <div class="imagedata">
                
            </div>
        </div>
        <div class="row3">
            <div class="textdata">

            </div>
            <div class="imagedata">
                
            </div>
        </div>
        <div class="row4">
            <div class="textdata">

            </div>
            <div class="imagedata">
                
            </div>
        </div>
    </div>
    <script>
        
    </script>
</body>
</html>


style.css
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;

}
body{
    background-color: #000;
    color: #fff;
}
.header{
    width: 100%;
    height: 100vh;
    background-image: linear-gradient(rgba(0,0,0,0.6),rgba(0,0,0,0.6)),url(header-image.png);
    background-size: cover;
    background-position: center;
    padding: 10px 8%;
    position: relative;
}
nav{
    display:flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 0;

}
#lang{
    border: 2px solid #fff;
    outline: 0;
    background: transparent;
    color: #fff;
    padding: 7px 20px;
    font-size: 12px;
    margin-left: 10px;
    cursor: pointer;
    border-radius: 4px;
    justify-content: space-evenly;
    font-weight: 700;


}
button{
   
    outline: 0;
    color: #fff;
    background:red;
    border:none;
    padding: 7px 20px;
    font-size: 12px;
    margin-left: 10px;
    cursor: pointer;
    border-radius: 4px;
    justify-content: space-evenly;
    font-weight: 700;
}
.logo{
    width:140px;
    cursor: pointer;
}
.header-content{
   
    margin-top: 180px;
    margin-left: 100px;
    line-height: 65px;
    background-color: transparent;
    align-items: center;
    justify-content: center;
    align-content: center;
}
h1{
    font-size: 55px;
    color: #fff;
    flex-wrap: wrap;
    font-weight: 700;
    text-align: center;
}
h3{
    
    font-size:22px;
    color: #fff;
    flex-wrap: wrap;
    font-weight: 700;
    text-align: center;

}
p{
    
    font-size: 15px;
    color: #fff;
    flex-wrap: wrap;
    font-weight: 700;
    text-align: center;
}
.header-inputbtn{
    margin-top: 20px;
    margin-left: 60px;
    display: flex;
    align-items: center;
    justify-content: center;
    align-content: center;
}
#email{
    
    width: 55%;
    text-align: center;
    font-size: larger;
    font-weight: 500;
    background-color: transparent;
    color:#fff;
    padding: 10px;
    margin: 10px;
    border: 2px solid white;


}
.gsbtn{
   
   padding: 85px 75px;
   font-size: large;
    
    border: transparent;
    
}
