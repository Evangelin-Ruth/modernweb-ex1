## EXPERIMENT 01: TO CREATE A WEB PORTFOLIO/CV USING HTML & CSS
## AIM:
To create a web portfolio/cv using html and css.

## ALGORITHM:
1. Create basic html page.
2. Use div components to separate each section of the webpage.
3. Add css styling to the required components.
4. Link the css file inside the head tag of html file.
5. Run the html page and dsiplay the output.

## PROGRAM:
### PORT.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Portfolio</title>
    
    <link rel="stylesheet" type="text/css" href="port.css">
</head>
<body style="background-color: darksalmon;">
  <img src="resume.jpg">
<div>      
        <nav>
          <ul>
           <center>
             <a class="she" href="#about">About</a>
             <a class="she" href="Education.html">Education</a>
            <a class="she" href="Skills.html">Skills</a>
            <a class="she" href="Service.html">Service</a>
            <a class="she" href="Contact.html">Contact</a>
           </center>
          </ul>
          
        </nav>

    <div class="content">
        <h1>Hello, I’m <hea>Evangelin</hea></h1>
        <p>
            Hi, I am Evangelin, a passionate student and aspiring web developer. 
            I am currently pursuing a degree in Artificial Intelligence abd Data Science
            and have a interest in front-end development. I am always eager to learn 
            new things and take on new challenges.I am looking for a career that would
             improve my skills and knowledge.
        </p>        
   
</body>
</html>
```
## SKILLS.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Portfolio</title>
    
    <link rel="stylesheet" type="text/css" href="port.css">
</head>
<body style="background-color: darksalmon;">
<div>      
        <nav>
          <ul>
           <center>
             <a class="she" href="#about">About</a>
             <a class="she" href="Education.html">Education</a>
            <a class="she" href="Skills.html">Skills</a>
            <a class="she" href="Service.html">Service</a>
            <a class="she" href="Contact.html">Contact</a>
           </center>
          </ul>
          
        </nav>
            <center><h2 class="skills">Skills</center></h2>
            <ul class="skills-list">
                <li>C Programming</li>   
                <li>Python</li> 
                <li>HTML</li>
                <li>Data Science</li>
                <li>Website development</li>
                <li>IOT</li>
                <li>Product Development</li>
                <li>3D Designing</li>
                <li>AR Filter Developing</li>
                <li>Communication skills</li>
                <li>Image processing Techniques</li>
            </ul>
        </div>
    </div>
    </body>
</html>
```
## EDUCATION.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Portfolio</title>
    
    <link rel="stylesheet" type="text/css" href="port.css">
</head>
<body style="background-color: darksalmon;">
<div>      
        <nav>
          <ul>
           <center>
             <a class="she" href="#about">About</a>
             <a class="she" href="Education.html">Education</a>
            <a class="she" href="Skills.html">Skills</a>
            <a class="she" href="Service.html">Service</a>
            <a class="she" href="Contact.html">Contact</a>
           </center>
          </ul>
          
        </nav>
            <center><h2 class="education">Education</h2>
            <div class="cont">
                <h1>School</h1>
                <p>Nazareth Matriculation Higher Secondary School</br>
                SSLC(2019),HSC(2020),SLC(2021)</p>  
            </center> 
        </div>
    </div>
    </body>
</html>
```
## CONTACT.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Portfolio</title>
    
    <link rel="stylesheet" type="text/css" href="port.css">
</head>
<body style="background-color: darksalmon;">
<div>      
        <nav>
          <ul>
           <center>
             <a class="she" href="#about">About</a>
             <a class="she" href="Education.html">Education</a>
            <a class="she" href="Skills.html">Skills</a>
            <a class="she" href="Service.html">Service</a>
            <a class="she" href="Contact.html">Contact</a>
           </center>
          </ul>
          
        </nav>
        <center><h1 class="contact">Contact</h1>
        <div class="contact">
            <h2>Phone number:</h2><br>
            <p class="con">9791102890</p>
            <ul>
                <li style="font-size:21px;"><b>Social Media:</b></li><br>
                <div class="size">
                <a href =https://instagram.com/__evangelin___?igshid=YmMyMTA2M2Y=><img src="insta.png"alt="Instagram" width="50"  ></a>
                <a href =https://www.snapchat.com/add/evangelinshel20?share_id=YhAFKZCQUlA&locale=en-IN><img src="snap1.jpg" width="40"  ></a>
            </div>
                </ul>
        </center> 
    </div>
</div>
</body>
</html>
```
## PORT.CSS
```
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}

  img 
  {
      float: right;
       /* border: 1px solid #ddd; 
       border-radius: 4px; 
       padding: 5px; 
       width: 400px;  */
       padding-top: 140px;  
  }
  


nav {
    align-items: center;
    justify-content: space-between;
    padding: 30px 100px;
    background-color: antiquewhite;

  } 
/* .but {
    display: inline-block;
    padding: 10px 20px;

  } */

  .she {
    color: #1d1d24;
    text-decoration: none;
    padding-left:120px;
  
  } 
  

.content {
    position: absolute;
    top: 30%;
    left: 8%;
  }

.content h1 {
  color: #1f1f25;
  font-size: 75px;
}

.content h1 hea {
    color: #fd4766;
  }

  .content p {
    width: 60%;
    color: #202020;
    font-size: 20px;
  }
  .skills{
    padding:50px;
  }
  .skills-list{
    text-align: center;
    font-size: 25px;
    /* padding: 30px; */

  }
  .cont h1{
    font-size: 50px;
  }
  .cont p{
    font-size: 20px;
  }
  .education{
    padding:50px;
    
  }
 .con{
  font-size: 20px;
 }
.size{
  width: 10;
  height: 30;
}
```
## OUTPUT:
![image](https://github.com/Evangelin-Ruth/modernweb-ex1/assets/94219798/b8d682c3-b1d2-4c22-b0ac-3d00511a1f70)
![image](https://github.com/Evangelin-Ruth/modernweb-ex1/assets/94219798/d932ef0e-c78b-49ae-a737-fca6455aa5f0)
![image](https://github.com/Evangelin-Ruth/modernweb-ex1/assets/94219798/b1214886-f2c6-44f6-80f6-dd4ac6800c7f)
![image](https://github.com/Evangelin-Ruth/modernweb-ex1/assets/94219798/4a5aee6b-f8da-4d95-af13-046af7d14848)

## RESULT:
Thus,a portfolio is created using html and css.

