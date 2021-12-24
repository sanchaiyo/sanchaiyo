# SFDC Knowledge
## Useful SOQL
| Description  | SOQL |
| ------------- | ------------- |
| Get Fields from Object  | SELECT Id,MasterLabel,QualifiedApiName,DataType FROM FieldDefinition WHERE EntityDefinition.QualifiedApiName = <--Custom Object API> |