---
layout: post
title: "OpenXPKI Technical Workshop - Online"
---

Get some real world experience with OpenXPKI - in this 90 minutes "Hands On" session you will learn how to modify OpenXPKI to setup automated enrollments to provision servers in your datacenter based on rulesets.

    When:  Tuesday, November 3th 14:00 CET.
    Where: Online    

The workshop will be held online, you should have some experience in setting up OpenXPKI already and be able to use SSH and a terminal to run common shell commands and edit files.

Reserve your seat at openxpki@whiterabbitsecurity.com - limited capacity!

*Update:* Agenda Details

The shared screen session will start on a prepared CentOS with an empty MariaDB, a basic configuration template, and existing Root and CA certificates. From there, we will walk through the following tasks:

* Setup the credential Connector and configure the database
* Create the "Server CA" realm
* Configure a TLS profile with RSA keys
* Create a simple enrollment configuration with manual approval
* Create a second endpoint with shared-secret-based auto-approval and regex checking
* Create a "Device CA" realm with ECC hierarchy
* Configure an EST endpoint with "on-behalf" signer from the "Server CA"
* Create an auto-enrollment with "on-behalf" for VoIP telephone using the "Eligibility" Connector and a simulated CMDB
* Proof-of-Posession (PoP) renewal
