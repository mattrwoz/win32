---
title: D3DX11CreateAsyncResourceLoader function
description: Note The D3DX (D3DX 9, D3DX 10, and D3DX 11) utility library is deprecated for Windows 8 and is not supported for Windows Store apps. See Remarks. Create an asynchronous-resource loader.
ms.assetid: b49900a1-866d-4a4a-bf3a-2deb9ce4a208
keywords:
- D3DX11CreateAsyncResourceLoader function Direct3D 11
topic_type:
- apiref
api_name:
- D3DX11CreateAsyncResourceLoader
api_location:
- D3DX11.lib
- D3DX11.dll
api_type:
- LibDef
ms.topic: article
ms.date: 05/31/2018
---

# D3DX11CreateAsyncResourceLoader function

> [!Note]  
> The D3DX (D3DX 9, D3DX 10, and D3DX 11) utility library is deprecated for Windows 8 and is not supported for Windows Store apps. See Remarks.

 

Create an asynchronous-resource loader.

## Syntax


```C++
HRESULT D3DX11CreateAsyncResourceLoader(
  _In_  HMODULE           hSrcModule,
  _In_  LPCTSTR           pSrcResource,
  _Out_ ID3DX11DataLoader **ppDataLoader
);
```



## Parameters

<dl> <dt>

*hSrcModule* \[in\]
</dt> <dd>

Type: **[**HMODULE**](https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types)**

Handle to the resource module. Use [GetModuleHandle Function](https://docs.microsoft.com/windows/desktop/api/libloaderapi/nf-libloaderapi-getmodulehandlea) to get the handle.

</dd> <dt>

*pSrcResource* \[in\]
</dt> <dd>

Type: **[**LPCTSTR**](https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types)**

Name of the resource in hSrcModule. If the compiler settings require Unicode, the data type LPCTSTR resolves to LPCWSTR. Otherwise, the data type resolves to LPCSTR.

</dd> <dt>

*ppDataLoader* \[out\]
</dt> <dd>

Type: **[**ID3DX11DataLoader**](id3dx11dataloader.md)\*\***

The address of a pointer to the asynchronous-data loader (see [**ID3DX11DataLoader Interface**](id3dx11dataloader.md)).

</dd> </dl>

## Return value

Type: **[**HRESULT**](https://msdn.microsoft.com/en-us/library/Bb401631(v=MSDN.10).aspx)**

The return value is one of the values listed in [Direct3D 11 Return Codes](d3d11-graphics-reference-returnvalues.md).

## Remarks

There s no implementation of the  async loader  outside of D3DX 10, and D3DX 11.

For Windows Store apps, the DirectX samples (for example, the [Direct3D tutorial sample](https://go.microsoft.com/fwlink/p/?linkid=255263)) include the **BasicLoader** module that uses the Windows Runtime asynchronous programming model ([**AsyncBase**](https://msdn.microsoft.com/en-us/library/BR244878(v=VS.110).aspx)).

For Win32 desktop apps, you can use the [Concurrency Runtime](https://msdn.microsoft.com/en-us/library/Ee207192(v=VS.100).aspx) to implement something similar to the Windows Runtime asynchronous programming model.

## Requirements



|                    |                                                                                          |
|--------------------|------------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>D3DX11async.h</dt> </dl> |
| Library<br/> | <dl> <dt>D3DX11.lib</dt> </dl>    |



## See also

<dl> <dt>

[D3DX Functions](d3d11-graphics-reference-d3dx11-functions.md)
</dt> </dl>

 

 





