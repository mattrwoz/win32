---
title: GatherCmpAlpha(S,float,float,uint) function
description: Samples a texture, tests the samples against a compare value, and returns the alpha component along with status about the operation.
ms.assetid: EA1D7176-3F70-4867-9854-80206A871B23
keywords:
- GatherCmpAlpha function HLSL
topic_type:
- apiref
api_name:
- GatherCmpAlpha
api_type:
- NA
ms.topic: article
ms.date: 05/31/2018
api_location: 
---

# GatherCmpAlpha(S,float,float,uint) function

Samples a texture, tests the samples against a compare value, and returns the alpha component along with status about the operation.

## Syntax


```C++
TemplateType GatherCmpAlpha(
  _In_  SamplerState S,
  _In_  float        Location,
  _In_  float        CompareValue,
  _Out_ uint         Status
);
```



## Parameters

<dl> <dt>

*S* \[in\]
</dt> <dd>

Type: **SamplerState**

The zero-based sampler index.

</dd> <dt>

*Location* \[in\]
</dt> <dd>

Type: **float**

The sample coordinates (u,v).

</dd> <dt>

*CompareValue* \[in\]
</dt> <dd>

Type: **float**

A value to compare each against each sampled value.

</dd> <dt>

*Status* \[out\]
</dt> <dd>

Type: **uint**

The status of the operation. You can't access the status directly; instead, pass the status to the [**CheckAccessFullyMapped**](checkaccessfullymapped.md) intrinsic function. **CheckAccessFullyMapped** returns **TRUE** if all values from the corresponding **Sample**, **Gather**, or **Load** operation accessed mapped tiles in a [tiled resource](https://docs.microsoft.com/windows/desktop/direct3d11/direct3d-11-2-features). If any values were taken from an unmapped tile, **CheckAccessFullyMapped** returns **FALSE**.

</dd> </dl>

## Return value

Type: **TemplateType**

A four-component value whose type is the same as the template type.

## Remarks

The texture samples can be used for bilinear interpolation.

This function is supported for the following types of shaders:



| Vertex | Hull | Domain | Geometry | Pixel | Compute |
|--------|------|--------|----------|-------|---------|
| x      | x    | x      | x        | x     | x       |



 

## See also

<dl> <dt>

[GatherCmpAlpha methods](texturecubearray-gathercmpalpha.md)
</dt> <dt>

[**TextureCubeArray**](texturecubearray.md)
</dt> </dl>

 

 




