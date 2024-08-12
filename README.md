This file that I created is displayed on the desktop and looks bad on the mobile phone.  For this, you must use the dcoder program and remove the background, move the buttons and delete the Persian text .Instead of a question like do you love me?  You can also add funny questions😁😏 this is all code for mobile , just copy it and make love.html 



<!doctype html>

<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title> do you love me ? </title>

<link rel="stylesheet" href="styles.css">

<style>

        h1 {

         font-size: 30px; /* Adjust  the font size as needed */

        }

    </style>

<style type="text/css" id="dcoder_stylesheet">/* Set up */

body {



    background-repeat: no-repeat;

    background-size: cover;

}



/* Center the h1 element */

h1 {

    position: absolute;

    left: 50%;

    top: 200px;

    transform: translateX(-50%);

    background-color: hsl(60, 92%, 49%); /* Red */

    border: none;

    color: rgb(32, 29, 29);

    padding: 20px 35px;

    text-align: center;

    text-decoration: none;

    display: inline-block;

    font-size: 16px;

}



/* Center the YES button */

#yes-button {

    position: absolute;

    left: 20%; /* Adjust the position */

    top: 300px;

    background-color: #4CAF50; /* Green */

    border: none;

    color: white;

    padding: 15px 32px;

    text-align: center;

    text-decoration: none;

    display: inline-block;

    font-size: 16px;

    box-shadow: 0 12px 16px 0 rgba(0,0,0,0.24), 0 17px 50px 0 rgba(0,0,0,0.19);

}



/* Center the NO button */

#no-button {

    position: absolute;

    left: 62%; /* Adjust the position */

    top: 300px;

    background-color: #f40505; /* red */

    border: none;

    color: white;

    padding: 15px 32px;

    text-align: center;

    text-decoration: none;

    display: inline-block;

    font-size: 16px;

    box-shadow: 0 12px 16px 0 rgba(0,0,0,0.24), 0 17px 50px 0 rgba(0,0,0,0.19);

}</style></head>

<body>

    <h1>do you love me?</h1>

    <input id="yes-button" type="button" value="YES" onclick="clickYesButton()">

    <input id="no-button" type="button" value="NO" onmouseover="hoverNoButton()">

    <script src="scripts.js"></script>



<script type="text/javascript" id="dcoder_script">



//click yes btn

function clickYesButton() {

    alert('منم دوستت دارم عشقممممم . i love you tooooo<3');

}



//move button on hover

function hoverNoButton() {

    // random from 0 to 1, then multiply with screen size

    let x = Math.random() * window.innerWidth;

    let y = Math.random() * window.innerHeight;



    document.getElementById('no-button').style.left = x + 'px';

    document.getElementById('no-button').style.top = y +'px';

    

}</script></body></html>
