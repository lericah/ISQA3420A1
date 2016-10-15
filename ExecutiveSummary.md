#Executive Summary
##Main Concepts
Open Source software is the future of Software development. It is becoming more and more self-evident that the Software industry is moving away from licensing models and moving towards a service based model for income. This new development has reduced the importance of closed source software and highlighted the benefits of community developed software. For this reason it is important to be able to fully utilize the OSS packages available to developers.
##Project Purpose
This Project focuses on parsing packages of software and identifying the relevant OSS licenses for each component. In addition to this it is important to identify known vulnerabilities in the system. Vulnerabilities are often caught quickly and noted in the Issues section of a repository. This program will use the license files included with each component as well as the NIST reported information to identify relevant OSS licenses and security vulnerabilities in the packages submitted to the system. 
This information will then be stored in a database so it can be freely queried by developers and managers within the company.
##Project Components
This Project is composed of several components which each have their own associated process. The results of the processes will ultimately result in output that the devewlopers and managers will utilize

**Package parser** - takes package input from the Developer and seperates the package(s) into individual components of software

**NIST database system** - National Institute of Standards and Technology database of known security vulnerabilities in software

**OSS license scanner** - process the scans compenents it receives and identifies the OSS license associated with the component as well as vital details

