---
title: JET_ENUMCOLUMN.cEnumColumnValue property  (Microsoft.Isam.Esent.Interop)
TOCTitle: 'cEnumColumnValue property '
ms:assetid: P:Microsoft.Isam.Esent.Interop.JET_ENUMCOLUMN.cEnumColumnValue
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.isam.esent.interop.jet_enumcolumn.cenumcolumnvalue(v=EXCHG.10)
ms:contentKeyID: 55103498
ms.date: 07/30/2014
ms.topic: article
f1_keywords:
- Microsoft.Isam.Esent.Interop.JET_ENUMCOLUMN.cEnumColumnValue
dev_langs:
- CSharp
- JScript
- VB
- other
api_name: 
- Microsoft.Isam.Esent.Interop.JET_ENUMCOLUMN.cEnumColumnValue
- Microsoft.Isam.Esent.Interop.JET_ENUMCOLUMN.get_cEnumColumnValue
- Microsoft.Isam.Esent.Interop.JET_ENUMCOLUMN.set_cEnumColumnValue
topic_type: 
- apiref
- kbSyntax
api_type: 
- Managed
api_location: 
- Microsoft.Isam.Esent.Interop.dll
ROBOTS: INDEX,FOLLOW

---

# JET_ENUMCOLUMN.cEnumColumnValue property

Gets the number of column values enumerated for the column. This member is only used if [err](dn335086\(v=exchg.10\).md) is not [ColumnSingleValue](hh557250\(v=exchg.10\).md).

**Namespace:**  [Microsoft.Isam.Esent.Interop](hh596136\(v=exchg.10\).md)  
**Assembly:**  Microsoft.Isam.Esent.Interop (in Microsoft.Isam.Esent.Interop.dll)

## Syntax

``` vb
'Declaration
Public Property cEnumColumnValue As Integer
    Get
    Friend Set
'Usage
Dim instance As JET_ENUMCOLUMN
Dim value As Integer

value = instance.cEnumColumnValue
```

``` csharp
public int cEnumColumnValue { get; internal set; }
```

#### Property value

Type: [System.Int32](https://docs.microsoft.com/dotnet/api/system.int32?redirectedfrom=MSDN)  

## See also

#### Reference

[JET_ENUMCOLUMN class](dn335081\(v=exchg.10\).md)

[JET_ENUMCOLUMN members](dn335133\(v=exchg.10\).md)

[Microsoft.Isam.Esent.Interop namespace](hh596136\(v=exchg.10\).md)

