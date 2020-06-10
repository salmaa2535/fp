<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
    <style>
      .imageborder { 
        border: 10px solid transparent;
        padding: 15px;
        border-image: url(borderleaf.png)round;
        border-image-slice: 10;
        width: 50%;
      }
      .accordion{
        background-color: black;
        color: lightblue;
        curser: none;
        padding: 18px;
        width: 100%;
        text-align: center;
        outline: none;
        transition: .4s;
      }
      
      .accordion:hover{
        background-color: black
      }
      .panel{
        padding:18px;
        background-color: lightblue;
        display: none;
        overflow: hidden;
      }
      </style>
  </head>
  <body>
    <p class="imageborder"> WELCOME TO SALMA'S MEDICAL PROJECT</p>
    <height="10px" width="10px">
    <button class= "accordion">About Me</button>
    <div class="panel">
      <p>
        Hey there, my name is Salma and I am a sophomore in high school. I'm from Egypt born and raised in New york. I have 3 siblings aka 3 brothers 0 sisters. I'm my mamas girl. 
      </p>
    </div>
    <button class="accordion">Asthma</button>
    <div class="panel">
      <p>
        Asthma is an important topic to me because I have asthma myself and I understand how it works and also how it can affect someones health. Asthma has affected my life because I had it ever since I was 4 and it's been 12 years living with this. I can't do some activities in my life such as runniing just for the reason that I have shortness of breath and many more things. 
        <br> 
        <br>
        Asthma is a chronic lung disease that inflames and narrows the airways. Asthma can wheezing chest tightness, shortness of breath, and coughing.
        People who have asthma may experience symptoms that can be from medium to severe and that can happen rarely or every day. When symptoms get worse, it is called an asthma attack. Asthma affects people of all ages and often starts during childhood. Doctors tell you your level of asthma by your symptoms.
        It can be mild night asthma,mild persistent asthma,moderate persistent asthma, severe persistent asthma. Severe asthma is you have ongoing symptoms both day and night. They’re so frequent that you have to limit your activities. During an asthma attack, your lung airways become swollen and inflamed. During an attack it can be treated at home but sometimes it can be a life threatening emergency.
      </p>
      <img src="asthma.jpg"> 
      <height="100px" width="100px">
    </div>
    <button class= "accordion">Down Syndrome</button>
    <div class="panel">
      <p> 
        People with down syndrome are born with an extra chromosome. This extra chromosome leads to a range of issues that affect you both mentally and physically. Down syndrome is a lifelong condition. People with down syndrome may have a physical feature like others such as a flat noses and small ears. As they grow up, they learn new skills but it can take them a while certain goals such as talking. Also some people have other conditions while others only have down syndrome as their only medical condition.
        The best treatment for people with down syndrome could be receiving care from a team of health professionals, physicians, special educators,speech ,etc. All professionals who interact with children with Down syndrome should provide encouragement.
        <br>
        <br>
        One of my cousin's has down syndrome and I can tell that it affects his life in speaking because most of the time he can't pronounce peoples names such as Salma. Many people can tell when a person has down syndrome but when it comes to my cousin, they are surprised because he doesn't look like he has down syndrome. No matter what happens, I love my cousin and I am the closest cousin to him. 
      </p>
      <img src="downsyndrome.jpg">
      <height="10px" width="10px">
    </div>
    <button class= "accordion">Pharmacy</button>
    <div class="panel">
      <p>
        Pharmacy is like the preparation and dispensing of drugs as well as the counseling of patients in the proper use of these drugs. Pharmacists must store medications under cooled environments and this includes protection from heat, light,etc. Pharmacists go through special systems to make sure that the prescribed medicine is filled correctly. Pharmacists calculate the dosages of mg to put in medicine. Dosages depend on your weight and age. A child may be infected if they are prescribed with the wrong medication.
        <br>
        <br>
        I am interested in Pharmacy because I want to know the history of pharmacy or even how people calculate the dosage of pills, what to provide for patients,etc.
      </p>
      <img src="pharmacy.jpg">
      <height="10px" width="10px">
    </div>
    <button class= "accordion">Sources</button>
    <div class="panel">
      <p>
      <a href="https://www.mayoclinic.org/diseases-conditions/asthma/symptoms-causes/syc-20369653">Asthma</a>
      <a href="https://www.nhlbi.nih.gov/health-topics/asthma">Asthma</a>
      <a href="https://www.mayoclinic.org/diseases-conditions/down-syndrome/symptoms-causes/syc-20355977">Down Syndrome</a>
      <a href="https://www.medicaldaily.com/pharmacy-prescription-drugs-378078">Pharmacy</a>
      </p>
    </div> 
<script src="script.js"></script>
<script>
var acc = document.getElementsByClassName("accordion");
var i;
for (i = 0; i < acc.length; i++) {
 acc[i].addEventListener("click", function() {
   var panel = this.nextElementSibling;
   if (panel.style.display === "block") {
     panel.style.display = "none";
   } else {
     panel.style.display = "block";
   }
 });
}
 </script>
    <script src="script.js"></script>
  </body>
</html>