# Gather Solar Data

Gather solar production and home consumption data from a local Enphase Envoy system 
and log to a SQL database.  


# Environment Variables

	ENPHASE_HOST=envoy.local
	ENPHASE_PORT=80
	SOLARDB_USER=
	SOLARDB_PASS=
	SOLARDB_NAME=
	SOLARDB_TABLE=
	SOLARDB_HOST=192.168.11.10
	SOLARDB_PORT=3306
	TZ=America/Los_Angeles



# Command line
To build:

	docker build -t gathersolar .

To run:

	docker run -it --rm --name gathersolarrun gathersolar