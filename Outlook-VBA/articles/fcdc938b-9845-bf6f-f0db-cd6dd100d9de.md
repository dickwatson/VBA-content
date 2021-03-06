
# FormRegion.DisplayName Property (Outlook)

Returns a  **String** representing the display name of the form region. Read-only.


## Syntax

 _expression_. **DisplayName**

 _expression_A variable that represents a  **FormRegion** object.


## Remarks

The display name is optional for a form region. If you have defined a value for the <formRegionName> tag in the corresponding form region manifest XML file, this value will map to the value of the  **DisplayName** property. For more information on the XML schema for form regions, see the Microsoft Outlook 2010 XML Schema Reference in the [MSDN Library](http://msdn.microsoft.com/library).

The value of the  **DisplayName** property is displayed at runtime in the **Show** tab of the ribbon for a separate form region, or in the header of an adjoining form region. It is used for the default locale, and can be overridden by the <stringOverride> tag in the corresponding form region manifest XML file. The string is case-insensitive, and its maximum length is 256 characters.


## See also


#### Concepts


 [FormRegion Object](3a0b83eb-4076-9cb3-86a9-68f9e44df89f.md)
#### Other resources


 [FormRegion Object Members](eb4ff750-2911-8f8d-2ef0-c3f5e7adf4e0.md)
