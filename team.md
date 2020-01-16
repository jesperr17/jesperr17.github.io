---
layout: page
title: Het onderzoeksteam
subtitle:
---

<div align="justify"> 
<p>
De volgende onderzoekers maken deel uit van het NEUROTREND team:
</p>
</div>


<html>
<head>
<style>

@media screen and (min-width: 700px) {   

  table          {border: transparent; width:100%;}
  table td       {border:transparent; padding: 10px}
  table th       {border: transparent; padding: 10px; font-family: 'Helvetica Neue'; text-transform: uppercase; font-weight: 800; text-align: center; font-size: 70%;}
  table tr#r1  {background-color: #404040; color:white;}

img {
  width:20vw;
  border-radius: 50%;
  padding: 0;
}

}

@media screen and (max-width: 700px) {   
   table, tr, td { display: block; }
   

img {
	.size {
		width:10vw;
	}
   border-radius: 50%;
}



table {
   width: 100%;
   
   td, th { 
      color: darken($baseColor, 10%);
      padding: $padding; 
   }
   
   td {
      text-align: center;
      vertical-align: middle;
   }
   
   th { 
      background-color: lighten($baseColor, 50%);
      font-weight: 300;
   }

   }
}   

</style>
</head>


<body>

<div>
   <table cellspacing="0">
      <tr>
         <th>Foto</th>
         <th>Naam</th>
         <th>Positie</th>
         <th>Instituut</th>
         <th>Email</th>
      </tr>

      <tr>
         <td><img src="{{ 'img/avatar.png' | relative_url }}" style="border: 3px solid #000000;"></td>
         <td>Drs. F.R. Ramsaransing</td>
         <td>AIOS & PhD-kandidaat </td>
         <td>GGzE & TU/e</td>
         <td> - </td>
      </tr>

      <tr>
         <td><img src="{{ 'img/avatar.png' | relative_url }}" style="border: 3px solid #000000;" ></td>
         <td> Drs. Ir. J. Pilmeyer </td>
         <td>PhD-kandidaat</td>
         <td>TU/e</td>
         <td>j.pilmeyer@tue.nl</td>
      </tr>

      <tr>
         <td><img src="{{ 'img/hello_world.jpeg' | relative_url }}" style="border: 3px solid #000000;"></td>
         <td>Prof. Dr. A.P. Aldenkamp</td>
         <td>Hoogleraar & Klinisch neuropsycholoog</td>
         <td>TU/e, MUMC & Kempenhaeghe</td>
         <td> - </td>
      </tr>
      
      <tr>
         <td><img src="{{ 'img/avatar.png' | relative_url }}" style="border: 3px solid #000000;"></td>
         <td>John Smith</td>
         <td>john.smith@foo.com</td>
         <td>01 800 2000</td>
         <td>Aut voluptatum accusantium, eveniet, sapiente quaerat adipisci consequatur maxime temporibus quas, dolorem impedit.</td>
      </tr>
   </table>
</div>
</body>
</html>


