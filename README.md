Nerf Turret
===========

Remote control a nerf turret

Hardware
--------
* Spark core - [get here](https://store.spark.io/?product=spark-core)
* Ada fruit motor shield V2 - [get here](http://www.adafruit.com/product/1438)
* Proto board
* Jumper wires
* Driving chassis - [I got one like this](http://www.dfrobot.com/index.php?route=product/* product&product_id=65&search=Turtle+2WD+chassis+&description=true)
* Battery box

Installation
------------
* Clone code: git clone https://github.com/geekfamily/turret.git
* Create a configuration file using the following format...
<code>

{
    "serviceUrl": "https://api.spark.io/v1",
    "accessToken": "...token here",
    "deviceId": "...deviceId here",
    "requestTimeout": 30000,
    "username": "...username here",
    "password": "...password here"
}

</code>

* npm install
* bower install
* grunt build
* grunt serve

