# Handout Hackathon Stuttgart
This one-pager explains how to get started with Altemista Cloud. The benefits of Altemista Cloud in this Hackathon are for you:
* A *turn-key platform* for REST services which you may need a "glue" between all the available APIs
* A chance to *win an extra prize* in the Altemista Cloud category, which is sponsored by NTT DATA
* A great opportunity to immediately get going with new technology like Docker and Kubernetes and to *brush up your resume*  
* Access *great engineers* of our on-site support team who are there to help you with your solution

## Installation of Altemista Cloud Toolbelt
### Install Git
In the unlikely event that you have not Git installed, download Git from here and follow installation instructions:
[Git - Downloads](https://git-scm.com/download)
We assume that you will be working in a unix shell, on Windows you can use the Git Bash. 

Install OC
The oc command is the CLI to OpenShift, the PaaS technology behind Altemista Cloud. Just download the binary form the links below and put it in your path.
https://github.com/openshift/origin/releases/download/v3.6.0/openshift-origin-client-tools-v3.6.0-c4dd4cf-windows.zip
https://github.com/openshift/origin/releases/download/v3.6.0/openshift-origin-client-tools-v3.6.0-c4dd4cf-mac.zip
https://github.com/openshift/origin/releases/download/v3.6.0/openshift-origin-client-tools-v3.6.0-c4dd4cf-linux-64bit.tar.gz

You can check the successful installation by running
```
oc login 
```
 
## Links to Starterkits
We assume that you have the tooling for you favourite language already installed.

### Starter Golang
Our favourite language these days is [Golang](http://golang.org) For this we have created a comprehensive REST template with unit tests, integration tests, and persistence (using MongoDB):


### Starter Node
For super fast prototyping as you many prefer it during a Hackathon we have provided a Node.js based REST template which uses Redis for persistence so that no database management is slowing you down:


### Starter Java
And well, we also support legacy applications ;-)
 

## Link to Tutorials
In case you are interested in diving deeper into container orchestration we recommend our internal tutorial which can be accessed from this URL:
[Home - Altemista Tutorials](https://tutorial-tutorial.ballpark.altemista.cloud/)
