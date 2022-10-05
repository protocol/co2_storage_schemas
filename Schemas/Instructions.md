## Schema Creation Instructions
We strongly encourage anyone working to tokenize environmental assets (RECs, Carbon Credits, Impact Certificates, etc.) to create new data schemas in this repository. The schemas created here will be utilized in [CO2.Storage](https://co2.storage) as base template schemas for industry practitioneers to leverage for their own use.  

To create a new schema, (1) create a new folder following this path co2_storage_schemas/Schemas/[YOUR_NEW_FOLDER], and (2) include these three artifacts:

- proposed data schema as a json file
- schema description
- example datapoint conforming to the schema


## Currently Supported Data Types:

- int, integer
- decimal, float
- str, string
- txt, text, textarea
- bool, boolean
- date (single date)
- dates (multiple dates)
- datetime (single datetime)
- datetimes (multiple datetimes)
- daterange (date range)
- datetimerange (datetime range)
- array (lists)
- images
- documents


These data types correspond to the [Form Element case statements here](https://github.com/protocol/co2-storage/blob/main/client/web/src/mixins/form-elements/update-form.js
). If your schema requires datatypes that are not currently supported, please request for a new datatype and tag [@mjohnson518](https://github.com/mjohnson518). 
