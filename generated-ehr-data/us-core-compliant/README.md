# US Core 6.1.0 Compliant Data

The data in this folder was generated using [Synthea](https://github.com/synthetichealth/synthea/wiki/Basic-Setup-and-Running).

Both CCDA and FHIR (R4) data was generated in their respective folders. The metadata folder contains artifacts from the Synthea generation. 

## (Lack of) USCDI Compliance

Synthea does not have a configuration option to generate data according to USCDI. Thus, the data in this folder is not guaranteed to be USCDI compliant.
Clinical Architecture's Test Clients currently evaluate PIQI messages against USCDI v2 and v3. Due to this, the generated data is not guaranteed to be free of errors when evaluated by a PIQI client.