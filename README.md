# icws-connector
 Template node.js Express app for connecting to ICWS instances

Currently tested with PureConnect 2018 R3.

Requires environment variables for authentication, either run as args or create a .env file with the following:
CICUSER=username
CICPASSWORD=password
CICURL=http://hostname:port
CICSERVER=hostname
CONNECTIONTYPE=local or internet
SERVERPORT=port

Run with npm start. Template verified in console validates ICWS connection.