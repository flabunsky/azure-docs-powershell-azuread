---
external help file: Microsoft.Open.AzureAD16.Graph.PowerShell.dll-Help.xml
online version: 
schema: 2.0.0
ms.assetid: CAA240EC-E380-4CDB-A1CC-56BBD28DFB82
---

# Get-AzureADDirectoryRole

## SYNOPSIS
Retrieves a specific directory role from Azure Active Directory

## SYNTAX

### GetQuery (Default)
```
Get-AzureADDirectoryRole [-InformationAction <ActionPreference>] [-InformationVariable <String>]
 [<CommonParameters>]
```

### GetById
```
Get-AzureADDirectoryRole -ObjectId <String> [-InformationAction <ActionPreference>]
 [-InformationVariable <String>] [<CommonParameters>]
```

## DESCRIPTION

## EXAMPLES

### -------------------------- EXAMPLE 1 --------------------------
```
PS C:\>Get-AzureADDirectoryRole -ObjectId 019ea7a2-1613-47c9-81cb-20ba35b1ae48
```

Output:

ObjectId                             DisplayName                        Description
--------                             -----------                        -----------
019ea7a2-1613-47c9-81cb-20ba35b1ae48 Company Administrator              Company Administrator role has full access to perform any operation in the company scope.

### -------------------------- EXAMPLE 2 --------------------------
```
PS C:\>Get-AzureADDirectoryRole
```

Output:

ObjectId                             DisplayName                        Description
--------                             -----------                        -----------
019ea7a2-1613-47c9-81cb-20ba35b1ae48 Company Administrator              Company Administrator role has full access to perform any operation in the company scope.
2b3a80bc-51a4-476d-8e09-cd8b6cdde5ea Directory Writers                  Allows access read tasks and a subset of write tasks in the directory.
526b7173-5a6e-49dc-88ec-b677a9093709 User Account Administrator         User Account Administrator has access to perform common user management related tasks.
542f5aef-b23f-4e34-a838-6f2b9205b3d6 Directory Synchronization Accounts Directory Synchronization Accounts
68239fa3-6b01-4396-aeb4-6af38a1b6abf Directory Readers                  Allows access to various read only tasks in the directory.
8c6a5c45-e93e-4f2b-81be-b57ad4c43ddd Privileged Role Administrator      Privileged Role Administrator has access to perform common role management related tasks.
8f8a1cf4-d535-4ccd-8552-7267c7ee0a88 Helpdesk Administrator             Helpdesk Administrator has access to perform common helpdesk related tasks.
b89a48d4-7595-48d0-bb36-69fe4b220668 Device Administrators              Device Administrators
d96eb2b3-0970-4827-8f26-6008efd86511 Security Administrator             Security Administrator allows ability to read and manage security configuration and reports.

## PARAMETERS

### -ObjectId
The unique identifier of a directory role in Azure Active Directory (ObjectId)

```yaml
Type: String
Parameter Sets: GetById
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### -InformationAction
@{Text=}```yaml
Type: ActionPreference
Parameter Sets: (All)
Aliases: infa

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InformationVariable
@{Text=}```yaml
Type: String
Parameter Sets: (All)
Aliases: iv

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS


