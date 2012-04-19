Evernote SDK for Python version 1.21
============================================

Overview
--------
This SDK contains wrapper code used to call the Evernote Cloud API from Python.

The SDK also contains a sample script. The code demonstrates the basic use of the SDK for single-user scripts that authenticate using username and password. Note that web applications must use OAuth to authenticate to the Evernote service.

Prerequisites
-------------
In order to use the code in this SDK, you need to obtain an API key from http://dev.evernote.com/documentation/cloud. You'll also find full API documentation on that page.

In order to run the sample code, you need a user account on the sandbox service where you will do your development. Sign up for an account at https://sandbox.evernote.com/Registration.action 

Getting Started
---------------
Single-user scripts may authenticate to the Evernote service using username and password. The code in sample/client/EDAMDemo.java demonstrates the basics.

1. Open sample/client/EDAMTest.py
2. Scroll down and fill in your Evernote API consumer key and secret.
3. On the command line, run the following command to execute the script:

    export PYTHONPATH=../lib; python EDAMTest.py username password

    Replace username and password with the username and password of your Evernote sandbox user account.
