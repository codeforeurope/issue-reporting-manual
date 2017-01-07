#
Administration

Open your browser with the link 
[http://localhost:8000/admin](http://localhost:8000/admin)

## Jurisdictions

Depending on whether your installation will be hosting a single or 
multiple cities, it is wise to start by entering at least one 
jurisdiction.

Select jurisdictions from the admin interface

Select add new

Enter information about the jurisdiction. It is common practice to 
identify a city by the official url, without the www, f.i. the 
identifier could be:

* nyc.gov
* eindhoven.nl

And for this example, we will use an Identifier in the form 
CITY-STATE-COUNTRY so in our case, we set the names to

* NYC-NY-US
* EHV-NB-NL

Now, when we enter on of the following url's:

* 
[http://localhost:8000/api/georeport/v2/services.json](http://localhost:8000/api/georeport/v2/services.json)
* 
[http://localhost:8000/api/georeport/v2/services.json?jurisdiction=eindhoven.nl](http://localhost:8000/api/georeport/v2/services.json?jurisdiction=eindhoven.nl)
* 
[http://localhost:8000/api/georeport/v2/services.json?jurisdiction=nyc.gov](http://localhost:8000/api/georeport/v2/services.json?jurisdiction=nyc.gov)

They will all return an empty array as we have no services defined. The 
endpoint is working as 
[http://localhost:8000/api/georeport/v2/services.json?jurisdiction=eindhoven.nl](http://localhost:8000/api/georeport/v2/services.json?jurisdiction=eindhoven.nl) 
shows by returning an empty services collection in XML format.

Next step: Services

## Services

