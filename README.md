# Ajax-jQuery
Keep your notes (client-server) WebApp

<h2>Setup Instructions</h2>
<h3>Download</h3>
<p>Paste the following into your terminal - <u><i><b>git clone git@github.com/Theokalo/Ajax-jQuery.git</u></i></b></p>
<h3>Server</h3>
<ul>
<li>Now <u><i><b>cd</u></i></b> into <u><i><b>Ajax-jQuery/server</u></i></b> and run <u><i><b>npm install</u></i></b></li>
<li>Start your mongo daemon <u><i><b>mongod</u></i></b> in a separate terminal tab</li>
<li>Install <u><i><b>nodemon</u></i></b> globally (if you don't already have it installed) with <u><i><b>npm i -g nodemon</u></i></b></li>
<li>Run your server in its own terminal tab with <u><i><b>nodemon</u></i></b> or <u><i><b>node app</u></i></b></li>
</ul>
<h3>Client</h3>
<ul>
<li>Navigate to <u><i><b>Ajax-jQuery/client</u></i></b> in a separate terminal tab and run <u><i><b>npm install</u></i></b></li>
<li>While working in development you can run <u><i><b>gulp watch</u></i></b> from a separate tab to listen for changes and tanspile your client-side JavaScript each time you update the <u><i><b>/client/src/ajax.js</u></i></b> file</li>
<li>Run your client server from <u><i><b>/client</u></i></b> with <u><i><b>python -m SimpleHTTPServer</u></i></b> (On windows use this command "<u><i><b>py -3.6 -m http.server</u></i></b>")</li>
<li>Navigate to <u><i><b>localhost:8000</u></i></b> in your browser</li>
</ul>
