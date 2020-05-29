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

1.  Clone the following package repo: https://github.com/ProminentEdge/recruiting-support-normalizer.git 
2.  Modify the code to accomplish the following:
   - [ ] Make all test's pass by modifying the code contained in src/incident.js.  No tests in test/test.js should be removed or modified.    
   - [ ] The customer has requested to add a new field to track the supervisor district.  Please add a new field (`address.location.supervisor_district`) in the normalizeAddress() function.  This should be populated with the `supervisor_district` value in the incoming raw data files.  
   - [ ] Create a new test in test/test.js verifying your new field.  
3. Commit the changes
4.  Issue a pull request with your changes

## Notes
- The raw data used by the payload can be examined by examining the contents of the files in the test/data/ directory.
- The tests given in the test/test.js file outline the form of the object expected, and the target values for those fields should give you clues as to what the proper mapping is from the files stored in test/data.
