---
title: ActiveBasicDevice MaxVolume property
description: Gets the maximum volume supported by the device.
ms.assetid: EA0EC323-4A18-4CC1-8FA4-7BD302318863
keywords:
- MaxVolume property Media Streaming API
- MaxVolume property Media Streaming API , ActiveBasicDevice interface
- ActiveBasicDevice interface Media Streaming API , MaxVolume property
topic_type:
- apiref
api_name:
- ActiveBasicDevice.MaxVolume
- ActiveBasicDevice.get_MaxVolume
api_location:
- playtodevice.dll
api_type:
- COM
ms.topic: article
ms.date: 05/31/2018
---

# ActiveBasicDevice::MaxVolume property

Gets the maximum volume supported by the device.

This property is read-only.

## Syntax


```C++
HRESULT get_MaxVolume(
  [out] boolean *UINT32
);
```



## Property value

A pointer to a**UINT32** that specifies the maximum volume supported by the device.

## Requirements



|                                     |                                                                                             |
|-------------------------------------|---------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 8.1 \[desktop apps only\]<br/>                                                |
| Minimum supported server<br/> | Windows Server 2012 R2 \[desktop apps only\]<br/>                                     |
| Header<br/>                   | <dl> <dt>PlayToDevice.h</dt> </dl>   |
| IDL<br/>                      | <dl> <dt>PlayToDevice.idl</dt> </dl> |
| DLL<br/>                      | <dl> <dt>Playtodevice.dll</dt> </dl> |



## See also

<dl> <dt>

[**ActiveBasicDevice**](https://msdn.microsoft.com/en-us/library/Dn385755(v=VS.85).aspx)
</dt> </dl>

 

 





