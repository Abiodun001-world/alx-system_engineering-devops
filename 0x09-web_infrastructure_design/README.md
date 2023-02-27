0x09. Web infrastructure design
# Devops SysAdmin Web Infrastructure
<br>
Concepts 
[DNS] (https://intranet.alxswe.com/concepts/12)
[Monitoring] (https://intranet.alxswe.com/concepts/13)
[Web Server] (https://intranet.alxswe.com/concepts/17)
[Network basics] (https://intranet.alxswe.com/concepts/33)
[Load balancer] (https://intranet.alxswe.com/concepts/46)
[Server] (https://intranet.alxswe.com/concepts/67)
[What Is a Database] (https://www.oracle.com/ke/database/what-is-database/)
[What's the difference between a web server and app server] (https://www.infoworld.com/article/2077354/app-server-web-server-what-s-the-difference.html)
[DNS record types] (https://www.site24x7.com/learn/dns-record-types.html)
[Single point of failure] (https://avinetworks.com/glossary/single-point-of-failure/)
[How to avoid downtime when deploying a new code] (https://softwareengineering.stackexchange.com/questions/35063/how-do-you-update-your-production-codebase-database-schema-without-causing-downt#answers-header)
[High availability cluster (active-active active/passive)] (https://docs.oracle.com/cd/E17904_01/core.1111/e10106/intro.htm#ASHIA712)
[What's HTTPS] (https://www.instantssl.com/http-vs-https)
[what is a firewall] (https://www.webopedia.com/definitions/firewall/)
<br>
## Tasks
# 0. Simple web stack
## Description
<br>
 A lot of websites are powered by simple web infrastructure, a lot of time it is composed of a single server with a LAMP stack.

On a whiteboard, design a one server web infrastructure that hosts the website that is reachable via www.foobar.com. Start your explanation by having a user wanting to access your website.

Requirements:

You must use:
1 server
1 web server (Nginx)
1 application server
1 application files (your code base)
1 database (MySQL)
1 domain name foobar.com configured with a www record that points to your server IP 8.8.8.8
You must be able to explain some specifics about this infrastructure:
What is a server
What is the role of the domain name
What type of DNS record www is in www.foobar.com
What is the role of the web server
What is the role of the application server
What is the role of the database
What is the server using to communicate with the computer of the user requesting the website
You must be able to explain what the issues are with this infrastructure:
SPOF
Downtime when maintenance needed (like deploying new code web server needs to be restarted)
Cannot scale if too much incoming traffic
<br>
.What is a Server?
A server is a computer hardware or software that provides services to other computers, which are usually referred to as clients.
.What is the role of the domain name?
Domain names serve to identify Internet resources, such as computers, networks, and services, with a text-based label that is easier to memorize than the numerical addresses used in the Internet protocols. A domain name may represent entire collections of such resources or individual instances.
.What is the role of the web server?
The primary role of a web server is to store, process, and deliver requested information or webpages to end users. It uses: Physical Storage: All website data is stored on a physical web server to ensure its safety.
.what is the role of the application server?
The function of the application server is to act as host (or container) for the user's business logic while facilitating access to and performance of the business application.
.What is the role of the database?
The use of a computer database is typically involved in efficient data management. A shared, integrated computer structure, a database stores the following: End-user data i.e. raw data relevant to the end user. Metadata—the data about data, through which end-user data is integrated and managed..


