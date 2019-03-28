
This page prepared alongside a submission to the Canadian Open Data Challenge 2019 

## Project Summary

We are Cait and Jane Harrigan. We’re from Vancouver, but both moved to Ontario for undergraduate studies. We’re based out of the University of Toronto and University of Waterloo respectively. Our reason for making use of Canadian open data is to implement an idea that Jane first pitched to make geocoding more human-readable, WordLynx. The idea is that we can map any location in the world using just 3 words. This in itself is not novel (what3words is an existing geocoding system), but we extend on this by creating a model that is hierarchical, iterative, and intuitive. The value that this system brings is to index locations, regardless of whether or not they have a mailing address in a standardized format. This is particularly useful for people working in rural areas, developing countries, and ecological conservation zones. 


## Impact 

This project is designed to make mapping locations easy in places where addressing systems are inconsistent or missing. The immediate impact of WordLynx is that for any longitude-latitude based mapping, a simple, memorable short code is available. We see this being useful in a wide variety of applications due to its flexibility, in particular research. For example, citizen scientists may more easily report invasive weeds in park areas. Health mapping in remote areas could be more accessible, in coordination with the mobile tool we intend to create for this project. We envision any type of data reporting to be simplified with human-readable codes. 
The project can be easily further adapted to other deterministic mappings of hard-to-remember alphanumeric strings, such as phone numbers, bank accounts, id numbers, or even the human genome and all its variants. 

## Goals of the project 

1. Create a human readable geolocating system 
2. Standardized addressing of locations with or without mailing addresses

The naming system developed for the prototype demonstrates that WordLynx we can uniquely geocode the whole planet to a fine-grained degree using only three variable words. WordLynx will continue to be developed as a freely available, user-friendly, mobile and web-based app.

## Data accessed 

* Open database of buildings

	https://www.statcan.gc.ca/eng/open-building-data/open-database 

* Geographic attribute file

	https://www150.statcan.gc.ca/n1/pub/92-151-g/92-151-g2016001-eng.htm  

## How the data is used

We downloaded every building, as well as larger geographic attributes, in BC and Ontario from the open database of buildings and the geographic attribute file. We linked latitude and longitude identifiers in these databases to three unique, user-friendly, words to generate labels with the functionality currently provided by mailing addresses. This was used in a web-app (WordLynx) with address search functions embedded in open source mapping software.
