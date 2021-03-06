---
title: EN_ALIGNLTR notification code
description: Notifies a rich edit control's parent window that the paragraph direction has changed to left-to-right. A rich edit control sends this notification code in the form of a WM\_COMMAND message.
ms.assetid: 754ac2b5-bcec-487b-a1ab-b653f673830a
keywords:
- EN_ALIGNLTR notification code Windows Controls
topic_type:
- apiref
api_name:
- EN_ALIGNLTR
api_location:
- Richedit.h
api_type:
- HeaderDef
ms.topic: article
ms.date: 05/31/2018
---

# EN\_ALIGNLTR notification code

Notifies a rich edit control's parent window that the paragraph direction has changed to left-to-right. A rich edit control sends this notification code in the form of a [**WM\_COMMAND**](https://docs.microsoft.com/windows/desktop/menurc/wm-command) message.


```C++
EN_ALIGNLTR

    WPARAM wParam
    LPARAM lParam; 
```



## Parameters

<dl> <dt>

*wParam* 
</dt> <dd>

The [**LOWORD**](https://docs.microsoft.com/previous-versions/windows/desktop/legacy/ms632659(v=vs.85)) contains the identifier of the rich edit control. The [**HIWORD**](https://docs.microsoft.com/previous-versions/windows/desktop/legacy/ms632657(v=vs.85)) specifies the notification code.

</dd> <dt>

*lParam* 
</dt> <dd>

Handle to the rich edit control.

</dd> </dl>

## Return value

This notification code does not return a value.

## Requirements



|                                     |                                                                                       |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista \[desktop apps only\]<br/>                                        |
| Minimum supported server<br/> | Windows Server 2003 \[desktop apps only\]<br/>                                  |
| Header<br/>                   | <dl> <dt>Richedit.h</dt> </dl> |



## See also

<dl> <dt>

**Reference**
</dt> <dt>

[**EN\_ALIGNRTL**](en-alignrtl.md)
</dt> <dt>

**Other Resources**
</dt> <dt>

[**HIWORD**](https://docs.microsoft.com/previous-versions/windows/desktop/legacy/ms632657(v=vs.85))
</dt> <dt>

[**LOWORD**](https://docs.microsoft.com/previous-versions/windows/desktop/legacy/ms632659(v=vs.85))
</dt> <dt>

[**WM\_COMMAND**](https://docs.microsoft.com/windows/desktop/menurc/wm-command)
</dt> </dl>

 

 





