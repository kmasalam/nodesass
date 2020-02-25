# nodesass
Use Node js as sass compiler

<h2>Check Node version</h2>
$ nodejs -v

<h2>Initialize Node</h2>
$ npm init

<h2>initiate a new Node application</h2>

$ npm i node-sass

<h2>Install live server</h2>

$ npm install -g live-server


<h2>Add following line in package.json file to redirect your css folder and file</h2>

"scss": "node-sass --watch assets/scss/style.scss  assets/css/style.css"
