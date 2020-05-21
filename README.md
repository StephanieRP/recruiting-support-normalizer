# normalizer-take-home

recruiting-support-normalizer module

## Dependencies
`node >= 10`

`npm >= 6`

Node typically comes with npm packaged and can be downloaded here https://nodejs.org/en/download/


## Installation
Using npm:
```
npm i 
```

## Tests
To run the test suite, first install the dependencies, then run `npm test`.

## Instructions

- Please clone the following package repo: https://github.com/ProminentEdge/normalizer-take-home.git 
- Without touching this package's tests, make them pass by changing src/incident.js.
- The raw data used by the payload can be examined by either inserting console.dir(payload) into the back portion of the constructor (after the super() call) or by examining the contents of the files in the test/data/ directory.
- The tests given in the test/test.js file outline the form of the object expected, and the target values for those fields should give you clues as to what the proper mapping is from the files stored in test/data.
- In addition, please add a 'location.supervisor_district' field to the address object that supplies the information from the supervisor_district field in the incoming data files. Please add a passing test for this field.
- Please issue a pull request against the package repository that will result in all tests passing and that includes your new mapping and test for 'location.supervisor_district'.
