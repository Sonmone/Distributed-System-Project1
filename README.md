# Distributed-System-Project1
A based distributed system of both servers and clients supproting several basic functions.

Introduction
-------------
  
This project implements a simple distributed system with both client and server program.<br/>
  
Compilation
-------------

Go to the root folder of code 3.0, then use CMD order:<br/>
javac-Djava.ext.dirs=./lib -d bin @bian.txt <br/>
Besides, the log4j2.xml must be included in src folder along with activitystreamer file folder.<br/>

Run
-------------

Go to this folder: code 3.0/bin<br/>
Run client through this CMD order:<br/>
java -Djava.ext.dirs=../lib activitystreamer.Client<br/>
Run server through this CMD order:<br/>
java -Djava.ext.dirs=../lib activitystreamer.Server<br/>

Activity Format
-------------

If the client wants send an activity message, it must input a JSON text in GUI such as
{"sport": "running"}.

