FHIR-boilerplate
================
FROM [google/fhir-examples: Usage Examples for github.com/google/fhir](https://github.com/google/fhir-examples)

### Tools
- [JSON to NDJSON Online Converter - Newline Delimited JSON](https://www.json-to-ndjson.app/)
- [Synthea by the Standard Health Record Collaborative](https://synthetichealth.github.io/synthea/)
    - [synthetichealth/synthea: Synthetic Patient Population Simulator](https://github.com/synthetichealth/synthea)
- [generated-sample-data/DSTU-2 at master · smart-on-fhir/generated-sample-data](https://github.com/smart-on-fhir/generated-sample-data/tree/master/DSTU-2)
- [smart-on-fhir/tag-uploader: Adds tags to FHIR bundles and resources and uploads them to specified servers](https://github.com/smart-on-fhir/tag-uploader)
- [RadovanTomik/FhirMaker: A tool for transforming medical data into the FHIR format](https://github.com/RadovanTomik/FhirMaker)

### Server
- [intervention-engine/fhir: Generic FHIR server implementation in GoLang.](https://github.com/intervention-engine/fhir)

### TODOs
- Generate a synthetic FHIR JSON dataset in a docker image
    - https://github.com/google/fhir-examples/blob/master/generate-synthea.sh

### Conversion
- From HL7
    - [microsoft/FHIR-Converter](https://github.com/microsoft/FHIR-Converter)
        - 
        ```
        .\Microsoft.Health.Fhir.Liquid.Converter.Tool.exe convert --TemplateDirectory "FHIR-Converter\data\Templates\Hl7v2" --RootTemplate ADT_A01 --InputDataFolder "FHIR-Converter\data\SampleData\Hl7v2" --OutputDataFolder ".\output"
        ```
### Reference
- [Index - FHIR v4.0.1](http://hl7.org/fhir/)
- [ndjson](http://ndjson.org/)
- [microsoft/fhir-server: A service that implements the FHIR standard](https://github.com/microsoft/fhir-server)
