# portfoilo-using-html-css
simple portfolio using html and css
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">



<style>

    
header{
position: fixed;
top: auto;
background-color: brown;
font-family: 'Times New Roman', Times, serif;
font-size: 30px;
width: 100%;
height: 50px;
text-align: right;


}
*{
    padding: 0%;
    margin: 0%;
}

.pad{

padding-right: 20px;
text-decoration:none;
color: white;

}
main{
    display: grid;
    grid: 620px 650px 565px/  auto;
    text-align: center;
}
.grid1{
background-color: black;
font-size: 40px;
color: white;
font-family:monospace;


}

.grid2{
background-color: rgb(42, 69, 109);
font-size: 40px;
font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
}

.grid3{
background-color: rgb(127, 143, 156);
font-size: 25px;
font-family:monospace;
padding-top: 100px;
}


.site{
    display: grid;
    grid: 200px/  auto auto auto;
    text-align: center;
    grid-gap: 10px;
}
.site_pic{
    padding-top: 30px;
height: 350px;
width: 350px;

}
input{

    background-color: rgb(137, 148, 147);
    color: rgb(119, 44, 44);
    width: 350;
    height: 50;
    border-style: none;
    font-size: 20px;
    margin-top: 20px;
}

input:hover{
    background-color: black;
    color: white;
}

.social{
    color: white;
padding-top: 40px;

}

</style>




<body>
    
<header>
    <a class="pad" href="#">About</a>
    <a class="pad" href="#Work">Work</a>
    <a class="pad" href="#Contact">Contact</a>
</header>
<main>
    <div class="grid1">
        <h1 style="padding-top: 200px;">
            Hi I'm ikram
        </h1>
        <p style="color: brown;font-style: italic;">a web develper</p>
        <p style="font-family: 'Times New Roman', Times, serif; font-size: 20px;color: white;padding-left: 40px;padding-right: 40px;padding-top: 20px;">Graduated from University of Engineering and Technology Peshawar as a Computer systems engineer.
            A computer systems engineer develops, tests, and evaluates software and personal computers by 
            combining their knowledge of engineering, computer science, and math analysis.</p>
    </div>


    <div class="grid2" id="Work">
        <h3 style="padding-top: 80px;color: white;font-family: monospace;">
            These are some of my projects
        </h3>
        <div class="site">
            <div>
                <img class="site_pic" src="1.jpg" alt="logo" />
                <input type="button" name="Learn more" value="Learn more">
            </div>

            <div>
                <a href="http://ikramsalarzai.pythonanywhere.com/">
                <img class="site_pic" src="my.jpg" alt="logo" />
                <input type="button" name="Learn more" value="Learn more">
                </a>
            </div>

            <div >
                <a href="https://salarzaibajaurs.wordpress.com/">   
                <img class="site_pic" src="bajaur.jpg" alt="logo" />
                
                <input type="button" name="Learn more" value="Learn more">
            </a>
            </div>


        </div>




    </div>

    <div class="grid3" id="Contact">
        <h1 style="color:white">
            Let's work together...

        </h1>
        <p style="font-family: sans-serif;font-style: italic;font-size: 20px;color: white;padding-top: 10px;">
            How do you take your coffee?
        </p>
        <div class="social">
            <a href="https://www.facebook.com/ikramsalarzaii/">
            <i class="	fa fa-facebook-square fa-lg" > Facbook&nbsp;&nbsp;</i></a>
            
            <a href="https://github.com/ikramsalarzai">
                
            <i class="fa fa-github-square fa-lg"> Github&nbsp;&nbsp;</i> </a>

            <a href="https://www.linkedin.com/in/ikramsalarzai/">
            <i class="fa fa-linkedin-square	fa-lg
            ">Linkedin&nbsp;&nbsp;</i> </a>

            <a href="https://www.twitter.com/ikramsalarzaii/">
            <i class="fa fa-twitter	fa-lg
            "> Twitter &nbsp;&nbsp;</i></a>
            
            <a href="">
            <i class="fa fa-whatsapp	fa-lg
            "> Whatsapp </i></a>


        </div>

        <hr color="brown" style="margin-top:120px;">
        <p style="color: white;font-family:Georgia, 'Times New Roman', Times, serif; padding-top: 40px;font-size: 15px;"> **This is just a fake portfolio. All the projects and contact details given are real.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; © Created Ikram Khan     </p>

    </div>



</main>



</body>
</html>
