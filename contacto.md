---
layout: default
title: Contacto
---


<!-- 
     After implementing this contact form make sure
     
     (Don't needed if like line 13)
     1. you have defined "email: "ventos@protonmail.com" in _config.yml file.
     2. you verify your form on formspree.io.
-->

<form class="wj-contact" action="//formspree.io/sieburger@bol.com.br" method="POST">
    <input type="text" name="email" placeholder="Email Address">
    <textarea type="text" name="content" rows="10" placeholder="Message"></textarea>
    <input type="hidden" name="_next" value="<REDIRECTION LINK> ">
    <input type="hidden" name="_subject" value="New Contact Form Submission">
    <input type="text" name="_gotcha" style="display:none">
    <input type="submit" value="Submit">
</form>


<style>
form.wj-contact input[type="text"], form.wj-contact textarea[type="text"] {
    width: 70%;
    vertical-align: middle;
    margin-top: 0.25em;
    margin-bottom: 0.5em;
    padding: 0.75em;
    font-family: monospace, sans-serif;
    font-weight: lighter;
    border-style: solid;
    border-color: #444;
    outline-color: #2e83e6;
    border-width: 1px;
    border-radius: 3px;
    transition: box-shadow .2s ease;
}
form.wj-contact input[type="submit"] {
    outline: none;
    color: white;
    background-color: #2e83e6;
    border-radius: 5px;
    padding: 0.6em;
    margin: 0.25em 0 0 0;
    border: 3px solid transparent;
    height: auto;
}
</style>

[back](./)