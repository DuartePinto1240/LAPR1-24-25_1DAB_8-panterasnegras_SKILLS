<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>Webpage design</title>
    <link rel="stylesheet" href="style.css">
    
</head>
<body>
    <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="logo">IRSGO</h2>
            </div>
            <div class="menu">
                <ul>
                    <li><a href="#">HOME</a></li>
                    <li><a href="#">ABOUT</a></li>
                    <li><a href="#">SERVICE</a></li>
                    <li><a href="#">DESIGN</a></li>
                    <li><a href="#">CONTACT</a></li>


                </ul>
            </div>
            <div class="search">
                <input class="srch" type="search" name="" placeholder="Type to text">
                <a href="#"><button class = "btn">Search</button></a>
            </div>
            <div class="content">
                <h1>WebDesign & <br><span>Development</span><br>Course</h1>
                <p class="par">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Adipisci officia nihil totam natus incidunt eos at omnis alias nulla dolores sequi, unde distinctio ad iusto asperiores expedita!<br> Recusandae, asperiores illum?</p>
                <button class="cn"><a href="#">JOIN US</a></button>
                <div class="form">
                    <h2>Login Here</h2>
                    <input type="email" name="email", placeholder="Enter Email Here">
                    <input type="password" name="", placeholder="Enter Password Here">
                    <button class="btn"><a href="#">Login</a></button>
                    <p class="link">Don `t have an account <br>
                    <a href="#">Sign up Here</a></p>
                    <p class="liw">Log in with</p>
                </div>
            </div>
            
        </div>
    </div>
</body>
</html>

-----------------------------------------------------------------------
*{
    margin: 0;
    padding: 0;
}

.main {
    width: 100%;
    background: linear-gradient(to top, rgba(0,0,0,0.5)50%,rgba(0,0,0,0.5)50%), url(irs\ background.jpg);
    background-position: center;
    background-size: cover;
    height: 109vh;
}
.navbar {
    width: 200px;
    float: left;
    height: 70px;
}
.logo {
    color: 	#89cff0;
    font-size: 35px;
    font-family: Arial;
    padding-left: 70px;
    float: left;
    padding-top: 20px;

}
.menu {
    width: 400px;
    float: left;
    height: 70px;
}
ul {
    float: left;
    display: flex;
    justify-content: center;
    align-items: center;
}
ul li {
    list-style: none;
    margin-left: 50px;
    margin-top: 7px;
    font-size: 14px;
}



ul li a {
    text-decoration:none ;
    color: #fff;
    font-family: Arial;
    font-weight: bold;
    transition: 0.4s ease-in-out;

}
ul li a:hover{
    color: #89cff0;
}
.search {
    width: 330px; ;
    float: left;
    margin-left: 970px;
    margin-top: -60px;

}
.srch{
    font-family: 'Times New Roman';
    width: 220px;
    height: 40px;
    background: transparent;
    border: 1px #89cff0;
    margin-top: 13px;
    color: white;
    border-right: none;
    font-size: 16px;
    float: left;
    padding: 10px;
    border-bottom-left-radius: 5px;
    border-top-left-radius: 5px;
}
.btn {
    width: 100px;
    height: 40px;
    background: #89cff0;
    border: 2px solid #89cff0;
    margin-top: 13px;
    color: white;
    font-size: 15px;
    border-bottom-right-radius: 5px;
    border-bottom-right-radius: 5px;

}
.btn:focus{
    outline: none;
}
.srch:focus{
    outline: none;
}
.content{
    width: 1200px;
    height: auto;
    margin: auto;
    color: white;
    position: relative;

}
.content .par{
    padding-left: 60px;
    padding-bottom: 25px;
    font-family: Arial;
    letter-spacing: 1.2px;
    line-height: 30px;
}
.content h1{
    font-family: 'Times New Roman';
    font-size: 50px;
    padding-left: 60px;
    margin-top: 9%;
    letter-spacing: 2px;
}
.content .cn {
    width: 160px;
    height: 40px;
    background: #89cff0;
    border: none;
    margin-bottom: 10px;
    margin-left: 60px;
    font-size: 18px;
    border-radius: 10px;
    cursor: pointer;
    transition: .4s ease;

}
.content .cn a{
    text-decoration: none;
    color: black;
    transition: .3s ease;
}
.cn:hover{
    background-color: white;

}
.form{
    width: 250px;
    height: 380px;
    background: linear-gradient(to top, rgba(0,0,0,0.8)50%, rgba(0,0,0,0.8)50%);
    position: absolute;
    top: 40px;
    left: 1200px;
    border-radius: 10px;
    padding: 25px;

}
.form h2{
    width: 220px;
    font-family: sans-serif;
    text-align: center;
    color: #89cff0;
    font-size: 22px;
    background-color: white;
    border-radius: 10px;
    margin: 2px;
    padding: 8px;
}
.form input{
    width: 240px;
    height: 35px;
    background: transparent;
    border-bottom: 1px solid #89cff0;
    border-top: none;
    border-right: none;
    border-left: none;
    color: white;
    font-size: 15px;
    letter-spacing: 1px;
    margin-top: 30px;
    font-family: sans-serif;
}
.form input:focus{
    outline: none;
}
::placeholder{
    color: white;
    font-family: Arial;

}
.btnn{
    width: 240px;
    height: 40px;
    background: #89cff0;
    border: none;
    margin-top: 30px;
    font-size: 18px;
}
.btnn:hover{
    background: white;
    color: #89cff0;

}
.btnn a{
    text-decoration: none;
    color: black;
    font-weight: bold;

}
.form .link{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 17px;
    padding-top: 20px;
    text-align: center;

}
.form .link a{
    text-decoration: none;
    color: #89cff0;
}
.liw{
padding-top: 15px;
padding-bottom: 10px;
text-align: center;
}
