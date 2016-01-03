Docker Control Panel
====================

This is a web interface(control panel) for [Docker](http://docker.io) containers, 
implemented using [Angular.JS](http://angularjs.org) and [Twitter Bootstrap](http://getbootstrap.com/).

Before using interface, you should launch docker with additional arguments, eg:

```bash
 $ docker -d -H=0.0.0.0:4243 -api-enable-cors
```

Compiling and running using Node.JS
===================================

```bash
 $ npm install
 $ bower install
 $ grunt serve
```

[Demo](http://13W.github.io/docker-cp/)
=======================================

or with defining docker host address
http://13W.github.io/docker-cp/#!/set/host/http://localhost:4243

----
