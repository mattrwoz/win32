---
title: MDM_EnterpriseModernAppManagement_AppManagement01_03 class
description: The MDM\_EnterpriseModernAppManagement\_AppManagement01\_03 class provides specific information about the app, such as name, version, and publisher.
ms.assetid: 424e68de-1411-490f-b33b-5243ffa5a31e
keywords:
- MDM_EnterpriseModernAppManagement_AppManagement01_03 class
- MDM_EnterpriseModernAppManagement_AppManagement01_03 class, described
topic_type:
- apiref
api_name:
- MDM_EnterpriseModernAppManagement_AppManagement01_03
- MDM_EnterpriseModernAppManagement_AppManagement01_03.InstanceID
- MDM_EnterpriseModernAppManagement_AppManagement01_03.ParentID
api_location:
- DMWmiBridgeProv.dll
api_type:
- DllExport
ms.topic: article
ms.date: 05/31/2018
---

# MDM\_EnterpriseModernAppManagement\_AppManagement01\_03 class

\[Some information relates to pre-released product which may be substantially modified before it's commercially released. Microsoft makes no warranties, express or implied, with respect to the information provided here.\]

The **MDM\_EnterpriseModernAppManagement\_AppManagement01\_03** class provides specific information about the app, such as name, version, and publisher.

The following syntax is simplified from MOF code and includes all inherited properties.

## Syntax

``` syntax
[InPartition("local-system", "local-user"), dynamic, provider("DMWmiBridgeProv")]
class MDM_EnterpriseModernAppManagement_AppManagement01_03
{
  string InstanceID;
  string ParentID;
  string Name;
  string Version;
  string Publisher;
  string Architecture;
  string InstallLocation;
  sint32 IsFramework;
  sint32 IsBundle;
  string InstallDate;
  string ResourceID;
  sint32 PackageStatus;
  sint32 RequiresReinstall;
  string Users;
  sint32 IsProvisioned;
};
```

## Members

The **MDM\_EnterpriseModernAppManagement\_AppManagement01\_03** class has these types of members:

-   [Properties](#properties)

### Properties

The **MDM\_EnterpriseModernAppManagement\_AppManagement01\_03** class has these properties.

<dl> <dt>

[Architecture](https://docs.microsoft.com/windows/client-management/mdm/enterprisemodernappmanagement-csp#----packagefamilyname-packagefullname-architecture)
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read/write
</dt> </dl>

</dd> <dt>

[InstallDate](https://docs.microsoft.com/windows/client-management/mdm/enterprisemodernappmanagement-csp#----packagefamilyname-packagefullname-installdate)
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read/write
</dt> </dl>

</dd> <dt>

[InstallLocation](https://docs.microsoft.com/windows/client-management/mdm/enterprisemodernappmanagement-csp#----packagefamilyname-packagefullname-installlocation)
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read/write
</dt> </dl>

</dd> <dt>

**InstanceID**
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**key**](https://docs.microsoft.com/windows/desktop/WmiSdk/key-qualifier)
</dt> </dl>

Identifies the name of the parent node. For this class, the string is the instance of the package full name.

</dd> <dt>

[IsBundle](https://docs.microsoft.com/windows/client-management/mdm/enterprisemodernappmanagement-csp#----packagefamilyname-packagefullname-isbundle)
</dt> <dd> <dl> <dt>

Data type: **sint32**
</dt> <dt>

Access type: Read/write
</dt> </dl>

</dd> <dt>

[IsFramework](https://docs.microsoft.com/windows/client-management/mdm/enterprisemodernappmanagement-csp#----packagefamilyname-packagefullname-isframework)
</dt> <dd> <dl> <dt>

Data type: **sint32**
</dt> <dt>

Access type: Read/write
</dt> </dl>

</dd> <dt>

[IsProvisioned](https://docs.microsoft.com/windows/client-management/mdm/enterprisemodernappmanagement-csp#----packagefamilyname-packagefullname-isprovisioned)
</dt> <dd> <dl> <dt>

Data type: **sint32**
</dt> <dt>

Access type: Read/write
</dt> </dl>

</dd> <dt>

[Name](https://docs.microsoft.com/windows/client-management/mdm/enterprisemodernappmanagement-csp#----packagefamilyname-packagefullname-name)
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read/write
</dt> </dl>

</dd> <dt>

[PackageStatus](https://docs.microsoft.com/windows/client-management/mdm/enterprisemodernappmanagement-csp#----packagefamilyname-packagefullname-packagestatus)
</dt> <dd> <dl> <dt>

Data type: **sint32**
</dt> <dt>

Access type: Read/write
</dt> </dl>

</dd> <dt>

**ParentID**
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**key**](https://docs.microsoft.com/windows/desktop/WmiSdk/key-qualifier)
</dt> </dl>

Describes the full path to the parent node. For this class, the string is "./Vendor/MSFT/EnterpriseModernAppManagement/AppManagement/*EnterpriseID*/*PackageFamilyName*"

</dd> <dt>

[Publisher](https://docs.microsoft.com/windows/client-management/mdm/enterprisemodernappmanagement-csp#----packagefamilyname-packagefullname-publisher)
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read/write
</dt> </dl>

</dd> <dt>

[RequiresReinstall](https://docs.microsoft.com/windows/client-management/mdm/enterprisemodernappmanagement-csp#----packagefamilyname-packagefullname-requiresreinstall)
</dt> <dd> <dl> <dt>

Data type: **sint32**
</dt> <dt>

Access type: Read/write
</dt> </dl>

</dd> <dt>

[ResourceID](https://docs.microsoft.com/windows/client-management/mdm/enterprisemodernappmanagement-csp#----packagefamilyname-packagefullname-resourceid)
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read/write
</dt> </dl>

</dd> <dt>

[Users](https://docs.microsoft.com/windows/client-management/mdm/enterprisemodernappmanagement-csp#----packagefamilyname-packagefullname-users)
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read/write
</dt> </dl>

</dd> <dt>

[Version](https://docs.microsoft.com/windows/client-management/mdm/enterprisemodernappmanagement-csp#----packagefamilyname-packagefullname-version)
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read/write
</dt> </dl>

</dd> </dl>

## Requirements



|                                     |                                                                                                |
|-------------------------------------|------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 10 \[desktop apps only\]<br/>                                                    |
| Minimum supported server<br/> | None supported<br/>                                                                      |
| Namespace<br/>                | Root\\cimv2\\mdm\\dmmap<br/>                                                             |
| MOF<br/>                      | <dl> <dt>DMWmiBridgeProv.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>DMWmiBridgeProv.dll</dt> </dl> |



## See also

<dl> <dt>

[Using PowerShell scripting with the WMI Bridge Provider](https://docs.microsoft.com/windows/client-management/mdm/using-powershell-scripting-with-the-wmi-bridge-provider)
</dt> </dl>

 

 





