# My-portfolio 
# HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chetan portfolio</title>
    <link rel="stylesheet" href="chetan.css"/>
</head>
<body>
    <h1 id="mainheading">Chetan Bhargava </h1>
   <div id="aboutme">  <div id="aboutme1">About Me</div>   Hi, my name is CHETAN BHARGAVA.I am a research scholor in IIT Jodhpur.I have worked in several
    fields like techanical,management and education.my driving forces are passion for learning,creativity,making a 
    positive impact.outside the professional realm you will find me immersed in cycling and badminton.
    </div>
    <div id="pic">
</div>
<div id="postgra">Post Graduation: Completed from IIT Jodhpur from 2022 to 2024 </div>
<span id="down1">&#8595;</span>
<h2 id="timeline">Career Timeline</h2>
<div id="developer">Worked as web developer in Elipi Software Solution from june 2020 to april 2022.
    Their i worked on front end using several tools like HTML,CSS and java script.
</div>
<span id="down2">&#8595;</span>
<div id="faculty">Worked as a mechanical faculty in Advance Engineering Classes from june 2018 to
    march 2020.</div>
    <span id="down3">&#8595;</span>
    <div id="manager">Worked as Business Development Manager in Equipshare a construction based
        startup. their i worked from aug 2015 to april 2018.</div>
        <span id="down4">&#8595;</span>
    <div id="Graduation">I have completed B.tech in Mechanical Engineering in 2013 from UIT RGPV BHOPAL.</div>
    <span id="down5">&#8595;</span>
    <div id="highersec">Completed Higher Secondary in 2008 from Excellence School,Shivpuri</div>
    
   <div id="Certification"> <ol>
        <li>  Certification on Full Stack Web Development from Interpid Websoul Private Limited.</li>
        <br>
        <li>NPTEL Certification on Python for Data Science.</li>
        <br>
        <li>Certification on Data Analytics and Fundamentals of Machine Learning for Process Modelling from IIT Jodhpur.</li>
    </ol></div>
    <h3 id="certi">Certification</h3>
    <div id="projects">
        <ol>
            <li> Simon Say Game using front end tools like HTML,CSS,JS.</li><br>
            <li> Amazon Clone using front end tools like HTML,CSS.</li><br>
            <LI>Black Friday Sales Data Analysis using tools like Pandas,<br>Matplotlib.</LI><br>
            <li>Human activity recognition using smart phone data.</li>

        </ol>
    </div>
    <h3 id="proj">Projects</h3>

    <div id="skills">
        <ul>
            <li><b ><u>Programming language</u></b>: Java,Python,Java script</li><br>
            <li><b><u>Web skills</u></b>: HTML,CSS,JS</li><br>
            <li><b><u>Libraries/Frameworks</u></b>:React<br>Tailwind,Numpy,Pandas<br>Metplotlib,Tableau</li>
        </ul>
    </div>
    <h3 id="techanicalskills">Techanical Skills</h3> 
    <div id="contact">
        <b><u>Email</u></b>: bhargavachetan56@gmail.com<br><br>
       <b><u>Contact no</u></b> : 7838330407<br><br>
       <b><U>Adress</U></b> : 34 Mohan nagar behind vishnu temple,shivpuri (M.P)
    </div>
    <h3 id="contecttext">Contect</h3>

   
</body>
</html>

# CSS

*{
    background-color: rgb(54, 171, 171);
}
#aboutme{
    height: 150px;
    width: 700px;
    border: 2px solid black;
    position: absolute;
    left: 350px;
    
    
    font-family: cursive;
    color: black;
    padding-left: 10px;
    
    border-radius: 10px;
    
}

