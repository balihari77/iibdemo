# IIB-xml-to-json

CONTENTS OF THIS FILE
---------------------

 * Introduction
 * Requirements
 * Confifuration
 * Troubleshooting


INTRODUCTION
------------

This repository is a simple IBM Integration Bus Application to convert XML data to JSON data using ESQL and HTTP Nodes.


REQUIREMENTS
------------

This module requires the following software:

1) IBM Integration Toolkit
2) Postman (recommended)


CONFIGURATION
-------------
 
 * This application user three nodes 'HTTP Input Node, Compute Node, HTTP Reply Node' connected in the following way Out-In-Out-In.
 * Properties for HTTP Input Node: -Basic- : path suffix for URL - /test
                                 : -Input Message Parsing- : Message Domain - XMLNSC.
                               
TROUBLESHOOTING
---------------

 * If the Postman does not reach the URL, check the following:

   - Is the 7800 port number being used somewhere else?
   - Try 7801,7802,7803 port numbers.
 
 * Ensure that the method is set to POST.

MAINTAINERS
-----------

Current maintainers:
 * Manoj Kumar B 
   
