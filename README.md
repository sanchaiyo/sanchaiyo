# SFDC Knowledge
## Useful SOQL
| Description  | SOQL |
| ------------- | ------------- |
| Get Fields from Object  | ```SELECT Id,MasterLabel,QualifiedApiName,DataType FROM FieldDefinition WHERE EntityDefinition.QualifiedApiName = <--Custom Object API-->``` |
| Get Custom Label  | ```SELECT Id,MasterLabel,Value,Language,Category FROM Externalstring``` |
| Get Custom Label Translation  | ```SELECT Id,ExternalString.MasterLabel,Value,Language,ExternalString.Category FROM ExternalStringLocalization``` |
| Get Field Permisison  | ```SELECT Id,Parent.Profile.Name,Parent.Name,ParentId,Field,PermissionsRead,PermissionsEdit FROM FieldPermissions WHERE SobjectType = 'Lead'``` |

## Good Tool
- [JSPdf](https://github.com/parallax/jsPDF)
