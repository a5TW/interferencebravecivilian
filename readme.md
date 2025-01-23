body{
    margin: 0 auto;
    background: #000;
    font-family: Georgia, Palatino, serif;
    color: #EEE;
    line-height: 1;
    max-width: 960px;
    padding: 30px;
}
h1, h2, h3, h4 {
    font-weight: 400;
}
h1, h2, h3, h4, h5, p {
    margin-bottom: 24px;
    padding: 0;
}
h1 {
    font-size: 48px;
}
h2 {
    font-size: 36px;
    margin: 24px 0 6px;
}
h3 {
    font-size: 24px;
}
h4 {
    font-size: 21px;
}
h5 {
    font-size: 18px;
}
a {
    color: #61BFC1;
    margin: 0;
    padding: 0;
    text-decoration: none;
    vertical-align: baseline;
}
a:hover {
    text-decoration: underline;
}
a:visited {
    color: #466B6C;
}
ul, ol {
    padding: 0;
    margin: 0;
}
li {
    line-height: 24px;
}
li ul, li ul {
    margin-left: 24px;
}
p, ul, ol {
    font-size: 16px;
    line-height: 24px;
    max-width: 540px;
}
pre {
    padding: 0px 24px;
    max-width: 800px;
    white-space: pre-wrap;
}
code {
    font-family: Consolas, Monaco, Andale Mono, monospace;
    line-height: 1.5;
    font-size: 13px;
}
aside {
    display: block;
    float: right;
    width: 390px;
}
blockquote {
    border-left:.5em solid #eee;
    padding: 0 2em;
    margin-left:0;
    max-width: 476px;
}
blockquote  cite {
    font-size:14px;
    line-height:20px;
    color:#bfbfbf;
}
blockquote cite:before {
    content: '\2014 \00A0';
}

blockquote p {  
    color: #666;
    max-width: 460px;
}
hr {
    width: 540px;
    text-align: left;
    margin: 0 auto 0 0;
    color: #999;
}

/* Code below this line is copyright Twitter Inc. */

button,
input,
select,
textarea {
  font-size: 100%;
  margin: 0;
  vertical-align: baseline;
  *vertical-align: middle;
}
button, input {
  line-height: normal;
  *overflow: visible;
}
button::-moz-focus-inner, input::-moz-focus-inner {
  border: 0;
  padding: 0;
}
button,
input[type="button"],
input[type="reset"],
input[type="submit"] {
  cursor: pointer;
  -webkit-appearance: button;
}
input[type=checkbox], input[type=radio] {
  cursor: pointer;
}
/* override default chrome & firefox settings */
input:not([type="image"]), textarea {
  -webkit-box-sizing: content-box;
  -moz-box-sizing: content-box;
  box-sizing: content-box;
}

input[type="search"] {
  -webkit-appearance: textfield;
  -webkit-box-sizing: content-box;
  -moz-box-sizing: content-box;
  box-sizing: content-box;
}
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}
label,
input,
select,
textarea {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  font-weight: normal;
  line-height: normal;
  margin-bottom: 18px;
}
input[type=checkbox], input[type=radio] {
  cursor: pointer;
  margin-bottom: 0;
}
input[type=text],
input[type=password],
textarea,
select {
  display: inline-block;
  width: 210px;
  padding: 4px;
  font-size: 13px;
  font-weight: normal;
  line-height: 18px;
  height: 18px;
  color: #808080;
  border: 1px solid #ccc;
  -webkit-border-radius: 3px;
  -moz-border-radius: 3px;
  border-radius: 3px;
}
select, input[type=file] {
  height: 27px;
  line-height: 27px;
}
textarea {
  height: auto;
}

/* grey out placeholders */
:-moz-placeholder {
  color: #bfbfbf;
}
::-webkit-input-placeholder {
  color: #bfbfbf;
}

input[type=text],
input[type=password],
select,
textarea {
  -webkit-transition: border linear 0.2s, box-shadow linear 0.2s;
  -moz-transition: border linear 0.2s, box-shadow linear 0.2s;
  transition: border linear 0.2s, box-shadow linear 0.2s;
  -webkit-box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.1);
  -moz-box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.1);
}
input[type=text]:focus, input[type=password]:focus, textarea:focus {
  outline: none;
  border-color: rgba(82, 168, 236, 0.8);
  -webkit-box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.1), 0 0 8px rgba(82, 168, 236, 0.6);
  -moz-box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.1), 0 0 8px rgba(82, 168, 236, 0.6);
  box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.1), 0 0 8px rgba(82, 168, 236, 0.6);
}

