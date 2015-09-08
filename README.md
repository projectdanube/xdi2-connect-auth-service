<a href="http://projectdanube.org/" target="_blank"><img src="http://projectdanube.github.com/xdi2/images/projectdanube_logo.png" align="right"></a>
<img src="http://projectdanube.github.com/xdi2/images/logo64.png"><br>

This is a "Connect Auth Service" component for the XDI Browser binding.

### XDI Connect

This is part of a set of projects related to XDI Connect:
* [xdi2-connect-core](http://github.com/projectdanube/xdi2-connect-core)
* [xdi2-connect-service](http://github.com/projectdanube/xdi2-connect-service)
* [xdi2-connect-auth-service](http://github.com/projectdanube/xdi2-connect-auth-service)
* [xdi2-connect-acmenews](http://github.com/projectdanube/xdi2-connect-acmenews)
* [xdi2-connect-acmepizza](http://github.com/projectdanube/xdi2-connect-acmepizza)

### Information


### How to build

First, you need to build the main [XDI2](http://github.com/projectdanube/xdi2) and the 
[xdi2-connect-core](http://github.com/projectdanube/xdi2-connect-core) projects.

After that, just run

    mvn clean install jetty:run

Then the Connect Auth Service is available at

	http://localhost:9202/

### Community

Website: https://xdi2.org/

Google Group: http://groups.google.com/group/xdi2

Weekly Call: [Thursdays at 4pm US Eastern Time](https://github.com/projectdanube/xdi2/wiki/XDI2-Weekly-Call)

IRC: [irc://irc.freenode.net:6667/xdi](http://webchat.freenode.net?randomnick=1&channels=%23xdi)

