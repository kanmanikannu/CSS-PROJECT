#  HTML AND CSS PAGE TO RE-CREATE THE IMAGE
### AIM
To re-create a HTML and CSS page based on the given image.
### PROGRAM
#### contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RoopTech Contact</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="header">
        <div class="logo">
            <span class="red">R</span><span class="white">OOP</span><span class="red">T</span><span class="white">ECH</span>
        </div>
        <div class="nav">
            <a href="home.html">Home</a>
            <a href="#">Products</a>
            <a href="#">People</a>
            <a href="contact.html">Contact</a>
            <div class="search-bar">
                <input  type="text" placeholder="Enter to Search">
                <button>Search</button>
            </div>
        </div>
    </div>
    <div class="content">
    <form  method="get">
                    
        <div class="container">
            <h1 style="font-weight: bold;color: skyblue;">Contact us</h1>
            <input type="text" placeholder="Your Name" name="uname" required><br>
            <input type="email" placeholder="Your Email" name="email" required>
            <div style="padding: 20px 10px;">
               <input type="button" value="Submit">
            
            </div>
        
    </form>
    
    </div>
    <div class="content1">
        <h2 style="color: skyblue;">Contact Information</h2>
        <p><strong class="red">Address:</strong> 3RD Floor, Tower 12, FCA Building No. 18, ROOP DEVELOP CITY, Phase-I, SECUNDERABAD HR IN 1888546</p>
        <p><strong class="red">Email:</strong> rooptech.official@gmail.com</p>
        <p><strong class="red">Phone:</strong> 1234567890</p>
    </div>

</body>
</html>
```
#### style.css
```
body {
            background-image: url('background_image.jpg');
            background-size: cover;
            color: white;
        }
        .header {
            display: flex;
            align-items: center;
            padding: 20px;
        }
        .logo{
            font-size: 35px;
            font-weight: bold;
            padding-left: 60px;
            
        }
         .red {
            color: skyblue;
        }
         .white {
            color: white;
        }
        .nav {
            display: flex;
            align-items: center;
            padding-left: 200px;
            gap: 20px;
        }
        .nav a {
            color: white;
            text-decoration: none;
            font-size: 20px;
        }
        .nav a:hover {
            color: skyblue;
        }
        .search-bar {
            display: flex;
           padding-left: 150px;
        }
        .search-bar input {
            padding: 5px;
            border: none;
            border-radius: 5px 0 0 5px;
            background-color: #585656;
            color: white;
            
        }
        .search-bar button {
            padding: 5px 10px;
            border: none;
            border-radius: 0 5px 5px 0;
            background: red;
            color:white;
            cursor: pointer;
            
        }
        .content{
    position: absolute;
    top: 52%;
    left: 30%;
    transform: translate(-50%,-50%);
    color: #fff;
    text-align: center;
    
}

form {
    border: 3px solid white;
    padding: -0.2px;
    border-radius: 15px;
}

 form input[type=text], input[type=email] {
  background: none;
  padding: 10px 14px;
  margin: 8px 0;
  color: white;
  display: inline-block;
  border: 1px solid white;
  box-sizing: border-box;
  border-radius: 5px;
  width: 200px;
}
form input[type=button]{
    border-radius: 20px;
    color: white;
    background-color: red;
    padding: 8px 30px 8px 30px;
}
.container {
  padding: 10px 20px;
}

.content1{
    position: absolute;
    top: 52%;
    left: 180%;
    transform: translate(-50%,-50%);
    color: #fff;
    text-align: left;
    border: 3px solid white;
    padding: 20px;
    border-radius: 15px;
    width: 220px;
}
```
### OUTPUT
![image](https://github.com/user-attachments/assets/d6d98e24-7253-441f-b345-8b11d2b493f5)
### RESULT
Thus the program has been completed successfully.
