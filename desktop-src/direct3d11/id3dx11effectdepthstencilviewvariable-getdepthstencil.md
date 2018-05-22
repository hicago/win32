---
title: ID3DX11EffectDepthStencilViewVariable GetDepthStencil method
description: Get a depth-stencil-view resource.
ms.assetid: '7d94d98b-7070-41ee-9a9d-fe848f8914f2'
keywords: ["GetDepthStencil method Direct3D 11", "GetDepthStencil method Direct3D 11 , ID3DX11EffectDepthStencilViewVariable interface", "ID3DX11EffectDepthStencilViewVariable interface Direct3D 11 , GetDepthStencil method"]
topic_type:
- apiref
api_name:
- ID3DX11EffectDepthStencilViewVariable.GetDepthStencil
api_location:
- N/A
- N/A.dll
api_type:
- COM
---

# ID3DX11EffectDepthStencilViewVariable::GetDepthStencil method

Get a depth-stencil-view resource.

## Syntax


```C++
HRESULT GetDepthStencil(
  �ID3D11DepthStencilView **ppResource
);
```



## Parameters

<dl> <dt>

*ppResource* 
</dt> <dd>

Type: **[**ID3D11DepthStencilView**](id3d11depthstencilview.md)\*\***

The address of a pointer to a depth-stencil-view interface. See [**ID3D11DepthStencilView**](id3d11depthstencilview.md).

</dd> </dl>

## Return value

Type: **[**HRESULT**](455d07e9-52c3-4efb-a9dc-2955cbfd38cc)**

Returns one of the following [Direct3D 11 Return Codes](d3d11-graphics-reference-returnvalues.md).

## Remarks

> [!Note]  
> The DirectX SDK does not supply any compiled binaries for effects. You must use Effects 11 source to build your effects-type application. For more information about using Effects 11 source, see [Differences Between Effects 10 and Effects 11](d3d11-graphics-programming-guide-effects-differences.md).

�

## Requirements



|                    |                                                                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>D3dx11effect.h</dt> </dl>                                                    |
| Library<br/> | <dl> <dt>N/A (An Effects 11 library is available online as shared source.)</dt> </dl> |



## See also

<dl> <dt>

[ID3DX11EffectDepthStencilViewVariable](id3dx11effectdepthstencilviewvariable.md)
</dt> </dl>

�

�




