# EXPERIMENT 1 - Portfolio-using-HTML-and-CSS
## AIM
To create a Portfolio using HTML and CSS
## ALGORITHM
1. Create a .html document and .css document.
2. Add the main contents of the Portfolio like info about work experience, education, contact in html document.
3. Add the styling part in the .css file
4. Link the .css file to the .html document in the head section
5. Visualise the output in the browser.
## PROGRAM
### shavs.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>shavs cv</title>
    <link rel="stylesheet" type="text/css" href="shavs.css">
</head>
<body>
    <center>
    <div class="hero">
        <nav>
            
            <h1 class="logo">PORTFOLIO</h2>
            <ul>
                <li><a href="#">About</a></li>
                <li><a href="#">Education</a></li>
                <li><a href="#">Work Experience</a></li>
                <li><a href="#">Recent Projects</a></li>
            </ul>
        </nav>
        <div class="content">
            <h4>Hi I'm</h4>
            <h2>Shavedha Yuvarajan</h2>
            <h3>I am a Software Engineer specialised in front end development.</h3>

        </div>
    </div>

<div class="about" style="background-image: url(https://media.istockphoto.com/id/1397590950/vector/abstract-black-metallic-space-design-modern-luxury-background.jpg?s=612x612&w=0&k=20&c=LcGAcv-pSIuo5tYSUcy6fnbxxOTmeb7vgnfbyChXoK8=);">
    <div class="main">
        <div class="abttext">
            <h2>About </h2>
        <h4><p>Hello, my name is Shavedha. I am a Software Engineer with 3 years of experience in FRONT END DEVELOPMENT. 
            Throughout my career, I have developed a strong skill set in website development and have worked on projects for Clients from different countries. 
            I am passionate about front end designing, and am always looking to stay up-to-date with the latest trends and technologies. 
            I am excited to apply my skills and experience to esteemed company and am confident that I would be a valuable asset to your team.</p></h4>
            <img src="" alt="">
            <h2>Technical Skills</h2>
            <ul>
                <li><a href="#" class="btn">App developer</a></li>
                <li><a href="#" class="btn">App developer</a></li>
                <li><a href="#" class="btn">App developer</a></li>
            </ul>
            <h2>Design Skills</h2>
            <ul>
                <li><a href="#" class="btn">App developer</a></li>
                <li><a href="#" class="btn">App developer</a></li>
                <li><a href="#" class="btn">App developer</a></li>
            </ul>
        </div>
        
    </div>
</div>
<div class="about1" style="background-image: url(https://media.istockphoto.com/id/1397590950/vector/abstract-black-metallic-space-design-modern-luxury-background.jpg?s=612x612&w=0&k=20&c=LcGAcv-pSIuo5tYSUcy6fnbxxOTmeb7vgnfbyChXoK8=);">
<div class="main">
    <div class="container">

    <div class="timeline">
        <!-- <div class="vertical-text">EDUCATION TIMELINE</div> -->
        <ul>
            <li>
                <div class="timeline-content">
                    <h1>UNDER GRADUATE DEGREE</h1>
                    <p>UG-DEGREE in Artificial Intelligence and Data Science<br>from Saveetha Engineering College (Yr - 2025)</p>
                </div>
            </li>
            <li>
                <div class="timeline-content">
                    <h1>SENIOR SCHOOL CERTIFICATE EXAMINATION </h1>
                    <p>Completed 12th Standard with 90.6% in Velammal Vidyalaya (Yr-2021)</p>
                </div>
            </li>
            <li>
                <div class="timeline-content">
                    <h1>SECONDARY SCHOOL EXAMINATION</h1>
                    <p>Completed 10th Standard with 92% in Velammal Vidyalaya (Yr - 2019)</p>
                </div>
            </li>
        </ul>
    </div>
</div>
</div>
</div>
<div class="about1" style="background-image: url(https://media.istockphoto.com/id/1397590950/vector/abstract-black-metallic-space-design-modern-luxury-background.jpg?s=612x612&w=0&k=20&c=LcGAcv-pSIuo5tYSUcy6fnbxxOTmeb7vgnfbyChXoK8=);">
    <div class="main">
        <div class="service">
            <div class="title">
                <h2>Work Experience and Internships</h2>
            </div>
            <div class="box">
                <div class="card">
                    <i class="fa-solid fa-bars"></i>
                    <h5>Monolith Research and Training Labs</h5>
                    <div class="pra">
                       <p >I have done intership and have experience in data analysis, machine learning, and predictive modeling.
                       </p> 
                       <p style="text-align: center;">
                      <a class="button" href="#">Read More</a>   
                    </p>
                    </div>
                </div>
                <div class="card">
                    <i class="fa-regular fa-user"></i>
                    <h5>Front-end Developer</h5>
                    <div class="pra">
                       <p >With a keen eye for design and a solid understanding of web technologies, 
                        I specialize in creating intuitive and visually appealing interfaces.
                        
                       </p> 
                       <p style="text-align: center;">
                      <a class="button" href="#">Read More</a>   
                    </p>
                    </div>
                </div>
                <div class="card">
                    <i class="fa-solid fa-bell"></i>
                    <h5>Cloud Computing</h5>
                    <div class="pra">
                       <p >With expertise in cloud platforms such as Azure, I leverage the power of cloud computing to optimize performance, 
                        and drive innovation for businesses.
                       <p style="text-align: center;">
                      <a class="button" href="#">Read More</a>   
                    </p>
                    </div>
                </div>
            </div>
        </div> 
    </div>

