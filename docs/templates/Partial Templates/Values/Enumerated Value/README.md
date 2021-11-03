Enumerated Value
================



```
concept {
    IfcPropertyEnumeratedValue:Name -> IfcIdentifier
    IfcPropertyEnumeratedValue:Description -> IfcText
    IfcPropertyEnumeratedValue:EnumerationValues -> IfcValue
    IfcPropertyEnumeratedValue:EnumerationReference -> IfcPropertyEnumeration
    IfcPropertyEnumeration:Name -> IfcLabel
    IfcPropertyEnumeratedValue:Name[binding="PropertyName"]
    IfcPropertyEnumeratedValue:EnumerationValues[binding="Value"]
    IfcPropertyEnumeration:Name[binding="Reference"]
}
```
