﻿---
title: MPI_Attr_delete function
TOCTitle: MPI_Attr_delete function
ms:assetid: 0e4d5d02-e4f7-49d5-b5e8-0a35addc0de0
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Dn473233(v=VS.85)
ms:contentKeyID: 59360779
ms.date: 03/28/2018
mtps_version: v=VS.85
f1_keywords:
- MPI_ATTR_DELETE
- mpif/MPI_Attr_delete
- mpi/MPI_ATTR_DELETE
dev_langs:
- C++
- C
---

# MPI\_Attr\_delete function

This function is deprecated in MPI-2 and removed from MPI-3. It is replaced by the [**MPI\_Comm\_delete\_attr**](mpi-comm-delete-attr-function.md) function.

## Syntax

``` c++
int
MPIAPI MPI_Attr_delete(
   MPI_Comm comm,
   int      keyval
);
```

## Parameters

  - *comm*  
    TBD

  - *keyval*  
    TBD

## Return value

TBD

## Fortran

    MPI_ATTR_DELETE(COMM, KEYVAL, IERROR)
        INTEGER COMM, KEYVAL, IERROR

## Requirements

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Product</p></td>
<td><p>HPC Pack 2012 MS-MPI Redistributable Package, HPC Pack 2008 R2 MS-MPI Redistributable Package, HPC Pack 2008 MS-MPI Redistributable Package or HPC Pack 2008 Client Utilities</p></td>
</tr>
<tr class="even">
<td><p>Header</p></td>
<td>Mpi.h;
Mpif.h</td>
</tr>
<tr class="odd">
<td><p>Library</p></td>
<td>Msmpi.lib</td>
</tr>
<tr class="even">
<td><p>DLL</p></td>
<td>Msmpi.dll</td>
</tr>
</tbody>
</table>


## See also

[MPI Miscellaneous Functions](mpi-miscellaneous-functions.md)

[**MPI\_Comm\_delete\_attr**](mpi-comm-delete-attr-function.md)
