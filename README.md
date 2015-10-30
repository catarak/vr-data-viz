#UN Immersive Data Visualization Examples

This project was created as a few examples for a workshop in immersive data visualization at the UN on October 30th, 2015.These examples hope to explore a series of projects that combine THREE.js, D3, and Virtual Reality. 

This was inspired from a [tutorial I found on Storybench](http://www.storybench.org/how-to-make-a-simple-virtual-reality-data-visualization/). [Source code here](https://github.com/rogerkenny/3D-chart-tutorial). 

I adapted the tutorial to use the [webvr-boilerplate](https://github.com/borismus/webvr-boilerplate).  

I also added a [Chrome experiments style reticule](https://vr.chromeexperiments.com/), adapted from a [small reticle THREE.js library](https://github.com/GQPBJ/Reticulum) I found on github.

#Examples

`basic.html`: a basic THREE.js sketch with no VR or D3
`basic-with-vr.html`: a simple THREE.js sketch configured for use with VR
`bar-chart-vr.html`: a interactive bar chart example, combining THREE.js, D3, and VR
`map-vr.html`: an interactive map example, combining THREE.js, D3, and VR

#Installation and Setup

1. [Clone this repository](https://help.github.com/articles/cloning-a-repository/), or if you don't have a github account, download a zip of this repository. 

2. Install node and npm by [downloading the installer on Nodejs.org](https://help.github.com/articles/cloning-a-repository/).

3. Install localtunnel by running `npm install -g localtunnel`.

4. Install http-server by running `npm install -g http-server`.

5. Open a terminal and `cd` to the project directory.

6. In the project directory, run `http-server`.

7. In a new terminal window, run `lt --port 8080`.

8. On your phone, navigate to the url that localtunnel spits out. The url is a little annoying to type, so I recommend using a [url shortener](http://shoutkey.com/). If the name of your html file is not index.html, you will need to navigate to the url/name-of-html-page.html.

