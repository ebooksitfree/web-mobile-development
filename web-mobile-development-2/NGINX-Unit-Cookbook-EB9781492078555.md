![Cover image for NGINX Unit Cookbook](https://imgdetail.ebookreading.net/cover/cover/20200920/EB9781492078555.jpg)

[NGINX Unit Cookbook](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_1.html "NGINX Unit Cookbook")
====================================================================================================================

Author : [Derek DeJonghe](https://ebookreading.net/search/author/Derek+DeJonghe)

Release Date : 2020/09/01

Book Description
-----------------


    
    Alongside its popular web server, NGINX provides a dynamic application server that supports a RESTful JSON API. The open source NGINX Unit server deploys configuration changes without service disruptions and runs apps built with multiple languages and frameworks. This updated cookbook shows developers, DevOps personnel, network admins, and cloud infrastructure pros how to quickly get started with NGINX Unit.
Hands-on recipes demonstrate Unit’s new approach and show you how to deploy and configure this server for different applications. You’ll learn how to run applications written in different languages on the same server, how to use NGINX Unit as the foundation for your web application development environment, and how Unit’s RESTful API simplifies configuration.
Learn how Unit differs from other middleware application serversInstall Unit using source code, Red Hat and Debian systems, or third-party repositoriesConfigure Unit using application, router, and listener objectsStart and stop the Unit server and the applications it runsManage user permissions, Linux namespace isolation, and API securityRun WordPress, Django, and other web applications with UnitServe applications with an NGINX proxy or load balancer
  

Table of Contents
-----------------

1. [NGINX](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_2.html#idm45681535255064)
1. [Preface](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_5.html#_preface)
    1. [Conventions Used in This Book](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_5.html#_conventions_used_i)
    1. [Using Code Examples](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_5.html#_using_code_example)
    1. [O’Reilly Online Learning](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_5.html#_safari_books_onlin)
    1. [How to Contact Us](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_5.html#_how_to_contact_us)
    1. [Acknowledgments](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_5.html#_acknowledgments)
1. [1. Unit Introduction and Features](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_6.html#unit_introduction_a)
    1. [1.1. Application Landscape and Unit Project History](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_6.html#idm45681534228840)
    1. [1.2. Dynamic Web Application Server](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_6.html#idm45681535209448)
    1. [1.3. Polyglotism](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_6.html#idm45681535202936)
    1. [1.4. API-Driven Configuration and Server Management](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_6.html#idm45681535196520)
    1. [1.5. Conclusion](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_6.html#idm45681535190184)
1. [2. Installation](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_7.html#Installation)
    1. [2.1. Red Hat–Based Systems (.rpm)](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_7.html#idm45681535173160)
    1. [2.2. Debian-Based Systems (.deb)](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_7.html#idm45681530947208)
    1. [2.3. Go and NPM](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_7.html#idm45681534518904)
    1. [2.4. Third-Party Repositories](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_7.html#idm45681534578952)
    1. [2.5. Installing from Source](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_7.html#idm45681529808872)
1. [3. Configuration](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_8.html#Configuration)
    1. [3.1. Application Object](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_8.html#idm45681529559800)
    1. [3.2. Listener Object](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_8.html#idm45681529435304)
    1. [3.3. Route Object](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_8.html#idm45681529382920)
    1. [3.4. Proxying](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_8.html#idm45681529103640)
    1. [3.5. Static Files](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_8.html#idm45681529044456)
    1. [3.6. Upstreams/Load Balancing](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_8.html#idm45681528941832)
    1. [3.7. Targets](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_8.html#idm45681528859128)
1. [4. Usage and Operations](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_9.html#usage_and_operation)
    1. [4.1. Startup and Shutdown](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_9.html#idm45681528722904)
    1. [4.2. Applying Configuration](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_9.html#applying_configurat)
    1. [4.3. Limits](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_9.html#idm45681528237416)
1. [5. Security](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_10.html#security)
    1. [5.1. Unix User Permissions](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_10.html#idm45681528117448)
    1. [5.2. Linux Namespace Isolation](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_10.html#idm45681528027032)
    1. [5.3. API Security Through Encryption](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_10.html#idm45681528026728)
1. [6. Application Integration](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_11.html#application_integra)
    1. [6.1. WordPress](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_11.html#idm45681527751336)
    1. [6.2. Django](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_11.html#idm45681527496664)
    1. [6.3. Flask](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_11.html#idm45681527272984)
    1. [6.4. Express](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_11.html#idm45681527012872)
    1. [6.5. Ruby](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_11.html#idm45681525658392)
1. [7. Ecosystem Integration](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_12.html#ecosystem_integrati)
    1. [7.1. Reverse Proxying to Unit Applications Through NGINX](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_12.html#idm45681525524104)
    1. [7.2. Securely Serving the NGINX Unit Control API](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_12.html#idm45681525429912)
    1. [7.3. Containerized Environment](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_12.html#idm45681525412904)
    1. [7.4. Deployments](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_12.html#idm45681525058344)
    1. [Conclusion](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_12.html#idm45681524643944)
1. [Index](https://ebookreading.net/view/book/NGINX+Unit+Cookbook-EB9781492078555_13.html#idm45681524610696)
