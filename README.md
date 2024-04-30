# Ex.07 Software Product Company Website
## Date: 30/04/2024

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:

```
home.html

<html>
<title></title>
<style>
    body{
        background-color: purple ;
        background-size: cover;
        
    }

    h1{
        color: aliceblue;
    }
    h2{
        color: aliceblue;
    }
    h3{
        color:tomato;
        align:center;
    }

.styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px;
            background-color: #3498db; 
            color: #ffffff; 
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="button"]:hover {
            background-color:purple; 
            color:aliceblue; 
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; 
            background-color: #3498db; 
            color: #ffffff; 
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="submit"]:hover {
            background-color:purple; 
            color:#ffffff; 
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); 
}

.login{
    margin-top: -100;
    margin-left: 1100;
    margin-right: 100;    
    background:black;

    scroll-padding-left: 5px;
    border:2px solid white;
}
.login input[type="button"] {
    padding: 10px 20px;
    background-color: #3498db;
    color: #ffffff;
    border: none;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}
.login input[type="button"]:hover {
    color:#000;
    background-color:rgb(204, 32, 204);
}
.login input[type="submit"]{
    padding: 10px 15px; /*  button size */
    background-color:#4234db;
    color: #ffffff;
    border-radius: 10px;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}
.login input[type="submit"]:hover {
    color:#000;
    background-color:chocolate;
}
.login input[type="text"] { 
    padding: 10px; 
    transition: background-color 0.3s; 
       
        background-color: #ffffff;
}
.login input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:slateblue; 
}
.join{
    padding: 10px 20px; 
    background-color: #3498db;
    color: #ffffff;
    border: none;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}
.join:hover {
    color: aquamarine;
    background-color: #4234db;
}

/main html/
</style>
<body >
    <form class="styled ">
        <div class=>
            <a href="home.html">
                <input type="button" value="HOME">
            </a>
            <a href="products.html">
                <input type="button" value="OUR PRODUCTS">
            </a>

            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>  
            <input type="text">
            <input type="submit"value="SEARCH">  
        </div>
    </form>

    <h1>WELCOME TO RK TECH</h1>
    <h2>ASSOCIATE YOURSELF WITH PEOPLE OF GOOD QUALITY, FOR IT IS BETER TO BE ALONE THAN IN BAD COMPANY</h2>
    <h2>PRODUCTS</h2>
    <a href="sign.html">
        <input type="button" value="JOIN US" class="join">
    </a>  
    
    <h3>"GOOD COMPANY IN A JOURNEY MAKES THE WAY SEEM SHORTER"</h3>

         <center>
        <div class="login">
            <div class="login-box">
            <p style="color: aliceblue;">DONT HAVE AN ACCOUNT</p>
            <a href="sign.html">
                <input type="button" value="SIGN IN"><br><br>
            </a>  
            <p style="color: aliceblue;">LOGIN</p>
            <input type="text" value="Username or email" ><br><br>
            <input type="text" value="Password"><br><br>
            <a href="products.html">
                <input type="submit" value="SUBMIT"><br><br>
            </a>  
        </div>
        </div>
    </center>

</body>
<footer style="background-color:rgb(139, 0, 0);margin-top: 250; border: none;">
    <P style="color:#ffffff; ;"align="center">Designed and Devoloped by NITHISH KUMAR P 2024 </P>
</footer>
</html>

sign.html

<!DOCTYPE html>
<html>
<head>
    <title>Sign Up</title>
    <style>
        body {
            background-color: purple;
            background-size: cover;
            color: antiquewhite;
            font-family: Arial, sans-serif;
        }

        .form {
            margin: 0 auto;
            width: 300px;
            padding: 20px;
        }

        label {
            color: chocolate;
        }

        .purpose {
            color: aqua;
        }

        .buttons {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #3498db;
            color: #ffffff;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s, color 0.3s;
        }

        .buttons:hover {
            color: aqua;
            background-color: #4234db;
        }
        .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; 
            background-color: #3498db; 
            color: #ffffff; 
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="button"]:hover {
            background-color:purple; 
            color:aliceblue; 
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px;
            background-color: #3498db;
            color: #ffffff; 
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="submit"]:hover {
            background-color:purple; 
            color:#ffffff; 
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); 
}
.text{
    transition: background-color 0.3s, color 0.3s;

}
.text :focus{
    background-color:skyblue;  
}
.full{
    background:black;
    padding: 10px;
    border:4px double white;
}
    </style>
</head>
<body>
    <form class="styled ">
        <div class=>
            <a href="home.html">
                <input type="button" value="HOME">
            </a>
            <a href="products.html">
                <input type="button" value="OUR PRODUCTS">
            </a>
            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>  
            <input type="text">
            <input type="submit"value="SEARCH">  
        </div>
    </form>
    <div class="form">
        <p align="center">JOIN THE FAMILY OF DURGA</p>
        <p align="center">DON'T HAVE AN ACCOUNT YET?</p>
        <div class="full">
        <div class="text">
           
        <label>Unique Username</label>
        <input type="text" value="username"><br><br>
        <label>Email</label>
        <input type="email" value="email"><br><br>
        </div>
        <label>DOB</label>
        <input type="date"><br><br>
        <label>Gender</label><br>
        <div class="purpose">
            <input type="radio" name="gender">Male<br>
            <input type="radio" name="gender">Female<br><br>
        </div>
        <label>Purpose</label><br>
        <div class="purpose">
            <input type="radio" name="purpose">Study<br>
            <input type="radio" name="purpose">Work<br>
            <input type="radio" name="purpose">Partnership<br><br>
        </div>
        <label>Click the checkbox to prove you are human</label>
        <input type="checkbox"><br><br>
        
            <input type="submit" value="CREATE ACCOUNT" class="buttons">
            <input type="submit" value="DOWNLOAD SOFTWARE"class="buttons">
        
    </div>
</div>
</body>
<footer style="background-color:rgb(139, 0, 0);margin-top: 100px; border: none;">
    <P style="color:#ffffff ;"align="center">Designed and Devoloped by NITHISH KUMAR P 2024 </P>
</footer>
</html>

products.html

<html>
    <title>our products</title>
    <style>  
    body{
        background-color: purple;
        background-size:contain;
    } 
    h1{
        color: aliceblue;
    }  
    .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; 
            background-color: #3498db; 
            color: #ffffff; 
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="button"]:hover {
            background-color:purple; 
            color:aliceblue; 
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; 
            background-color: #3498db; 
            color: #ffffff;
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="submit"]:hover {
            background-color:purple;
            color:#ffffff; 
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); 
}
</style>
    
    <body>
        <form class="styled ">
            <div class=>
                <a href="home.html">
                    <input type="button" value="HOME">
                </a>
                <a href="products.html">
                    <input type="button" value="OUR PRODUCTS">
                </a>
                <a href="about.html">
                    <input type="button" value="ABOUT US">
                </a>
                <a href="sign.html">
                    <input type="button" value="SIGN IN">
                </a>
                <a href="contact.html">
                    <input type="button" value="CONTACT">
                </a>  
                <input type="text">
                <input type="submit"value="SEARCH">  
            </div>
        </form>
        
        <center>
            <h1 >OUR PRESTIGEOUS PROJECTS</h1>
        <img src="PRODUCTS.png" height="500" width="800">
    </center>
    </body>
    <footer style="background-color:rgb(139, 0, 0);margin-top:200; border: none;">
        <P style="color:#ffffff; ;"align="center">Designed and Devoloped by NITHISH KUMAR P 2024 </P>
    </footer>
</html>


about.html

<html>
<title>about us</title>
<style>
    p{
        color: antiquewhite;
    }
    body{
        background-color: purple;
        background-size: cover;
    }
    .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; 
            background-color: #3498db; 
            color: #ffffff; 
            border: none;
            transition: background-color 0.3s, color 0.3s;
        }
        .styled [type="button"]:hover {
            background-color:purple;
            color:aliceblue;
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; 
            background-color: #3498db; 
            color: #ffffff; 
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="submit"]:hover {
            background-color:purple;
            color:#ffffff;
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); 
}
.photos{
    display:flex;
    justify-content: space-around;
    margin-top: 200px;
}
.names{
    display:flex;
    justify-content: space-around;

}
.position {
    display: flex;
    justify-content: space-around;
    margin-left: 10px;
    border-image:5px;
    border-image: antiquewhite;
}

</style>
<body>
    <form class="styled ">
        <div class=>
            <a href="home.html">
                <input type="button" value="HOME">
            </a>
            <a href="products.html">
                <input type="button" value="OUR PRODUCTS">
            </a>
            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>  
            <input type="text">
            <input type="submit"value="SEARCH">  
        </div>
    </form>
    <div class="photos">
    <img src="212221040115.jpg" height="200" width="180">
    <img src="3078918.jpg" height="200" width="200">
    <img src="VIJAY.jpeg" height="200" width="200">
    <img src="AJITH.jpeg" height="200" width="200">
    <img src="SURIYA.jpeg" height="200" width="200">
</div>
<div CLASS="names">
    <P style="margin-left:-20;">NITHISH KUMAR P</P>     
    <P>VIRAT KOHLI</P>     
    <P>MR VIJAY</P>    
    <P>MR AJITH KUMAR</P>    
    <P>MR SURIYA</P>    
</div>
<DIV class="position">
    <p>FOUNDER </p>
    <p style="margin-left:20;">CEO </p>
    <p>COFOUNDER</p>
    <p>DIRECTOR</p>
    <p>CO-DIRECTOR </p>

</DIV>
</body>
<footer style="background-color:rgb(139, 0, 5);margin-top:230px; border: none;">
    <P style="color:#ffffff; ;"align="center">Designed and Devoloped by NITHISH KUMAR P 2024 </P>
</footer>
</html>


contact.html

<!DOCTYPE html>
<html>
<head>
    <title>Contact Us</title>
    <style>
        b{
            color:cornflowerblue
        }
        p {
            color: aliceblue;
        }

        body {
            background-color: purple;
        }

        .yourinfo {
            background-color: aqua;
            border:5px solid rgb(232, 71, 71);
            margin-right: 800px ;
            
            margin-top: 200px; 
            padding: 10px; 
        }
        .yourinfo input[type="text"] {
            width: 500px;
            transition: background-color 0.3s; 
        }
        .yourinfo input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color: #2278c3; 
}

        .buttons {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #3498db;
            color: #ffffff;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s, color 0.3s;
        }

        .buttons:hover {
            color: aqua;
            background-color: #4234db;
        }
        .styled form {
            display: flex;
            justify-content: space-evenly;
        }
        .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px;
            background-color: #3498db;
            color: #ffffff; 
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="button"]:hover {
            background-color:purple; 
            color:aliceblue;
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px;
            background-color: #3498db; 
            color: #ffffff; 
            border: none;
            transition: background-color 0.3s, color 0.3s; 
        }
        .styled [type="submit"]:hover {
            background-color:purple; 
            color:#ffffff; 
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); 
}
    
.company{

margin-left: 900px;
margin-top: -330px;
background-color: red;

scroll-padding-left: 5px;
border:2px solid white;
}
.message textarea {
        background-color: white; 
        color: black; 
    }


.message    textarea:focus {
        background-color: cadetblue; 
        color: white; 
    }
    </style>
</head>
<body>
    <form class="styled">
        <div>
            <a href="home.html">
                <input type="button" value="HOME">
            </a>
            <a href="products.html">
                <input type="button" value="OUR PRODUCTS">
            </a>
            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>
            <input type="text" >
            <input type="submit" value="SEARCH">
        </div>
    </form>
    <div class="yourinfo">
        <center>
        <p>Contact Information</p>
        <div>            
            <input type="text" maxlength="100" placeholder="Your Name"><br><br>
            <input type="text" maxlength="100" placeholder="Your Email"><br><br>
            <div class="message">
            <textarea rows="5" cols="65" placeholder="Your Message"></textarea><br><br>
        </div>
            <input type="button" value="SUBMIT" class="buttons">
        
        </center>
        </div>
    </div>
    <div class="company">
        <center>
        <h3 style="color: aliceblue;">COMPANY CONTACT INFORMATION</h3>
       <p> <b >Address</b></p>
        <p >8/188,JEEVA NAGAR</p>
        <p >SINGAPERUMAL KOIL</p>
        <p >CHENGALPATTU-603204</p>
        <b >Email:</b>
        <p >nithishkumar143257@gmail.com</p>
        <b >Phone</b>
        <p >9363019669</p>
    </center>
    </div>
</body>
<footer style="background-color:darkmagenta;margin-top: 200px; border: none;">
    <P style="color:#ffffff ;"align="center">Designed and Devoloped by NITHISH KUMAR P 2024 </P>
</footer>
</html>

```


## OUTPUT:

![alt text](<Screenshot (151).png>)
![alt text](<Screenshot (152).png>)
![alt text](<Screenshot (153).png>)
![alt text](<Screenshot (154).png>)
![Screenshot (157)](https://github.com/nithish143257/softweb/assets/113762839/e89b0663-4810-44ad-b618-eb882f589158)




## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
