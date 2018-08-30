﻿---
title: MPI_Info_delete function
TOCTitle: MPI_Info_delete function
ms:assetid: 059ee73a-7053-440f-9eb0-5b011a9cf640
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Dn473410(v=VS.85)
ms:contentKeyID: 59360946
ms.date: 03/28/2018
mtps_version: v=VS.85
f1_keywords:
- MPI_INFO_DELETE
- mpif/MPI_Info_delete
- mpi/MPI_INFO_DELETE
dev_langs:
- C++
- C
---

# MPI\_Info\_delete function

TBD

## Syntax

``` c++
int MPIAPI MPI_Info_delete(
       MPI_Info info,
  _In_ char     *key
);
```

## Parameters

  - *info*  
    TBD

  - *key* \[in\]  
    TBD

## Return value

TBD

## Fortran

    MPI_INFO_DELETE(INFO, KEY, IERROR)
        INTEGER INFO, IERROR
        CHARACTER*(*) KEY

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

[MPI Info Object Functions](mpi-info-object-functions.md)
