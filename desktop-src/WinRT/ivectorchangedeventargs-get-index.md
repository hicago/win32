﻿---
Description: 'Gets the position in the vector where the change occurred.'
ms.assetid: '00756d77-aae0-45f0-8bd4-cf68af9bdc7c'
title: 'IVectorChangedEventArgs::get\_Index method'
---

# IVectorChangedEventArgs::get\_Index method

Gets the position in the vector where the change occurred.

## Syntax


```C++
HRESULT get_Index(
  [out, retval] unsigned *value
);
```



## Parameters

<dl> <dt>

*value* \[out, retval\]
</dt> <dd>

Type: **unsigned\***

The zero-based position in the vector where the change occurred, if applicable.

</dd> </dl>

## Return value

Type: **HRESULT**

If this method succeeds, it returns **S\_OK**. Otherwise, it returns an **HRESULT** error code.

## Requirements



|                                     |                                                                                                      |
|-------------------------------------|------------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 8<br/>                                                                                 |
| Minimum supported server<br/> | Windows Server 2012<br/>                                                                       |
| Header<br/>                   | <dl> <dt>IVectorChangedEventArgs.h</dt> </dl> |



## See also

<dl> <dt>

[**IVectorChangedEventArgs**](ivectorchangedeventargs.md)
</dt> </dl>

 

 



