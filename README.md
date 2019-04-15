## Changes made:-

* Port needed to be initialized to 5001 since in dockerfile it was exposed to 5001.
	* Change => app.run(host='0.0.0.0', port=int("5001"))

* Local folder in yml file is specified incorrectly.
	* Correction => "data" -- "./data"

* Synchronized of port no. 80 in flaskapp.conf and in yml file.	
	* Correction => "8080:80"
