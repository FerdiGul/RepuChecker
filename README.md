# RepuChecker @2019


	 _   ___                ___ _           _                 _   __    _ 
	| | | _ \___ _ __ _  _ / __| |_  ___ __| |_____ _ _  __ _/ | /  \  | |
	| | |   / -_) '_ \ || | (__| ' \/ -_) _| / / -_) '_| \ V / || () | | |
	| | |_|_\___| .__/\_,_|\___|_||_\___\__|_\_\___|_|    \_/|_(_)__/  | |
	|_|         |_|                                                    |_|
		
		The Reputation Checker on VT - McAffee - AbuseIpDB [ @2019 ]<br>

Developed by @FerdiGul  <br>
You have an idea about project? Contact me : @0xfrd1<br>

Note: Details of project are on my blog: https://ferdigul.com/repuchecker-v1-tool/<br>

RepuChecker Tool help you to check URL/IP reputation on some platform such as security engines and ip database..<br>




Which version of Python do I need?<br>
Any Python 2.x version >= 2.7.0. mechanize does not currently support python 3.<br>
#Install Python 2.7.x: https://www.python.org/downloads/release/python-2716/<br>


Install pip on Windows:<br>
	https://bootstrap.pypa.io/get-pip.py<br>
	python get-pip.py<br>
	

Install Modules for project:<br>
	import mechanize<br>
	from BeautifulSoup import BeautifulSoup<br>
	import sys<br>
	import datetime<br>
	import Tkinter<br>
	import tkFileDialog<br>
	import requests<br>
	import time<br>
	from random import choice<br>
	
Example: >pip install mechanize<br>

Note: on VT option you can see some notice about usage of api key: <br>
	The Public API is limited to 4 requests per minute.<br>
	The Public API must not be used in commercial products or services.<br>
	The Private API returns <br>
	threat data and exposes more endpoints.<br>
	The Private API is governed by an SLA that guarantees readiness of data.<br>
	

Note: on VT option you can see some info about usage of api key: <br>

https://developers.virustotal.com/v2.0/reference#public-vs-private-api<br>

But you can send random http headers and api keys for pass it :). But if you wanna use your premium api key, yes just add your api key in this section:<br>

def checkDomain_VT(urlist):

	api = ['   <api key is here>   ']<br>

For now, only these engines were added on tool I’ve listed as you can see below:<br>

McAfee (trustedsource.org | McAfee Web Gateway v7.x/6.9.x (Resident)), <br>
VirusTotal (https://www.virustotal.com/gui/home/url),<br>
AbuseIpDB (abuseipdb.com)<br>
So, what can we perform via engines or dbs ?:<br>

In All of engines or dbs listed options, cheackable only single url/ip or more than one urls/ips.
