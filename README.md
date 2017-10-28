# Project 8 - Pentesting Live Targets

Time spent: 8 hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: SQL Injection
    With the SQL fragment   ' OR SLEEP(3)=0--'  I was to put the server to sleep for 3 number of seconds.
    https://makeagif.com/i/TyqWGx

Vulnerability #2: Session Hijacking/Fixation
    With two browsers in two separate machines I was able to use the hacking tool to hijack the session by changing the PHPSESSIONID.
    https://makeagif.com/i/OUa_BI


## Green

Vulnerability #1: Username Enumeration
    	The bolding indicates which user names are in the database.
	https://makeagif.com/i/7S2A94

Vulnerability #2: Cross-Site Scripting (XSS)
    The vulnerability is in the contact form and reveals itself in the feedback page.
    https://makeagif.com/i/E1kaUF


## Red

Vulnerability #1: Insecure Direct Object Reference (IDOR)
    User can manipulate url and can access sensitive info.
    https://makeagif.com/i/uLAsx1

Vulnerability #2: Cross-Site Request Forgery (CSRF)
    Using burp I was able to isolated the form and change user information with the admins credentials.
    https://makeagif.com/i/NpAe9a



## Notes

Describe any challenges encountered while doing the work
