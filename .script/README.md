# Convert Sentinel Rule From Yaml Format

U can use this PowerShell function to convert the Detections rules published in the Microsoft Sentinel Github repository to the right Azure Resource Manager format. This way you can easily import the rules by configuring Repository blade integration in Microsoft Sentinel or through ARM deployment.

## Example

```PowerShell
  ./.script/ConvertSentinelRuleFrom-Yaml -Path './.tmp/ASimDNS' -OutputFolder
```

This function is using powershell-yaml (great work by [@Gabriel](https://github.com/gabriel-samfira) ) to convert the data

## Links

- Source of the Detection rules: https://github.com/Azure/Azure-Sentinel/tree/master/Detections
- PowerShell-YAML module: https://github.com/cloudbase/powershell-yaml
