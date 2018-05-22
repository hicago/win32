---
title: IADsDNWithBinary Property Methods
description: The property method of the IADsDNWithBinary interface sets the property described in the following table. For more information, see Interface Property Methods.
audience: developer
author: REDMOND\\markl
manager: REDMOND\\mbaldwin
ms.assetid: '3e9ceabb-7a38-4a63-ab62-240ff521e373'
ms.prod: 'windows-server-dev'
ms.technology: 'active-directory-domain-services'
ms.tgt_platform: multiple
keywords: ["IADsDNWithBinary Property Methods ADSI"]
topic_type:
- apiref
api_name:
- IADsDNWithBinary Property Methods
- IADsDNWithBinary.BinaryValue
- IADsDNWithBinary.get_BinaryValue
- IADsDNWithBinary.put_BinaryValue
- IADsDNWithBinary.DNString
- IADsDNWithBinary.get_DNString
- IADsDNWithBinary.put_DNString
api_location:
- Activeds.dll
api_type:
- COM
---

# IADsDNWithBinary Property Methods

The property method of the [**IADsDNWithBinary**](iadsdnwithbinary.md) interface sets the property described in the following table. For more information, see [Interface Property Methods](interface-property-methods.md).

## Properties

<dl> <dt>

**BinaryValue**
</dt> <dd> <dl>

The GUID of an object associated with a DN.

<dt>

Access type: Read/write
</dt> <dt>

Scripting data type: **VARIANT**
</dt> <dt>



``` syntax
// C++ method syntax
HRESULT get_BinaryValue(
  [out] VARIANT* retVal
);
HRESULT put_BinaryValue(
  [in] VARIANT varBV
);
```


</dt> </dl> </dd> <dt>

**DNString**
</dt> <dd> <dl>

The DN string associated with the GUID of an object.

<dt>

Access type: Read/write
</dt> <dt>

Scripting data type: **BSTR**
</dt> <dt>



``` syntax
// C++ method syntax
HRESULT get_DNString(
  [out] BSTR* retval
);
HRESULT put_DNString(
  [in] BSTR bstrDN
);
```


</dt> </dl> </dd> </dl>

�

## Requirements



|                                     |                                                                                         |
|-------------------------------------|-----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows�Vista<br/>                                                                |
| Minimum supported server<br/> | Windows Server�2008<br/>                                                          |
| Header<br/>                   | <dl> <dt>Iads.h</dt> </dl>       |
| DLL<br/>                      | <dl> <dt>Activeds.dll</dt> </dl> |
| IID<br/>                      | IID\_IADsDNWithBinary is defined as 7E99C0A2-F935-11D2-BA96-00C04FB6D0D1<br/>     |



## See also

<dl> <dt>

[**IADsDNWithBinary**](iadsdnwithbinary.md)
</dt> <dt>

[**ADS\_DN\_WITH\_BINARY**](ads-dn-with-binary.md)
</dt> </dl>

�

�




