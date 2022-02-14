# SFDC Knowledge
## Useful SOQL
| Description  | SOQL |
| ------------- | ------------- |
| Get Fields from Object  | ```SELECT Id,MasterLabel,QualifiedApiName,DataType FROM FieldDefinition WHERE EntityDefinition.QualifiedApiName = <--Custom Object API-->``` |
| Get Custom Label  | ```SELECT Id,MasterLabel,Value,Language,Category FROM Externalstring``` |
| Get Custom Label Translation  | ```SELECT Id,ExternalString.MasterLabel,Value,Language,ExternalString.Category FROM ExternalStringLocalization``` |


# Other Stuff (Don't POC)
## MYSQL Command
- LOAD DATA INFILE 'C:/code/olympus-sea/scripts/data/Opportunity.csv' INTO TABLE olympus.opportunity FIELDS TERMINATED BY ',' ENCLOSED BY '"' LINES TERMINATED BY '\n' IGNORE 1 ROWS;

## Good Tool
- [JSPdf](https://github.com/parallax/jsPDF)
