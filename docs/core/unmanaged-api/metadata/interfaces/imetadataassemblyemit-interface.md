---
description: "Learn more about: IMetaDataAssemblyEmit Interface"
title: "IMetaDataAssemblyEmit Interface"
ms.date: "03/30/2017"
api_name:
  - "IMetaDataAssemblyEmit"
api_location:
  - "mscoree.dll"
api_type:
  - "COM"
f1_keywords:
  - "IMetaDataAssemblyEmit"
topic_type:
  - "apiref"
---
# IMetaDataAssemblyEmit Interface

Provides methods that support the self-description model used by the common language runtime to resolve and consume resources.

## Methods

| Method | Description |
|------------|-----------------|
|[DefineAssembly Method](imetadataassemblyemit-defineassembly-method.md)| Creates an assembly data structure containing metadata for the specified assembly, and returns the associated metadata token. |
|[DefineAssemblyRef Method](imetadataassemblyemit-defineassemblyref-method.md)| Creates an `AssemblyRef` structure containing metadata for the assembly that this assembly references, and returns the associated metadata token. |
|[DefineExportedType Method](imetadataassemblyemit-defineexportedtype-method.md)| Creates an `ExportedType` structure containing metadata for the specified exported type, and returns the associated metadata token. |
|[DefineFile Method](imetadataassemblyemit-definefile-method.md)| Creates a `File` metadata structure containing metadata for assembly referenced by this assembly, and returns the associated metadata token. |
|[DefineManifestResource Method](imetadataassemblyemit-definemanifestresource-method.md)| Creates a `ManifestResource` structure containing metadata for the specified manifest resource, and returns the associated metadata token. |
|[SetAssemblyProps Method](imetadataassemblyemit-setassemblyprops-method.md)| Modifies the specified `Assembly` metadata structure. |
|[SetAssemblyRefProps Method](imetadataassemblyemit-setassemblyrefprops-method.md)| Modifies the specified `AssemblyRef` metadata structure. |
|[SetExportedTypeProps Method](imetadataassemblyemit-setexportedtypeprops-method.md)| Modifies the specified `ExportedType` metadata structure. |
|[SetFileProps Method](imetadataassemblyemit-setfileprops-method.md)| Modifies the specified `File` metadata structure. |
|[SetManifestResourceProps Method](imetadataassemblyemit-setmanifestresourceprops-method.md)| Modifies the specified `ManifestResource` metadata structure. |

## Remarks

## Requirements

 **Platforms:** See [.NET supported operating systems](https://github.com/dotnet/core/blob/main/os-lifecycle-policy.md).

 **Header:** Cor.h

 **Library:** CorGuids.lib

## See also

- [Metadata Interfaces](metadata-interfaces.md)
- [IMetaDataAssemblyImport Interface](imetadataassemblyimport-interface.md)
