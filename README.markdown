## JS Console

A JavaScript (and [CoffeeScript](http://coffeescript.com)) web console, useful 
for quick experimentation, debugging, presentations (for live coding) and workshops.

This is a fork of [jsconsole.com](http://jsconsole.com), optimized for indipendent hosting/experimentation.

## Features

- Remote device debugging using "listen" command ([more info](http://jsconsole.com/remote-debugging.html))
- Resizable font (yep, biggest issue with Firebug in workshops)
- Autocomplete in WebKit desktop browsers
- shift + up/down for bigger console
- Save history (based on session)
- Add support for loading in a DOM (YQL - I thank you again)
- Permalink to individual executions

## Hosting jsconsole yourself

The server-side code is used mainly only for the remote debugging feature.

This requires that you install [node.js](http://nodejs.org). Once installed, 
download this project (or clone it using git) 
and inside the new `jsconsole` directory run:

    npm install
    
This will install the dependancies (in particular 1.8.x version of connect.js).

Once installed, run (on port 80):

    node server.js
    
Or to run on a specific port (like 8080):

    node server.js 8080
    
Then check your own ip address of the machine it's running on (using `ipconfig` 
for windows or `ifconfig` for mac and linux). Then on the mobile phone, just 
visit that IP address and port you're running jsconsole on:

![jsconsole running locally](http://i.imgur.com/hyRF5.png)

## License, authors and contributors

You can read the MIT-LICENSE file for licensing information.

This fork is maintained by [Michele Bini (rev22)](http://rev22.github.io)

JS Console was originally built by [Remy Sharp (@rem)](http://twitter.com/remy)

In addition the following contributors helped to create this fork of jsconsole (ordered by first contribution, according to the [Git repository log](https://github.com/rev22/jsconsole/commits/gh-pages)):
- [Dominic Mitchell](https://github.com/happygiraffe)
- [Brian Arnold](https://github.com/brianarn)
- [Lim Chee Aun](https://github.com/cheeaun)
- [Ryan Grove](https://github.com/rgrove)
- Grigory V
- [Tyler Breisacher](https://github.com/MatrixFrog)
- [Mathias Bynens](https://github.com/mathiasbynens)
- [Gilbert (mindeavor)](https://github.com/mindeavor)
- [Martin Sander](https://github.com/marvinthepa)
- [tribalvibes](https://github.com/tribalvibes)
- [cgack](https://github.com/cgack)
- [Leiron](https://github.com/Leiron)
- [Gheric Speiginer](https://github.com/speigg)
- Shannon

The list is incomplete and may have erroneous information, so it will benefit from your help, especially if you are one of the contributors!

See also: https://github.com/rev22/jsconsole/graphs/contributors
