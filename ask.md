---
layout: default
title: Ask
description: Ask Jono a question
---


  A mentor to some, a mentee to others. Do you need help with something? Maybe you want to offer advice? Let me know below..

<script>
       function more(){
          document.getElementById("personal").style.display = "block";
          document.getElementById("more-personal").style.display = "none";
       }
    </script>
  <form style="max-width:30em;margin:auto;padding:1em;" class="form-horizontal" netlify name="Ask Jono" action="/" method="POST">
    <fieldset>

    <label for="message">Question</label>
    <div>
    <textarea class="full-width" required id="message" name="message" placeholder="Please enter your question here..." rows="5"></textarea>
    </div>
    
    <div id="more-personal" class="text-right">
        <button onclick="more()" class="btn btn-dark btn-lg">Submit</button>
    </div>
    
    <div id="personal" style="display:none;">
      <label for="name">Name</label>
      <input id="name" class="full-width" name="name" type="text" placeholder="Your name">

      <label for="email">E-mail</label>
      <input id="email" class="full-width" name="Email" type="text" placeholder="Your email" >
    </div>

    <div class="text-right">
        <button type="submit" class="btn btn-dark btn-lg">Submit</button>
    </div>
    </fieldset>
    </form>