/* buttons */
button {
  display: inline-block;
  padding: 4px 14px;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  line-height: 18px;
  -webkit-border-radius: 4px;
  -moz-border-radius: 4px;
  border-radius: 4px;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.2), 0 1px 2px rgba(0, 0, 0, 0.05);
  -moz-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.2), 0 1px 2px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.2), 0 1px 2px rgba(0, 0, 0, 0.05);
  background-color: #0064cd;
  background-repeat: repeat-x;
  background-image: -khtml-gradient(linear, left top, left bottom, from(#049cdb), to(#0064cd));
  background-image: -moz-linear-gradient(top, #049cdb, #0064cd);
  background-image: -ms-linear-gradient(top, #049cdb, #0064cd);
  background-image: -webkit-gradient(linear, left top, left bottom, color-stop(0%, #049cdb), color-stop(100%, #0064cd));
  background-image: -webkit-linear-gradient(top, #049cdb, #0064cd);
  background-image: -o-linear-gradient(top, #049cdb, #0064cd);
  background-image: linear-gradient(top, #049cdb, #0064cd);
  color: #fff;
  text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25);
  border: 1px solid #004b9a;
  border-bottom-color: #003f81;
  -webkit-transition: 0.1s linear all;
  -moz-transition: 0.1s linear all;
  transition: 0.1s linear all;
  border-color: #0064cd #0064cd #003f81;
  border-color: rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.25);
}
button:hover {
  color: #fff;
  background-position: 0 -15px;
  text-decoration: none;
}
button:active {
  -webkit-box-shadow: inset 0 3px 7px rgba(0, 0, 0, 0.15), 0 1px 2px rgba(0, 0, 0, 0.05);
  -moz-box-shadow: inset 0 3px 7px rgba(0, 0, 0, 0.15), 0 1px 2px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 3px 7px rgba(0, 0, 0, 0.15), 0 1px 2px rgba(0, 0, 0, 0.05);
}
button::-moz-focus-inner {
  padding: 0;
  border: 0;
}

<!-- don't mess it up -->

<br />
<div align="center">
  <a href="https://github.com/a5tw/interferencebravecivilian">
    <img src="hyperlink-icon.png" alt="Logo" width="96" height="96">
  </a>

  <h3 align="center">Resources</h3>

  <p align="center">
    A list of links for you to use when you don't have an address bar.
    <br />
    <a href="https://pdsb.online/redirector">Redirector</a>
    ·
    <a href="https://github.com/a5tw/interferencebravecivilian/issues/new">Suggestions</a>
  </p>
</div>

## THE MOST IMPORTANT LINK
The [redirector](https://pdsb.online/redirector) lets you visit any site by just typing in the url. If you want to visit a site not listed, definitely use this.

## Glossary
🐐 = The greatest

⭐ = Really good

## Table of Contents
1. [Run by @legendaryfishwastaken](#run-by-legendaryfishwastaken)
2. [Google Services](#google-services)
3. [Games](#games)
4. [Quiz Games](#quiz-games)
5. [Piracy](#piracy)
6. [Extras](#extras)

## Run by [@legendaryfishwastaken](https://github.com/legendaryfishwastaken)
- 🐐[Free Movies - lfdev.site](https://nova.lfdev.site/), [2](https://movies.lfdev.site/)
- ⭐[Free Books - pdsb.online](https://pdsb.online/books/)
- [Unblocked Games - lfdev.site](https://games.lfdev.site/)
- [Site Unblocker - pdsb.online](https://pdsb.online/proxy)
- [Minecraft 1.5 (Eaglercraft) - pdsb.online](https://pdsb.online/minecraft)
- [Free TV Channels - pdsb.online](https://pdsb.online/channels)
- [Celeste in Your Browser - pdsb.online](https://pdsb.online/celeste)

## Google Services
- 🐐[Google](https://www.google.com/)
- ⭐[YouTube](https://www.youtube.com/)
- ⭐[Gmail](https://mail.google.com/)
- ⭐[Google Drive](https://drive.google.com/)
- ⭐[Google Classroom](https://classroom.google.com/)
- [Google Docs](https://docs.google.com/)
- [Google Sheets](https://sheets.google.com/)
- [Google Slides](https://slides.google.com/)
- [Google Maps](https://www.google.com/maps/)
- [Google Photos](https://photos.google.com/)
- [Google Play](https://play.google.com/)

## Games
- 🐐[Itch.io](https://itch.io/)
- ⭐[Kongregate](https://www.kongregate.com/)
- ⭐[Newgrounds](https://www.newgrounds.com/)
- ⭐[Armor Games](https://www.armorgames.com/)
- ⭐[TETR.IO](https://tetr.io/)
- ⭐[Cookie Clicker](https://orteil.dashnet.org/cookieclicker/), [2](https://orteil.dashnet.org/experiments/cookie/)
- [Miniclip](https://www.miniclip.com/)
- [Pogo](https://www.pogo.com/)
- [Addicting Games](https://www.addictinggames.com/)
- [Crazy Games](https://www.crazygames.com/)
- [Y8](https://www.y8.com/)
- [Nitrome](https://www.nitrome.com/)
- [GamePix](https://www.gamepix.com/)
- [Pokémon Showdown](https://pokemonshowdown.com/)

## Quiz Games
- 🐐[Quizit (cheats)](https://quizit.online/)
- ⭐[Kahoot](https://kahoot.it/)
- ⭐[Blooket](https://play.blooket.com/)
- ⭐[Gimkit](https://gimkit.com/join)

## Piracy
- 🐐[FMHY](https://fmhy.net/)

you shouldn't need anything else lmao

## Extras
- 🐐[Webview Browser](https://science-homework.mrlewburger.com/)
- ⭐[ext-remover](https://ext-remover.net/)
- [~~Iframe embedder (broken)~~](https://pdsb.online/iframe)
- [Gmail hacker](https://pdsb.online/)
