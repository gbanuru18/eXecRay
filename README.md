# ExecRay
<p align="center"><img src="/images/HOMESCREEN.png" width=600></p>

This program enables a user to input a file into our webapp. We execute the file in an AWS virtual machine instance and generate a log file of the running processes in the executable. The log file is generated on the screen to help experienced developers make an informed decision.

Created and maintained by Gautam and Sahil.

## Why Did We Make This Developer Tool?

Information security is vital for corporations and government partners. Using open source file distributions can pose a potential risk for employers. Keeping our focus on security enables a safer internet for everyone.

## What Services Do We Use?

* Amazon EC2 for creating Virtual Machines
* Flask for Website Deployment
* psutils Python library for dynamic analysis of running executable processes

## How To Run Our Code?

1. Git clone this repository.
1. Input AWS credentials
1. Run main.py

## What Metrics Do You Receive?
* Some metrics accounted for include external process creation, hardware resources consumed, network activity (opened ports and REST API verbs), database connections, and system files and registry modification.
