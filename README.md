# What is FAME ?

FAME is a recursive acronym meaning “FAME Automates Malware Evaluation”.

It is meant to facilitate analysis of malicious files, leveraging as much knowledge as possible in order to speed up and automate end-to-end analysis.

Best case scenario: the analyst drops a sample, waits for a few minutes, and FAME is able to determine the malware family and extract its configuration and IOCs.

FAME should be seen as a framework that will empower your malware analysis development efforts.

# Technical Specs

FAME is a Python application that relies on the following technologies:

* flask for the web framework
* celery for background tasks
* MongoDB (and pymongo) for the database


