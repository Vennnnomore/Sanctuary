<html lang="en"> 
 <head> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>project for you</title> 
  <link rel="stylesheet" type="text/css" href="styles.css"> 
 <style type="text/css" id="dcoder_stylesheet">body {

  font-family: 'Arial', sans-serif;

  background-color: #f8f8f8;

}

h1 {

  text-align: center;

  color: #ff69b4;

}

#clickButton {

  display: block;

  margin: 20px auto;

  padding: 10px 20px;

  font-size: 25px;

  background-color: #ff69b4;

  color: white;

  border: none;

  border-radius: 5px;

  cursor: pointer;

}

.popup {

  display: none;

  position: fixed;

  top: 50%;

  left: 50%;

  transform: translate(-50%, -50%);

  background-color: #ffffff;

  border: 2px solid #ff69b4;

  padding: 20px;

  z-index: 1000;

  width: 300px;
  

  text-align: center; /* Center text horizontally */

  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);

}

.love-letter {

  font-style: italic;

  line-height: 1.5;

  text-align: center;

  color: #ff69b4;

}

.buttons {

  margin-top: 20px;

  text-align: cente

  text-align: center; /* Center text horizontally */

  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);

}

.love-letter {

  font-style: italic;

  line-height: 1.5;

  text-align: center;

  color: #ff69b4;

}

.buttons {

  margin-top: 20px;

  text-align: center;

}

.buttons button {
r;

}

.buttons button {

  margin: 0 10px;

  padding: 8px 16px;

  font-size: 16px;

  background-color: #ff69b4;

  color: white;

  border: none;

  border-radius: 5px;

  cursor: pointer;

}

.buttons button:hover {

  background-color: #d154a0;

}
.popup

  color: white;

  border: none;
  

  border-radius: 10px;

  cursor: pointer;

}

.custom-popup button {

  padding: 10px 20px;

  font-size: 20px;

  background-color: #ff69b4;

  color: white;

  border: none;


  border-radius: 10px;

  cursor: pointer;

}

.custom-popup button {

  padding: 10px 20px;

  font-size: 20px;

  background-color: #ff69b4;

  color: white;

  border: none;

  border-radius: 10px;

  cursor: pointer;

}

.custom-popup {

  position: fixed;

  border-radius: 10px;

  cursor: pointer;

}

.custom-popup {
  
  position: fixed;

  top: 50%;

  left: 50%;

  transform: translate(-50%, -50%);

  background-color: #ffffff;

  border: 2px solid #ff69b4;

  padding: 20px;

  z-index: 1000;

  width: 300px;

  text-align: center;

  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);

}

.custom-popup p {

  margin-bottom: 20px;

  color: #ff69b4;
  
}

.custom-popup button {

  margin: 0 10px;

  padding: 10px 20px;


  background-color: #d154a0;
ff69b4;

  color: white;

  border: none;

  border-radius: 5px;

  cursor: pointer;

}

.custom-popup .buttons {

  display: flex;

  justify-content: center;

}

.custom-popup button:first-child {

  margin-right: 10px;

}

.custom-popup button:hover {
  font-size: 16px;

  background-color: #ff69b4;

  color: whi
.custom-popup button {

  margin: 0 10px;

  padding: 10px 20px;

  font-size: 16px;

  background-color: #
.custom-popup button {

  margin: 0 10px;

  padding: 10px 20px;
  

  font-size: 16px;

  background-color: #ff69b4;

  color: white;

  border: none;

  border-radius: 5px;

  cursor: pointer;

}

.custom-popup .buttons {

  display: flex;

  justify-content: center;

}

.custom-popup button:first-child {

  margin-right: 10px;

}

.custom-popup button:hover {
  
  
  background-color: #d154a0;
ff69b4;

  color: white;

  border: none;

  border-radius: 5px;

  cursor: pointer;

}

.cus}

.background-color: #d154a0;
te;

  border: none;

  border-radius: 5px;

  cursor: pointer;

}

.custom-popup .buttons {

  display: flex;
  

  justify-content: center;

}

.custom-popup button:first-child {

  margin-right: 10px;

}

.custom-popup button:hover {

  background-color: #d154a0;

}</style></head> 
 <body> 
  <h1 id="helloLovey">HI JAJA</h1> <button id="clickButton">click to proceed</button> 
  <div id="myModal1" class="popup"> 
   <p class="love-letter">hello my SANCTUARY, i would like to ask you something...</p> <button id="proceedButton">PROCEED</button> 
  </div> 
  <div id="myModal2" class="popup"> 
   <p class="love-letter">Can I court you?</p>
   <div class="buttons"> <button id="yesButton">Yes</button> <button id="noButton">No</button> 
   </div> 
  </div> 
  <script src="script.js"></script> 
 
