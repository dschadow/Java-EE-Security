JEE Security
============
This repository contains several Java EE web applications covering different security topics. Have a look at the [slides](https://blog.dominikschadow.de/events) from various events covering the applications in this repository. The **[Java Web Security Workshop](https://blog.dominikschadow.de/workshop)** talks about some of these applications in much greater detail.

#Web Applications in Detail
Using [Mozilla Firefox](https://www.mozilla.org) as browser is strongly recommended. 

##FerrisWheelManager
Ferris Wheel Manager is a JEE 7 demo application containing security vulnerabilities like **SQL Injection** and **Cross-Site Scripting (XSS)**. A datasource named **jdbc/fwm** is required, which must contain the tables/ data provided by SQL scripts in the [Resources](https://github.com/dschadow/JavaSecurity/tree/master/Resources/FerrisWheelManager) project. 
Valid usernames/passwords are **Marvin/wheel** (role **Manager**), **Zaphod/ferris** (role **User**).
This web application was tested with [Java Enterprise Edition 7](http://www.oracle.com/technetwork/java/javaee),  [GlassFish 4](https://glassfish.java.net) and [MySQL 5.6](http://dev.mysql.com).

##Meta
[![Build Status](https://travis-ci.org/dschadow/JEESecurity.svg)](https://travis-ci.org/dschadow/JEESecurity)