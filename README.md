# erntehelfer-suche.de
Dieses Repository ist der Versuch auf möglichst schnelle Art eine Anwendung zu implementieren, die deutschen Landwirten dabei hilft Erntehelfer zu finden. Das Team um die Anwendung möchte diese als Teil des #WirVsVirus Hackathon erstellen.

Das Interface wird auf deutsch sein. Der Code selbst auf Englisch.

# Architecture

![Architecture](https://editor.signavio.com/p/model/2ac514dabcda4befa31ac9e7480f0adc/png?inline&authkey=2c2f769ba13e4ae3b39be8fe131df11a4fdfc59366edae9b1d0daa5c4b4dc)

# Requirements and Specifications

The following standards & technologies should be used:

 * HTML5 & JavaScript that are supported by Chrome 80
 ** Harmony modules (https://v8.dev/features/modules & https://javascript.info/modules-dynamic-imports)
 ** Asynchronous functions and promises
 ** JavaScript class syntax (https://developer.mozilla.org/de/docs/Web/JavaScript/Reference/Klassen)
 ** Visual Studio Code as editor (https://code.visualstudio.com/)
 * WMS, WFS and WFS-T
 ** geoserver (http://geoserver.org/)
 ** openlayers from CDN (https://openlayers.org/)
 * GitHub Pages (https://pages.github.com/) for hosting the static assets of the website
 * Amazon Web Services for server logic
 ** Copy of WFS-T request to Amazon MQ via WebSocket
 *** Topic for job offers called job-offers
 *** Topic for job seekers called job-seekers
 ** Amazon Lambda
 ** Amazon SNS


The following thing should not be used:

 * Continuous integration
 * npm, webpack or other bundlers 
 * JavaScript framework, standards only