<script type="text/javascript" id="dcoder_script">document.getElementById("clickButton").addEventListener("click", function() {

  document.getElementById("helloLovey").style.display = "none";

  document.getElementById("clickButton").style.display = "none";

  document.getElementById("myModal1").style.display = "block";

});

document.getElementById("proceedButton").addEventListener("click", function() {

  document.getElementById("myModal1").style.display = "none";

  document.getElementById("myModal2").style.display = "block";

});

document.getElementById("noButton").addEventListener("click", function() {

  var button = document.getElementById("noButton");

  var newPosition = getRandomPosition();

  button.style.position = "absolute";

  button.style.left = newPosition.x + "px";
  

  button.style.top = newPosition.y + "px";

});

document.getElementById("yesButton").addEventListener("click", function() {

  document.getElementById("myModal2").style.display = "none";

  var confirmation = confirm("Thank you for giving me a chance. I know this is just the beginning, but I hope I can show you my sincerity through my actions. I may not be perfect, but I promise to treat you with respect, care, and honesty. Can I court you? ❤️");

  if (confirmation) {

    var message = "You clicked OK in the confirmation dialog!";

    var popupMessage = "Pick one:";

    var button1Text = "🌺";

    var button1Url = "https://codepen.io/mdusmanansari/full/BamepLe";
    
    var button2Text = "🫀";

    var button2Url = "https://codepen.io/morkett/full/VjByYj";

    var popupBox = document.createElement("div");

    popupBox.className = "custom-popup";

    popupBox.innerHTML = `<p>${popupMessage}</p>

                          <button id="flowerButton">${button1Text}</button>

                          <button id="heartButton">${button2Text}</button>`;

    document.body.appendChild(popupBox);

    document.getElementById("flowerButton").addEventListener("click", function() {

      window.location.href = button1Url;

    });

    document.getElementById("heartButton").addEventListener("click", function() {

      window.location.href = button2Url;
      
    });

  }

});

function getRandomPosition() {

  var x = Math.floor(Math.random() * window.innerWidth);

  var y = Math.floor(Math.random() * window.innerHeight);

  return { x: x, y: y };

}</script></body></html>  border: none;

  border-radius: 5px;

  cursor: pointer;

}

.popup {

  display: none;

  position: fixed;

  top: 50%;

  left: 50%;

  transform: translate(-50%, -50%);

  background-color: #ffffff;

  border: 2px solid #ff69b4;

  padding: 20px;

  z-index: 1000;

  width: 300px;
  

  text-align: center; /* Center text horizontally */

  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);

}

.love-letter {

  font-style: italic;

  line-height: 1.5;

  text-align: center;

  color: #ff69b4;

}

.buttons {

  margin-top: 20px;

  text-align: cente

  text-align: center; /* Center text horizontally */

  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);

}

.love-letter {

  font-style: italic;

  line-height: 1.5;

  text-align: center;

  color: #ff69b4;

}

.buttons {

  margin-top: 20px;

  text-align: center;

}

.buttons button {
r;

}

.buttons button {

  margin: 0 10px;

  padding: 8px 16px;

  font-size: 16px;

  background-color: #ff69b4;

  color: white;

  border: none;

  border-radius: 5px;

  cursor: pointer;

}

.buttons button:hover {

  background-color: #d154a0;

}
.popup

  color: white;

  border: none;
  

  border-radius: 10px;

  cursor: pointer;

}

.custom-popup button {

  padding: 10px 20px;

  font-size: 20px;

  background-color: #ff69b4;

  color: white;

  border: none;


  border-radius: 10px;

  cursor: pointer;

}

.custom-popup button {

  padding: 10px 20px;

  font-size: 20px;

  background-color: #ff69b4;

  color: white;

  border: none;

  border-radius: 10px;

  cursor: pointer;

}

.custom-popup {

  position: fixed;

  border-radius: 10px;

  cursor: pointer;

}

.custom-popup {
  
  position: fixed;

  top: 50%;

  left: 50%;

  transform: translate(-50%, -50%);

  background-color: #ffffff;

  border: 2px solid #ff69b4;

  padding: 20px;

  z-index: 1000;

  width: 300px;

  text-align: center;

  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);

}

