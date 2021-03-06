---
Description: Represents a set of components that function as a single high-level entity.
ms.assetid: 784cee32-e0ae-4632-8dac-e5110513f5c9
title: CIM_System class
ms.topic: article
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- CIM_System
- CIM_System.CreationClassName
- CIM_System.Name
- CIM_System.NameFormat
- CIM_System.PrimaryOwnerName
- CIM_System.PrimaryOwnerContact
- CIM_System.Roles
- CIM_System.OtherIdentifyingInfo
- CIM_System.IdentifyingDescriptions
api_type: 
- DllExport
api_location: 
- vmms.exe
---

# CIM\_System class

Represents a set of components that function as a single high-level entity.

## Syntax

``` syntax
[Abstract, Version("2.15.0"), UMLPackagePath("CIM::Core::CoreElements"), AMENDMENT]
class CIM_System : CIM_EnabledLogicalElement
{
  string CreationClassName;
  string Name;
  string NameFormat;
  string PrimaryOwnerName;
  string PrimaryOwnerContact;
  string Roles[];
  string OtherIdentifyingInfo[];
  string IdentifyingDescriptions[];
};
```

## Members

The **CIM\_System** class has these types of members:

-   [Properties](#properties)

### Properties

The **CIM\_System** class has these properties.

<dl> <dt>

**CreationClassName**
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**Key**](https://docs.microsoft.com/windows/desktop/WmiSdk/key-qualifier), [**MaxLen**](https://docs.microsoft.com/windows/desktop/WmiSdk/standard-qualifiers) (256)
</dt> </dl>

The class name used to create an instance of this class. **CreationClassName** is combined with other key properties of this class to uniquely identify instances of this class and its subclasses.

</dd> <dt>

**IdentifyingDescriptions**
</dt> <dd> <dl> <dt>

Data type: **string** array
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**ArrayType**](https://docs.microsoft.com/windows/desktop/WmiSdk/standard-qualifiers) ("Indexed"), [**ModelCorrespondence**](https://docs.microsoft.com/windows/desktop/WmiSdk/standard-qualifiers) ("**CIM\_System**.**OtherIdentifyingInfo**")
</dt> </dl>

An array that contains descriptions of the values in the **OtherIdentifyingInfo** property. The array items in **IdentifyingDescriptions** correspond to the items in the **IdentifyingDescriptions** property.

</dd> <dt>

**Name**
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**Key**](https://docs.microsoft.com/windows/desktop/WmiSdk/key-qualifier), [**Override**](https://docs.microsoft.com/windows/desktop/WmiSdk/standard-qualifiers) ("Name"), [**MaxLen**](https://docs.microsoft.com/windows/desktop/WmiSdk/standard-qualifiers) (256)
</dt> </dl>

The key of this instance in an enterprise environment.

</dd> <dt>

**NameFormat**
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**MaxLen**](https://docs.microsoft.com/windows/desktop/WmiSdk/standard-qualifiers) (64)
</dt> </dl>

The naming convention used by the Name property to ensure that **Name** values are unique.

</dd> <dt>

**OtherIdentifyingInfo**
</dt> <dd> <dl> <dt>

Data type: **string** array
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**ArrayType**](https://docs.microsoft.com/windows/desktop/WmiSdk/standard-qualifiers) ("Indexed"), [**MaxLen**](https://docs.microsoft.com/windows/desktop/WmiSdk/standard-qualifiers) (256), [**ModelCorrespondence**](https://docs.microsoft.com/windows/desktop/WmiSdk/standard-qualifiers) ("**CIM\_System**.**IdentifyingDescriptions**")
</dt> </dl>

An array that contains a set of additional data, beyond system name information, that could be used to identify a computer system.

</dd> <dt>

**PrimaryOwnerContact**
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read/write
</dt> <dt>

Qualifiers: [**MaxLen**](https://docs.microsoft.com/windows/desktop/WmiSdk/standard-qualifiers) (256), [**MappingStrings**](https://docs.microsoft.com/windows/desktop/WmiSdk/standard-qualifiers) ("MIF.DMTF\|General Information\|001.4")
</dt> </dl>

A string that provides information on how the primary system owner can be reached (for example, phone number, e-mail address, and so on).

</dd> <dt>

**PrimaryOwnerName**
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read/write
</dt> <dt>

Qualifiers: [**MaxLen**](https://docs.microsoft.com/windows/desktop/WmiSdk/standard-qualifiers) (64), [**MappingStrings**](https://docs.microsoft.com/windows/desktop/WmiSdk/standard-qualifiers) ("MIF.DMTF\|General Information\|001.3")
</dt> </dl>

The name of the primary user of the system.

</dd> <dt>

**Roles**
</dt> <dd> <dl> <dt>

Data type: **string** array
</dt> <dt>

Access type: Read/write
</dt> </dl>

An array that contains the roles carried out by the system in an enterprise environment.

</dd> </dl>

## Requirements



|                                     |                                                                                                         |
|-------------------------------------|---------------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 8<br/>                                                                                    |
| Minimum supported server<br/> | Windows Server 2012<br/>                                                                          |
| Namespace<br/>                | Root\\virtualization\\v2<br/>                                                                     |
| MOF<br/>                      | <dl> <dt>WindowsVirtualization.V2.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>Vmms.exe</dt> </dl>                     |



## See also

<dl> <dt>

[**CIM\_EnabledLogicalElement**](cim-enabledlogicalelement.md)
</dt> </dl>

 

 




