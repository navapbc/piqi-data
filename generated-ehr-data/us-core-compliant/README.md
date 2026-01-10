# US Core 6.1.0 Compliant Data

The data in this folder was generated through [Synthea](https://github.com/synthetichealth/synthea/wiki/Basic-Setup-and-Running).

Both CCDA and FHIR (R4) data was generated in their respective folders. The metadata folder contains metadata artifacts from the Synthea generation. 

## (Lack of) USCDI Compliance

The data in this folder was configured to be compliant with US Core 6.1.0, however Synthea does not have an option to generate data using USCDI.
Clinical Architecture's Test Clients currently evaluate PIQI messages against USCDI v2 or v3. Due to this, the generated data is not guaranteed to be free of errors when evaluated by a PIQI client.