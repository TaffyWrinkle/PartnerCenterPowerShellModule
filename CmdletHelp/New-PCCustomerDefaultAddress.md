# New-PCCustomerDefaultAddress

This cmdlet is used to create a PowerShell object that can be passed to other cmdlets, such as the the New-PCCustomerBillingProfile cmdlet.

## SYNTAX

```powershell
New-PCCustomerDefaultAddress [-Country] <String> [[-Region] <String>] [-City] <String> [-State] <String> [-AddressLine1] <String> [-PostalCode] <String> [-FirstName] <String> [-LastName] <String> [-PhoneNumber] <String> [<CommonParameters>]
```

## DESCRIPTION

The New-PCCustomerDefaultAddress cmdlet returns a PowerShell object with the properties for a default address.

## PARAMETERS

### -Country &lt;String&gt;

Specifies the country for the customer company.

```
Required?                    true
Position?                    1
Default value
Accept pipeline input?       false
Accept wildcard characters?  false
```

### -Region &lt;String&gt;

Specifies the three letter region for the customer company.

```
Required?                    false
Position?                    2
Default value
Accept pipeline input?       false
Accept wildcard characters?  false
```

### -City &lt;String&gt;

Specifies the city for the customer's company address.

```
Required?                    true
Position?                    3
Default value
Accept pipeline input?       false
Accept wildcard characters?  false
```

### -State &lt;String&gt;

Specifies the state for the customer's company address.

```
Required?                    true
Position?                    4
Default value
Accept pipeline input?       false
Accept wildcard characters?  false
```

### -AddressLine1 &lt;String&gt;

Specifies the first address line for the customer's address.

```
Required?                    true
Position?                    5
Default value
Accept pipeline input?       false
Accept wildcard characters?  false
```

### -PostalCode &lt;String&gt;

Specifies the postal code for the customer's address.

```
Required?                    true
Position?                    6
Default value
Accept pipeline input?       false
Accept wildcard characters?  false
```

### -FirstName &lt;String&gt;

Specifies the first name for the customer's contact.

```
Required?                    true
Position?                    7
Default value
Accept pipeline input?       false
Accept wildcard characters?  false
```

### -LastName &lt;String&gt;

Specifies the last name for the customer's contact.

```
Required?                    true
Position?                    8
Default value
Accept pipeline input?       false
Accept wildcard characters?  false
```

### -PhoneNumber &lt;String&gt;

Specifies the phone number for the customer's contact.

```
Required?                    true
Position?                    9
Default value
Accept pipeline input?       false
Accept wildcard characters?  false
```

## INPUTS

## OUTPUTS

## NOTES

## EXAMPLES

### EXAMPLE 1

Create a new PowerShell object that includes the properties for a customer's default address.

```powershell
PS C:\>$cda = New-PCCustomerDefaultAddress -Country 'US' -Region 'USA' -City 'Redmond' -State 'WA' -AddressLine1 '1 Microsoft Way' -PostalCode '98502' -FirstName 'John' -LastName 'Smith' -PhoneNumber '8005551212'
```
