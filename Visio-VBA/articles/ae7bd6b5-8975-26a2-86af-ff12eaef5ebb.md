
# Page.GroupCanceled Event (Visio)

Occurs after an event handler has returned  **True** (cancel) to a **QueryCancelGroup** event.


## Syntax

Private Sub  _expression__**GroupCanceled**( **_ByVal Selection As [IVSELECTION]_**)

 _expression_A variable that represents a  **Page** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
|Selection|Required| **[IVSELECTION]**|The selection of shapes that was going to be grouped.|

## Remarks

If you're using Microsoft Visual Basic or Visual Basic for Applications (VBA), the syntax in this topic describes a common, efficient way to handle events.

If you want to create your own  **Event** objects, use the **Add** or **AddAdvise** method. To create an **Event** object that runs an add-on, use the **Add** method as it applies to the **EventList** collection. To create an **Event** object that receives notification, use the **AddAdvise** method. To find an event code for the event you want to create, see [Event codes](de8f5c7a-421d-ebcf-22b6-4310a202ef64.md).

