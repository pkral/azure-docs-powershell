---
external help file: Microsoft.WindowsAzure.Commands.dll-Help.xml
online version: 
schema: 2.0.0
ms.assetid: 3A514910-AF12-4BC2-B9D3-A19FF28DA1E6
---

# Stop-AzureWebsiteJob

## SYNOPSIS
Stops a web job for a website.

## SYNTAX

```
Stop-AzureWebsiteJob -JobName <String> [-PassThru] [[-Name] <String>] [-Slot <String>]
 [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Stop-AzureWebsiteJob** cmdlet stops a web job for a website.

## EXAMPLES

### Example 1: Stop a web job for a website
```
PS C:\> Stop-AzureWebsiteJob -Name MyWebsite -JobName MyWebJob -JobType Continuous
```

Stops a web job called MyWebJob for MyWebSite.

## PARAMETERS

### -Name
The name of the Azure website.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Slot
The slot name of the Azure website.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -JobName
The web job name.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -PassThru
Returns a boolean value indicating that the job stopped successfully.
By default, this cmdlet does not return any output.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Profile

```yaml
Type: AzureSMProfile
Parameter Sets: (All)
Aliases: 

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

[Stop-AzureWebsite](./Stop-AzureWebsite.md)

[Get-AzureWebsiteJob](./Get-AzureWebsiteJob.md)

[New-AzureWebsiteJob](./New-AzureWebsiteJob.md)

[Remove-AzureWebsiteJob](./Remove-AzureWebsiteJob.md)

[Start-AzureWebsiteJob](./Start-AzureWebsiteJob.md)