.custom-popup p {

  margin-bottom: 20px;

  color: #ff69b4;
  
}

.custom-popup button {

  margin: 0 10px;

  padding: 10px 20px;


  background-color: #d154a0;
ff69b4;

  color: white;

  border: none;

  border-radius: 5px;

  cursor: pointer;

}

.custom-popup .buttons {

  display: flex;

  justify-content: center;

}

.custom-popup button:first-child {

  margin-right: 10px;

}

.custom-popup button:hover {
  font-size: 16px;

  background-color: #ff69b4;

  color: whi
.custom-popup button {

  margin: 0 10px;

  padding: 10px 20px;

  font-size: 16px;

  background-color: #
.custom-popup button {

  margin: 0 10px;

  padding: 10px 20px;
  

  font-size: 16px;

  background-color: #ff69b4;

  color: white;

  border: none;

  border-radius: 5px;

  cursor: pointer;

}

.custom-popup .buttons {

  display: flex;

  justify-content: center;

}

.custom-popup button:first-child {

  margin-right: 10px;

}

.custom-popup button:hover {
  
  
  background-color: #d154a0;
ff69b4;

  color: white;

  border: none;

  border-radius: 5px;

  cursor: pointer;

}

.cus}

.background-color: #d154a0;
te;

  border: none;

  border-radius: 5px;

  cursor: pointer;

}

.custom-popup .buttons {

  display: flex;
  

  justify-content: center;

}

.custom-popup button:first-child {

  margin-right: 10px;

}

.custom-popup button:hover {

  background-color: #d154a0;

}</style></head> 
 <body> 
  <h1 id="helloLovey">HAPPY MONTHSARY</h1> <button id="clickButton">click to proceed</button> 
  <div id="myModal1" class="popup"> 
   <p class="love-letter">hello my SANCTUARY, i would like to ask you something...</p> <button id="proceedButton">PROCEED</button> 
  </div> 
  <div id="myModal2" class="popup"> 
   <p class="love-letter">Will you accept my love again for many more months?</p> 
   <div class="buttons"> <button id="yesButton">Yes</button> <button id="noButton">No</button> 
   </div> 
  </div> 
  <script src="script.js"></script> 
 
<script type="text/javascript" id="dcoder_script">document.getElementById("clickButton").addEventListener("click", function() {

  document.getElementById("helloLovey").style.display = "none";

  document.getElementById("clickButton").style.display = "none";

  document.getElementById("myModal1").style.display = "block";

});

document.getElementById("proceedButton").addEventListener("click", function() {

  document.getElementById("myModal1").style.display = "none";

  document.getElementById("myModal2").style.display = "block";

});

document.getElementById("noButton").addEventListener("click", function() {

  var button = document.getElementById("noButton");

  var newPosition = getRandomPosition();

  button.style.position = "absolute";

  button.style.left = newPosition.x + "px";
  

  button.style.top = newPosition.y + "px";

});

document.getElementById("yesButton").addEventListener("click", function() {

  document.getElementById("myModal2").style.display = "none";

  var confirmation = confirm("Thankyou Love for accepting me again. I'm happy for that you still choose my love for you even sometimes i'm being not the boyfriend you deserve. For the past few weeks i'm being a bitch and not the man i promised to you. I'm thankful that you still choose me and never give up on us. One day we will be successful in life and give you the life i promised that you deserved. Love HAPPY MONTHSARY 🥰");

  if (confirmation) {

    var message = "You clicked OK in the confirmation dialog!";

    var popupMessage = "Choose an action:";

    var button1Text = "🌺";

    var button1Url = "https://codepen.io/mdusmanansari/full/BamepLe";
    
    var button2Text = "🫀";

    var button2Url = "https://codepen.io/morkett/full/VjByYj";

    var popupBox = document.createElement("div");

    popupBox.className = "custom-popup";

    popupBox.innerHTML = `<p>${popupMessage}</p>

                          <button id="flowerButton">${button1Text}</button>

                          <button id="heartButton">${button2Text}</button>`;

    document.body.appendChild(popupBox);

    document.getElementById("flowerButton").addEventListener("click", function() {

      window.location.href = button1Url;

    });

    document.getElementById("heartButton").addEventListener("click", function() {

      window.location.href = button2Url;
      
    });

  }

});

function getRandomPosition() {

  var x = Math.floor(Math.random() * window.innerWidth);

  var y = Math.floor(Math.random() * window.innerHeight);

  return { x: x, y: y };

}</script></body></html>
