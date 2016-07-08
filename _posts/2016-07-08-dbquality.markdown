---
title: "dbquality"
layout: post
date: 08-02-2016 13:10
tag: 
- dbquality 
- java
image: #/assets/images/jekyll-logo-light-solid.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "This is a program which parses XMLs, creates and executes SQLs against a database (Teradata or MySQL) and validates the results."
jemoji: '<img class="emoji" title=":ramen:" alt=":ramen:" src="https://assets.github.com/images/icons/emoji/unicode/1f35c.png" height="20" width="20" align="absmiddle">'
author: gkolokotronis
externalLink: false
---

dbquality is a utility which parses XMLs, creates and executes SQLs against a database (Teradata or MySQL) and validates the results. The XMLs contain all the information for creating the SQLs and validating the results. It is also licensed under GPLv3.

Feel free to [browse the code](https://github.com/gkolokotronis/dbquality) and read [how to build, configure and execute the program](https://github.com/gkolokotronis/dbquality/wiki).

---

Tools/Libraries used for creating dbquality:

- Eclipse Java EE IDE - Mars.2 Release (4.5.2)
- Smartgit 7.1
- Java - openJDK version 1.7.0_95
- Apache Maven 3.0.5
- commons-digester3, commons-dbutils, commons-lang3, maven-assembly-plugin, log4j-api, log4j-core, terajdbc4, mysql-connector-java
