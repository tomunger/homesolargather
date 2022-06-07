# Gather Solar Data

Gather solar production and home consumption data from a local Enphase Envoy system 
and log to a SQL database.  


# Command line
To build:

	docker build -t gathersolar .

To run:

	docker run -it --rm --name gathersolarrun gathersolar