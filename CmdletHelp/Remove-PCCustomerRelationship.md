# Remove-PCCustomerRelationship

Removes reseller relationship from a customer domain in the CSP Portal.

## SYNTAX

```powershell
Remove-PCCustomerRelationship [[-TenantId] <Object>] [[-SaToken] <String>] [<CommonParameters>]
```

## DESCRIPTION

The Remove-PCCustomerRelationship cmdlet removes reseller relationship from a customer domain in the CSP Portal.

## PARAMETERS

### -TenantId &lt;Object&gt;

Specifies the tenant used for scoping this cmdlet.

```
Required?                    false
Position?                    1
Default value
Accept pipeline input?       false
Accept wildcard characters?  false
```
 
### -SaToken &lt;String&gt;

Specifies an authentication token with your Partner Center credentials.

```
Required?                    false
Position?                    2
Default value                $GlobalToken
Accept pipeline input?       false
Accept wildcard characters?  false
```

## INPUTS



## OUTPUTS

## NOTES



## EXAMPLES

### EXAMPLE 1

```powershell
PS C:\>Remove-PCCustomerRelationship -TenantId 97037612-799c-4fa6-8c40-68be72c6b83c
```