</div>
</center>
</body>
</html>
```
### style.css
```
.hero{
    
    height: 70vh;
    width: 90%;
    background-image: url(https://media.istockphoto.com/id/1397590950/vector/abstract-black-metallic-space-design-modern-luxury-background.jpg?s=612x612&w=0&k=20&c=LcGAcv-pSIuo5tYSUcy6fnbxxOTmeb7vgnfbyChXoK8=);
    background-size: cover;
    white-space: nowrap;
    display: block;
    
}
.nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-top: 45px;
    padding-left: 8%;
    padding-right: 8%;
}
.logo{
    color: white;
    font-size: 35px;
    letter-spacing: 2px;
    text-align: left;
    margin-left: 30px;
    padding: 10px 30px 20px 50px;
    font-family:Georgia, 'Times New Roman', Times, serif
}
nav ul li{
    list-style-type: none;
    display: inline;
    padding: 10px 30px 20px 50px;
    
}
nav ul li a{
    color: rgb(215, 131, 22);
    font-size: 20px;
    text-transform: capitalize;
    font-weight: bold;
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
}
.content{
    position:absolute;
    top: 50%;
    left: 8%;
    text-align: left;
    transform: translateY(-50%);
    padding-bottom: 1px
}


h4{
    color: aliceblue;
    letter-spacing: 2px;
    font-family: 'Courier New', Courier, monospace;
}
h2{
    color: aliceblue;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: 25px;
    letter-spacing: 2px;
}
h3{
    color: aliceblue;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: 20px;
    letter-spacing: 2px;
}
.about{
    height: 100vh;
    width: 90%;
    background-size: cover;
    
    
}
.main{
    width: 1130px;
    max-width: 95%;
    margin: 0 auto;
    display: flex;
    align-items: center;
    justify-content: space-around;
}
.abttext h2{
    font-size: 35px;
    color: rgb(215, 131, 22);
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    text-align: left;
    padding-left: 400px;
}
.abttext p{
    padding-left: 400px;
    text-align: left;
    font-family:sans-serif;
    color: white;
}

.abttext h3{
    font-size: 25px;
    color: rgb(215, 131, 22);
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.abttext ul li{
    list-style-type: none;
    display: inline-block;
    padding-left: 30%;
}
.btn{
    background-color: black;
    color: white;
    text-decoration: none;
    border: 2px solid snow;
    font-weight: bold;
    padding: 10px 30px;
    border-radius: 20px;
    transition: transform .4s;
}
.about1{
    height: 100vh;
    width: 90%;
    background-size: cover;
}
.container{
    align-items: center;
    justify-content: center;
}
.timeline{
    width: 80%;
    height:auto;
    max-width: 800px;
    margin: 0 auto;
    position: relative;
}
.timeline ul{
    list-style: none;
}
.timeline ul li{
    padding: 20px;
    background-color: #cd874a;
    color: white;
    border-radius: 10px;
    margin-bottom: 20px;
}
.timeline ul li:last-child{
    margin-bottom: 0;
}
.timeline-content h1{
    font-size: 25px;
    
    line-height: 20px;
    margin-bottom: 10px;

}
.timeline-content p{
    font-size: 16px;
    line-height: 30px;
    font-weight: 300;
    
}
@media only screen and (min-width:760px){
    .timeline::before{
        content: '';
        position: absolute;
        height: 100%;
        width: 2px;
        left: 50%;
        transform: translateX(-50%);
        background-color: gray;
    }
    .timeline ul li{
        width: 80%;
        position: relative;

    }
    .timeline ul li:nth-child(odd){
        float: left;
        clear: right;
        transform: translateX(-30px);
    }
    .timeline ul li:nth-child(even){
        float: right;
        clear: left;
        transform: translateX(30px);
    }

}
.title h2{
    color: rgb(215, 131, 22);
    font-size: 40px;
    width: 1130px;
    margin: 30px auto;
    text-align: left;
    padding-left: 200px;
}
.box{
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 400px;
}
.card{
    height: 275px;
    width: 230px;
    padding: 20px 35px;
    background: #191919;
    border-radius: 20px;
    margin: 15px;
    position: relative;
    overflow: hidden;
    text-align: center;
}
.card i{
    font-size: 50px;
    display: block;
    text-align: center;
    margin: 25px 0px;
    color: #858585;
}
h5{
    color: whitesmoke;
    font-size: 25px;
    margin-bottom: 15px;
}
.pra p{
    color: burlywood;
    font-size: 16px;
    line-height: 27px;
    margin-bottom: 25px;
 }
 .card .button{
    background-color: #d2691e;
    color: white;
    text-decoration: none;
    border: 2px solid transparent;
    font-weight: bold;
    padding: 9px 22px;
    border-radius: 30px;
    transition: .4s;
}
.vertical-text {
    writing-mode: vertical-lr; /* Rotates the text vertically */
    text-orientation: upright; /* Keeps the text upright */
    white-space: nowrap; /* Prevents text from wrapping */
  }
.image-container {
    display: flex; /* Use flexbox to control layout */
    /* Center items vertically within the container */
  }

.image-container img {
    max-width: 10%; /* Ensure the image does not exceed its container */
    margin-right: 10px; /* Add some spacing between the image and other elements */
  }
```
## OUTPUT
![Web capture_11-6-2023_01938_](https://github.com/Shavedha/Portfolio-using-HTML-and-CSS/assets/93427376/ccc34a3e-25e2-4f23-a525-a1e6ddbe4b46)

## RESULT
Thus a portfolio is created using html and css
