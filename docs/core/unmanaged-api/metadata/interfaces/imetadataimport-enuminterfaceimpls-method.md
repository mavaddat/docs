---
description: "Learn more about: IMetaDataImport::EnumInterfaceImpls Method"
title: "IMetaDataImport::EnumInterfaceImpls Method"
ms.date: "03/30/2017"
api_name:
  - "IMetaDataImport.EnumInterfaceImpls"
api_location:
  - "mscoree.dll"
api_type:
  - "COM"
f1_keywords:
  - "IMetaDataImport::EnumInterfaceImpls"
  - "EnumInterfaceImpls method [.NET metadata]"
topic_type:
  - "apiref"
---
# IMetaDataImport::EnumInterfaceImpls Method

Enumerates all interfaces implemented by the specified `TypeDef`.

## Syntax

```cpp
HRESULT EnumInterfaceImpls (
   [in, out]  HCORENUM       *phEnum,
   [in]   mdTypeDef          td,
   [out]  mdInterfaceImpl    rImpls[],
   [in]   ULONG              cMax,
   [out]  ULONG*             pcImpls
);
```

## Parameters

 `phEnum`
 [in, out] A pointer to the enumerator.

 `td`
 [in] The token of the TypeDef whose MethodDef tokens representing interface implementations are to be enumerated.

 `rImpls`
 [out] The array used to store the MethodDef tokens.

 `cMax`
 [in] The maximum length of the `rImpls` array.

 `pcImpls`
 [out] The actual number of tokens returned in `rImpls`.

## Return Value

| HRESULT | Description |
|-------------|-----------------|
| `S_OK` | `EnumInterfaceImpls` returned successfully. |
| `S_FALSE` | There are no MethodDef tokens to enumerate. In that case, `pcImpls` is set to zero. |

## Remarks

The enumeration returns a collection of `mdInterfaceImpl` tokens for each interface implemented by the specified `TypeDef`. Interface tokens are returned in the order the interfaces were specified (through `DefineTypeDef` or `SetTypeDefProps`). Properties of the returned `mdInterfaceImpl` tokens can be queried using [GetInterfaceImplProps](imetadataimport-getinterfaceimplprops-method.md).

## Requirements

 **Platforms:** See [.NET supported operating systems](https://github.com/dotnet/core/blob/main/os-lifecycle-policy.md).

 **Header:** Cor.h

 **Library:** CorGuids.lib

## See also

- [IMetaDataImport Interface](imetadataimport-interface.md)
- [IMetaDataImport2 Interface](imetadataimport2-interface.md)
