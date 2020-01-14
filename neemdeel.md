---
layout: page
title: Neem deel!
subtitle:
---

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {font-family: Arial, Helvetica, sans-serif;}
* {box-sizing: border-box;}

input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 15px;
  box-sizing: border-box;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=email], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 15px;
  box-sizing: border-box;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}


input[type=submit] {
  background-color: #4CAF50;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}


.container {
  width: 80%;
  border-radius: 15px;
  background-color: #f2f2f2;
  padding: 20px;
}
</style>
</head>
<body>

<h2> Vul de onderstaande gegevens in en dan zullen wij contact met u opnemen! </h2>
<div class="container">
<form id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/j.pilmeyer@tue.nl" method="post">
  <fieldset id="fs-frm-inputs">
    <label for="full-name"> Voor- en achternaam </label>
    <input type="text" name="name" id="full-name" placeholder="Vul hier uw voor- en achternaam in" required="">
    
    <label for="email-address"> Uw email-adres </label>
    <input type="email" name="_replyto" id="email-address" placeholder="email@domein.com" required="">

    <label for="age"> Leeftijd </label>
    <input type="text" name="name" id="age" placeholder="Vul hier uw leeftijd in." required="">
   
    <label for="geslacht"> Geslacht </label>
    <select>
    <option value="man">Man</option>
    <option value="vrouw">Vrouw</option>
    <option value="anders">Anders</option>
    </select>

    <label for="message">Commentaar of vragen</label>
    <textarea rows="5" name="message" id="message" placeholder="Vul hier uw commentaar of vragen in." required=""></textarea>
    <input type="hidden" name="_subject" id="email-subject" value="Contact Form Submission">
  </fieldset>
  <input type="submit" value="Submit">
</form>
</div>
