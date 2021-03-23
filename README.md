# Moje-CV.-Pierwszy-Plik-HTML Wykonany w VSC.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="./css/1.css" />
  <title>Document</title>
</head>
<body>
  <div class="container">
 <aside class="left-side">
  <img
  src="./images/Ork.jpg"
  alt="photo Ork"
  width="270"
  class="photo"
/>

<section class="contacts">
  <h2 class="contacts-title">Contacts</h2>
    <p>E-mail</p>
      <a href="mailto: piskorznorbert@gmail.com" class="contacts-link">piskorznorbert@gmail.com</a>
    <p>Tel:</p>
      <a href="tel:+570360650" class="contacts-link">+570360650</a>
</section>

<section class="Skills">
  <h2 class="Skills-title">Tech Skills</h2>
    <ul class="List">
      <li>HTML</li>
      <li>CSS</li>
      <li>Frezowanie CNC</li>
      <li>Leksykologia</li>
    </ul>
</section>
<section class="Skills">
   <h2>Soft Skills</h2>
     <ul class="List">
       <li>teamwork</li>
       <li>Project Manager</li>
       <li>JavaScript</li> 
     </ul>
</section>
 </aside>

<aside class="right-side">
  <h1 class="Title">Norbert Piskorz</h1>
    <p>Front-end Developer</p>
       <p>Front-end jest odpowiedzialny za pobieranie danych od użytkownika oraz przekazanie ich do back-endu. Następnie back-end na podstawie tych danych wykonuje określone zadanie. Opcjonalnie front-end może pokazać użytkownikowi wyniki otrzymane od back-endu. Często stosowanym tłumaczeniem jest „fasada” i „wnętrze”.</p>

<section class="Employment">
  <h2>Employment history</h2>
     <h3>Ślusarz/Tokarz/Frezer at 
       <span class="accent">Derol</span>
     </h3>
         <p>March 2015 - January 2016</p>
         <ul class="List">
           <li>Czytanie rysuków technicznych</li>
           <li>Frezowanie</li>
           <li>Toczenie</li>
           <li> Skomplikowane prace ślusarskie</li>
         </ul>

      <h3>Frezer at
        <span class="accent">Fabryka Broni Łucznik</span>
      </h3>  
         <p>February 2016 - May 2017</p>
         <ul class="List">
          <li>Czytanie rysuków technicznych</li>
          <li>Frezowanie</li>
          <li>Toczenie</li>
          <li> Skomplikowane prace ślusarskie</li>
         </ul>

         <h3>Specjalista ds. produkcji at
          <span class="accent">Fabryka Broni Łucznik</span>
        </h3>  
           <p>February 2016 - May 2017</p>
           <ul class="List">
            <li>Analiza Danych</li>
            <li>Monitoring Procesów produkcji</li>
            <li>Inwentaryzacja zasobów produkcyjnych</li>
            <li> Nadzór nad procesami produkcyjnymi</li>
           </ul>
 </section>
 <section class="Education">
   <h3>Licenjonowany Filolog Angielski</h3>
      <p>September 2020 - Until Now</p>
 </section>
    
</aside>
</div>
</body>
</html>


<--------CSS---------->

body {
    background-color: rgb(215, 230, 229);
    padding: 40px;
}
.container {
    display: flex;
    width: 1200px;
    margin-left: auto;
    margin-right: auto;
  
    background-color: #fff;
  }
        
.left-side {
    padding-left: 0px;
    width: 370px;
    background-color: rgb(13, 10, 46);
    color: cornsilk;
    margin-bottom: 60px;
}    
.right-side {
    width: 830px;
    padding-left: 80px;
    padding-right: 200px;
    padding-bottom: 68px;
}
.accent {
    color: rgb(233, 155, 54);
}
.contacts-title {
    font-size: 20px;
}
.skills-title {
    font-size: 20px;
}
.photo {
width: 370px;
margin-bottom: 60px;
}
.Title {
    font-size: 48px;
}
