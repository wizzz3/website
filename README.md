<!DOCTYPE html>
<html>
<head>
<style>
div.a {
  text-align: center;
</style>
</head>
<body>
<style>
.container-fluid > .row:first-of-type > div:not(:only-child) {
  z-index: 1;
}

.button {
  background-color: #4CAF50; /* Green */
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: block;
  font-size: 16px;
  margin: 0 auto;
  cursor: pointer;
  -webkit-transition-duration: 0.4s; /* Safari */
  transition-duration: 0.4s;
}

.button2:hover {
  box-shadow: 0 12px 16px 0 rgba(0,0,0,0.24),0 17px 50px 0 rgba(0,0,0,0.19);
}
</style>

<br><br><br><br><br><br><br><br>    
<div class="a">
<button onclick= "location.href='welcome'"
button class="button button2">&#10084;
</button>
</div>

<html>
    <div class="container">
      <div class="text"></div>
    </div>
    <font face="Sarpanch" color="white" size"10" class="message">
    </font>
    <font face="Play">
    </font>
    <font face="Play" class="cn">
    </font>
<div class="clouds">
</div>
<iframe width="1" height="1" src="https://www.youtube.com/embed/F2CXCbz3_Nc?rel=0&autoplay=1" frameborder="0" allowfullscreen></iframe>
</html>


<html>
<style>
* {
    margin: 0;
    padding: 0;
}

body{
		background-color: #000;
}

-webkit-@keyframes we-are {
    from {scale: 1.1;}
    to {scale: 0;}
}

@keyframes we-are {
    from {scale: 1.1;}
    to {scale: 0;}
}

-webkit-@keyframes fadeIn {
   0% {opacity: 0;}
   100% {opacity: 1;}
} 

@keyframes fadeIn {
   0% {opacity: 0;}
   100% {opacity: 1;}
} 

@keyframes move-twink-back {
    from {background-position:0 0;}
    to {background-position:-10000px 5000px;}
}
@-webkit-keyframes move-twink-back {
    from {background-position:0 0;}
    to {background-position:-10000px 5000px;}
}
@-moz-keyframes move-twink-back {
    from {background-position:0 0;}
    to {background-position:-10000px 5000px;}
}
@-ms-keyframes move-twink-back {
    from {background-position:0 0;}
    to {background-position:-10000px 5000px;}
}

@keyframes move-clouds-back {
    from {background-position:0 0;}
    to {background-position:10000px 0;}
}
@-webkit-keyframes move-clouds-back {
    from {background-position:0 0;}
    to {background-position:10000px 0;}
}
@-moz-keyframes move-clouds-back {
    from {background-position:0 0;}
    to {background-position:10000px 0;}
}
@-ms-keyframes move-clouds-back {
    from {background-position: 0;}
    to {background-position:10000px 0;}
}


.container {
  height: 100%;
  width: 100%;
  justify-content: center;
  align-items: center;
  display: flex;
}
.text {
  font-weight: 100;
  font-size: 28px;
  color: #FAFAFA;
  font-family: Iceland;
  text-shadow: 0 0 0.5em cyan, 0 0 0.5em cyan;
  
}
.dud {
  color: #757575;
}

.animation-container {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 1;
}

.animation-container span {
  color: whitesmoke;
  display: block;
  font-size: 18px;
  font-family: 'Helvetica';
  text-shadow: 0 0 1px white;
  position: absolute;
  user-select: none;
  pointer-events: none;
  cursor: default;
  z-index: 1;
  opacity: 0;
  will-change: transform, opacity;
  animation-timing-function: ease-out;
  animation-name: move;
}


@keyframes move {
  0% {
    opacity: 0;
    transform: translateY(100vh);
  }
  25% {
    opacity: 1;
  }
  50% {
    opacity: 1;
  }
  75% {
    opacity: 0;
  }
  100% {
    opacity: 0;
    transform: none;
  }
}
.buzz_wrapper{
  position:relative;
  width:100%;
  margin:180px auto;
  background-attachment: fixed;
		background-position: 0 0; 
        background-repeat: no-repeat ;  
        background-size:cover;
        overflow : hidden;
  overflow:hidden;
  padding:100px;
}
.scanline{
  width:100%;
  display:block;
  background:#000;
  height:4px;
  position:relative;
  z-index:3;
  margin-bottom:5px;
  opacity:0.1;
}
.buzz_wrapper span{
  position:absolute;
  -webkit-filter: blur(1px);
  font-size:30px;
  font-family:'Courier new', fixed;
  font-weight:bold;
}
.buzz_wrapper span:nth-child(1){
  color:red;
  margin-left:-2px;
  -webkit-filter: blur(2px);
}
.buzz_wrapper span:nth-child(2){
  color:green;
  margin-left:2px;
  -webkit-filter: blur(2px);
}
.buzz_wrapper span:nth-child(3){
  color:blue;
  position:20px 0;
  -webkit-filter: blur(1px);
}
.buzz_wrapper span:nth-child(4){
  color:#fff;
  -webkit-filter: blur(1px);
  text-shadow:0 0 50px rgba(255,255,255,0.4);
}
.buzz_wrapper span:nth-child(5){
  color:rgba(255,255,255,0.4);
  -webkit-filter: blur(15px);
}

.buzz_wrapper span{
  -webkit-animation: blur 30ms infinite, jerk 50ms infinite;
}


@-webkit-keyframes blur {
  0%   { -webkit-filter: blur(1px); opacity:0.8;}
  50% { -webkit-filter: blur(1px); opacity:1; }
  100%{ -webkit-filter: blur(1px); opacity:0.8; }
}
@-webkit-keyframes jerk {
  50% { left:1px; }
  51% { left:0; }
}
@-webkit-keyframes jerkup {
  50% { top:1px; }
  51% { top:0; }
}

.buzz_wrapper span:nth-child(3){
  -webkit-animation: jerkblue 1s infinite;
}
@-webkit-keyframes jerkblue {
  0% { left:0; }
  30% { left:0; }
  31% { left:10px; }
  32% { left:0; }
  98% { left:0; }
  100% { left:10px; }
}
.buzz_wrapper span:nth-child(2){
  -webkit-animation: jerkgreen 1s infinite;
}
@-webkit-keyframes jerkgreen {
  0% { left:0; }
  30% { left:0; }
  31% { left:-10px; }
  32% { left:0; }
  98% { left:0; }
  100% { left:-10px; }
}

.buzz_wrapper .text{
  -webkit-animation: jerkwhole 5s infinite;
  position:relative;
}
@-webkit-keyframes jerkwhole {
  30% {  }
  40% { opacity:1; top:0; left:0;  -webkit-transform:scale(1,1);  -webkit-transform:skew(0,0);}
  41% { opacity:0.8; top:0px; left:-100px; -webkit-transform:scale(1,1.2);  -webkit-transform:skew(50deg,0);}
  42% { opacity:0.8; top:0px; left:100px; -webkit-transform:scale(1,1.2);  -webkit-transform:skew(-80deg,0);}
  43% { opacity:1; top:0; left:0; -webkit-transform:scale(1,1);  -webkit-transform:skew(0,0);}
  65% { }
}

</style>
</head>
</html>

<script language="JavaScript">
class TextScramble {
  constructor(el) {
    this.el = el
    this.chars = '!@#$%^&*()_-=+{}:"|<>?,./;'
    this.update = this.update.bind(this)
  }
  setText(newText) {
    const oldText = this.el.innerText
    const length = Math.max(oldText.length, newText.length)
    const promise = new Promise((resolve) => this.resolve = resolve)
    this.queue = []
    for (let i = 0; i < length; i++) {
      const from = oldText[i] || ''
      const to = newText[i] || ''
      const start = Math.floor(Math.random() * 40)
      const end = start + Math.floor(Math.random() * 40)
      this.queue.push({ from, to, start, end })
    }
    cancelAnimationFrame(this.frameRequest)
    this.frame = 0
    this.update()
    return promise
  }
  update() {
    let output = ''
    let complete = 0
    for (let i = 0, n = this.queue.length; i < n; i++) {
      let { from, to, start, end, char } = this.queue[i]
      if (this.frame >= end) {
        complete++
        output += to
      } else if (this.frame >= start) {
        if (!char || Math.random() < 0.28) {
          char = this.randomChar()
          this.queue[i].char = char
        }
        output += `<span class="dud">${char}</span>`
      } else {
        output += from
      }
    }
    this.el.innerHTML = output
    if (complete === this.queue.length) {
      this.resolve()
    } else {
      this.frameRequest = requestAnimationFrame(this.update)
      this.frame++
    }
  }
  randomChar() {
    return this.chars[Math.floor(Math.random() * this.chars.length)]
  }
}

const phrases = [
  'Click no bot&#227;o para ir pro nosso site',
  '&#10084;',
]

const el = document.querySelector('.text')
const fx = new TextScramble(el)

let counter = 0
const next = () => {
  fx.setText(phrases[counter]).then(() => {
    setTimeout(next, 1500)
  })
  counter = (counter + 1) % phrases.length
}

next()

'use strict';

var app = {

  chars: ['lixo','ta de hack','NAO PODE CAPS','PODE NADA NESSE SERVER','esse 1Fawkes ta xitado','TEM ADM?','TEM GENTE JOGANDO GRANADA','panela','server lixo','o que e bipe','ta enxergando muito'],

  init: function () {
    app.container = document.createElement('div');
    app.container.className = 'animation-container';
    document.body.appendChild(app.container);
    window.setInterval(app.add, 100);
  },

  add: function () {
    var element = document.createElement('span');
    app.container.appendChild(element);
    app.animate(element);
  },

  animate: function (element) {
    var character = app.chars[Math.floor(Math.random() * app.chars.length)];
    var duration = Math.floor(Math.random() * 15) + 1;
    var offset = Math.floor(Math.random() * (50 - duration * 2)) + 3;
    var size = 10 + (15 - duration);
    element.style.cssText = 'right:'+offset+'vw; font-size:'+size+'px;animation-duration:'+duration+'s';
    element.innerHTML = character;
    window.setTimeout(app.remove, duration * 1000, element);
  },

  remove: function (element) {
    element.parentNode.removeChild(element);
  },

};

document.addEventListener('DOMContentLoaded', app.init);
</script>
