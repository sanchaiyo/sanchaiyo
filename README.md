# SFDC Knowledge
## Useful SOQL
| Description  | SOQL |
| ------------- | ------------- |
| Get Fields from Object  | SELECT Id,MasterLabel,QualifiedApiName,DataType FROM FieldDefinition WHERE EntityDefinition.QualifiedApiName = <--Custom Object API> |
| Get Custom Label  | SELECT Id,MasterLabel,Value,Language,Category FROM Externalstring |
| Get Custom Label Translation  | SELECT Id,ExternalString.MasterLabel,Value,Language,ExternalString.Category FROM ExternalStringLocalization |