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
  table th       {border: transparent; padding: 10px;}
  table tr#r1  {background-color: #404040; color:white;}

img {
  width:5vw;
  border-radius: 50%;
  padding: 0;
}

}

@media screen and (max-width: 700px) {   
   table, tr, td { display: block; }
   

img {
	.size {
		width:5vw;
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
         <td>Jane Doe</td>
         <td>jane.doe@foo.com</td>
         <td>01 800 2000</td>
         <td>Lorem ipsum dolor sit amet, consectetur adipisicing elit. </td>
      </tr>

      <tr>
         <td><img src="{{ 'img/avatar.png' | relative_url }}" style="border: 3px solid #000000;" ></td>
         <td>John Doe</td>
         <td>john.doe@foo.com</td>
         <td>01 800 2000</td>
         <td>Blanditiis, aliquid numquam iure voluptatibus ut maiores explicabo ducimus neque, nesciunt rerum perferendis, inventore.</td>
      </tr>

      <tr>
         <td><img src="{{ 'img/avatar.png' | relative_url }}" style="border: 3px solid #000000;"></td>
         <td>Jane Smith</td>
         <td>jane.smith@foo.com</td>
         <td>01 800 2000</td>
         <td> Culpa praesentium unde pariatur fugit eos recusandae voluptas.</td>
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


