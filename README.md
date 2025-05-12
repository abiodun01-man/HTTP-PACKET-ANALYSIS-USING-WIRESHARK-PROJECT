This repository contains a collection of projects for understanding HTTP Packet Analysis using Wireshark.

PROJECTS:

1: How to CAPTURE NETWORK TRAFFIC : 

i: I open a Wireshark and start a new capture session.

ii: Choose the appropriate network interface for capturing, begin capturing traffic by clicking the ‘start’ button on the WI-FI

2: ANALYZE HTTP PACKETS:  

i: Locate the HTTP packets by using the filter ‘http’ in the Wireshark filter bar.

ii: Identify the packets related to the login process. Look for the POST
request to the login endpoint. (http://testphp.vulnweb.com/login.php)

3: EXTRACT INFORMATION (USERNAME & PASSWORD)Enter
the username and password and go to the Wireshark and you will find the
list of information. Select userinfo. php and it will show all the detailed
information with credentials:

i: Enter user name and password and select Post/userinfo. php and it will give you detailed information.

ii: Examine the HTTP POST request payload for any parameters containing
logininformation. The username and password may be encoded or
encrypted.
