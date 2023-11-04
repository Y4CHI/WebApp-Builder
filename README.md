# WebApp-Builder
Webapp builder is programmed with electron to convert from a web page to a desktop application quickly.

#Dependencies
<p>For the code to work we will have to install nodeJS, the installation is as follows.</p>
<code>curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash </code><br>
<code>nvm install --lts </code><br>
<code>nvm use 16.20.2</code>

<p>We will install electron, and standard to check code errors.</p>
<code>npm install --save-dev electron</code><br>
<code>npm install standard -D</code>

#Initialization<br>
<code>npm run dev</code>

<p>By default it is with the YouTube page, if you want it to load from another page, you would have to modify the main.js file, exactly 
  in <code>win.loadURL('https://www.youtube.com/')</code> .</p>