#pic{
    height: 150px;
    width: 150px;
    border: 2px solid black;
    position: absolute;
    right: 25px;
    background-image: url(GATE\ PHOTO.jpg);
    background-size: cover;
    
    border-radius: 10px; 
    
}
#mainheading{
    text-align: center;
    text-decoration:  underline;
    font-family: cursive;
    color: rgb(120, 71, 165);
    
    
    
}
#aboutme1{
    text-align: left;
    text-decoration: underline;
    
    
    color: rgb(47, 47, 204);
    font-size: 25px;
    padding-left: 270px;
    
}
#postgra{
    height: 50px;
    width: 700px;
    border: 2px solid black;
    position: absolute;
    top: 300px;
    left: 350px;
    border-radius: 10px;
    font-family: cursive;
    padding-left: 10px;
}
#timeline{
    position: absolute;
    top: 230px;
    left: 600px;
    font-family: cursive;
    color: rgb(120, 71, 165);
    font-size: 25px;
    text-decoration: underline;

}
#developer{
    height: 50px;
    width: 700px;
    border: 2px solid black;
    position: absolute;
    top: 400px;
    left: 350px;
    border-radius: 10px;
    font-family: cursive;
    padding-left: 10px;
}
#faculty{
    height: 50px;
    width: 700px;
    border: 2px solid black;
    position: absolute;
    top: 500px;
    left: 350px;
    border-radius: 10px;
    font-family: cursive;
    padding-left: 10px;
}
#manager{
    height: 50px;
    width: 700px;
    border: 2px solid black;
    position: absolute;
    top: 600px;
    left: 350px;
    border-radius: 10px;
    font-family: cursive;
    padding-left: 10px;
}
#Graduation{
    height: 50px;
    width: 700px;
    border: 2px solid black;
    position: absolute;
    top: 700px;
    left: 350px;
    border-radius: 10px;
    font-family: cursive;
    padding-left: 10px;
}
#Certification{
    height: 350px;
    border: 2px solid black;
    width: 240px;
    position: absolute;
    top: 305px;
    left: 50px;
    border-radius: 10px;
    font-family: cursive;
}
#certi{
    position: absolute;
    top: 250px;
    left: 120px;
    font-family: cursive;
    font-size: 20px;
    color: rgb(120, 71, 165);
}
#projects{
    position: absolute;
    height: 550px;
    width: 150px;
    border: 2px solid black;
    right: 20px;
    top: 305px;
    font-family: cursive;
    border-radius: 10px;
    justify-content: center;


}
#proj{
    position: absolute;
    top: 250px;
    right: 55px;
    font-family: cursive;
    font-size: 20px;
    color: rgb(120, 71, 165);

}
#skills{
    height: 200px;
    width: 260px;
    border: 2px solid black;
    position: absolute;
    top: 700px;
    left: 50px;
    font-family: cursive;
    border-radius: 10px;
    
}
#highersec{
    height: 50px;
    width: 700px;
    border: 2px solid black;
    position: absolute;
    top: 800px;
    left: 350px;
    border-radius: 10px;
    font-family: cursive;
    padding-left: 10px;
}
#techanicalskills{
    position: absolute;
    top: 645px;
    left: 100px;
    font-family: cursive;
    font-size: 20px;
    color: rgb(120, 71, 165);
}
#contact{
    height: 145px;
    width: 300px;
    border: 2px solid black;
    position: absolute;
    left: 25px;
    border-radius: 10px;
    font-family: cursive;
    padding-left: 10px;
    padding-top: 5px;

}
#contecttext{
    position: absolute;
    top: 25px;
    left: 140px;
    font-family: cursive;
    font-size: 20px;
    color: rgb(120, 71, 165);
}
#down1{
    height: 20px;
    width: 20px;
    font-size: 35px;
    position: absolute;
    left: 680px;
    top: 355px;
    color: rgb(47, 47, 204);
    
}
#down2{
    height: 20px;
    width: 20px;
    font-size: 35px;
    position: absolute;
    left: 680px;
    top: 455px;
    color: rgb(47, 47, 204);
    
}
#down3{
    height: 20px;
    width: 20px;
    font-size: 35px;
    position: absolute;
    left: 680px;
    top: 555px;
    color: rgb(47, 47, 204);
    
}
#down4{
    height: 20px;
    width: 20px;
    font-size: 35px;
    position: absolute;
    left: 680px;
    top: 655px;
    color: rgb(47, 47, 204);
    
}
#down5{
    height: 20px;
    width: 20px;
    font-size: 35px;
    position: absolute;
    left: 680px;
    top: 755px;
    color: rgb(47, 47, 204);
    
}

