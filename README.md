java cECE4016 Assignment 1
In this assignment, you are required to implement a simple Local DNS Server .
Introduction
The Domain Name System (DNS) is the hierarchical and decentralized naming system used to
identify computers reachable through the Internet or other Internet Protocol (IP) networks. The
resource records contained in the DNS associate domain names with other forms of information.
These are most commonly used to map human-friendly domain names to the numerical IP
addresses computers need to locate services and devices using the underlying network
protocols, but have been extended over time to perform many other functions as well. The
Domain Name System has been an essential component of the functionality of the Internet since
1985. (wikipedia)
Iterative query and Recursive query
Detailed grading rule
The local DNS server should have the following function:Listen and accept the DNS queries
Send response to the clients
Maintain a cache(20 points). If the ip address is queried before, it should be stored in the
cache. if the answer for the query is found in cache, Local DNS Server send this answer to
Client as the DNS response
Support the DNS queries of www.baidu.com through recursive or iterative searching (30
points)
Support the DNS queries of www.example.com through recursive or iterative searching (20
points)
Support the DNS queries of www.baidu.com through public DNS server (15 points)
Support the DNS queries of www.example.com through代 写ECE4016、Python
代做程序编程语言 public DNS server (15 points)
Requirements
Print the ip address of all the servers you pass by during the searching
Use a variable flag to indicate whether ask the public server for the IP address. When the
flag is set to be 0 , ask the public server for the IP address. When the flag is set to be 1 do
the recursive or iterative searching
Make sure your program works under ubuntu 20
Show how to execute your code
The programming language should be Python(version 3.9)
Dnspython is not allowed to use in this lab
The server is required to work on port 1234 of 127.0.0.1
Useful tools
There are some useful tools that may help you in your programming. (Dnspython is not allowed
to use in this lab)
socket
dnslibSimple test by yourself
You can use dig to test your local NDS server.
An example test code:
dig www.example.com @127.0.0.1 -p 1234
dig www.baidu.com @127.0.0.1 -p 1234
Note that this test code will be used in the evaluation of this project, make sure your program
works given this test code.
Submission
Due on 23:59, 13 Oct 2024(Late submission within 5 minitues is allowed without
punishment)
Every 24h late delivery will be deducted 10%, and 48h late delivery will be allowed at most.
After 48h, 0 marks will be given for this assignment
Honesty
We take your honesty seriously. If you are caught copying others' code, you will get an
automatic 0 in this project. Please write your own code.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
