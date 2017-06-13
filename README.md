# GRETA-model-view
Working file for model view of GRETA

This project requires npm. Install npm, then initialize using

npm init

Install d3, by using

npm install d3

Further documentation: https://github.com/d3/d3/wiki


Install http-server globally with

npm install -g http-server

Further documentation: https://www.npmjs.com/package/http-server
or, type "http-server -h" for the man page



To start the page, navigate to the cloned repository, and type

http-server &

Open a browser of your choice (I use Chrome), and type "localhost:8080" (or whichever port you happen to be using). Write using developer mode.

To close the server, type "lsof -i :8080" to determine the PID. Then, type "kill PID" where PID is the actual PID.
