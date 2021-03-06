# Move-TppObject

## SYNOPSIS
Move an object of any type

## SYNTAX

```
Move-TppObject [-SourcePath] <String> [-TargetPath] <String> [[-VenafiSession] <VenafiSession>]
 [<CommonParameters>]
```

## DESCRIPTION
Move an object of any type

## EXAMPLES

### EXAMPLE 1
```
Move-TppObject -SourceDN '\VED\Policy\My Folder\mycert.company.com' -TargetDN '\VED\Policy\New Folder\mycert.company.com'
```

Moves mycert.company.com to a new Policy folder

## PARAMETERS

### -SourcePath
Full path to an object in TPP

```yaml
Type: String
Parameter Sets: (All)
Aliases: SourceDN

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TargetPath
New path

```yaml
Type: String
Parameter Sets: (All)
Aliases: TargetDN

Required: True
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -VenafiSession
Session object created from New-VenafiSession method. 
The value defaults to the script session object $VenafiSession.

```yaml
Type: VenafiSession
Parameter Sets: (All)
Aliases:

Required: False
Position: 3
Default value: $script:VenafiSession
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### none
## OUTPUTS

## NOTES

## RELATED LINKS

[http://VenafiPS.readthedocs.io/en/latest/functions/Move-TppObject/](http://VenafiPS.readthedocs.io/en/latest/functions/Move-TppObject/)

[http://VenafiPS.readthedocs.io/en/latest/functions/Test-TppObject/](http://VenafiPS.readthedocs.io/en/latest/functions/Test-TppObject/)

[https://github.com/gdbarron/VenafiPS/blob/main/VenafiPS/Code/Public/Move-TppObject.ps1](https://github.com/gdbarron/VenafiPS/blob/main/VenafiPS/Code/Public/Move-TppObject.ps1)

[https://docs.venafi.com/Docs/20.4SDK/TopNav/Content/SDK/WebSDK/r-SDK-POST-Config-renameobject.php?tocpath=Web%20SDK%7CConfig%20programming%20interface%7C_____35](https://docs.venafi.com/Docs/20.4SDK/TopNav/Content/SDK/WebSDK/r-SDK-POST-Config-renameobject.php?tocpath=Web%20SDK%7CConfig%20programming%20interface%7C_____35)

