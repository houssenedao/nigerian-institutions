List of Nigerian Institutions 
=============================

A searchablen list of all federal, state and private universities, polytechnics, colleges of education and monotechnics in Nigeria with city and abbreviation.


## Installation

npm install nigerian-institutions

## Usage

var institutions = require('nigerian-institutions');

// To implement realtime or normal search for any school in Nigeria, it will return array of schools with name and city closest to you search input

//Example 1
var response = institutions.search('ABU Zaria');    // [{ name: "Ahmadu Bello University, Zaria", city: "Zaria", code: "ABU Zaria" }, { name: "Nuhu Bamalli Polytechnic, Zaria", city: "Zaria", code: "NUBA Zaria"}, .......]

//Example 2

var response = institutions.allSchools();   // Return list of all institutions in Nigeria

## Contributing

You can contribute follow me on github.com/motionboy and fork the repo...
