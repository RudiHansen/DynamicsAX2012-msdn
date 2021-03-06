﻿---
title: ReleaseUpdateDB60_Basic.updateMappingBatch Upgrade Script
TOCTitle: ReleaseUpdateDB60_Basic.updateMappingBatch Upgrade Script
ms:assetid: ee144809-df8c-26af-c965-b000c0facd5a
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ719983(v=AX.60)
ms:contentKeyID: 49712055
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Basic.updateMappingBatch Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Basic</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateMappingBatch</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Adds table mapping for the Batch and BatchJob tables.</p></td>
</tr>
</tbody>
</table>


## Affected Modules and Tables

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Affected Modules</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Basic</p></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Affected Tables</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>ReleaseUpdateSpecialTableMapping</p></td>
</tr>
<tr class="even">
<td><p>Batch</p></td>
</tr>
<tr class="odd">
<td><p>BatchGroup</p></td>
</tr>
<tr class="even">
<td><p>BatchJob</p></td>
</tr>
<tr class="odd">
<td><p>BatchConstraints</p></td>
</tr>
<tr class="even">
<td><p>DEL_Batch50</p></td>
</tr>
<tr class="odd">
<td><p>DEL_BatchGroup50</p></td>
</tr>
<tr class="even">
<td><p>DEL_BatchJob</p></td>
</tr>
<tr class="odd">
<td><p>DEL_BatchConstraints</p></td>
</tr>
</tbody>
</table>


## Data Migration Section

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: Batch</p></th>
<th><p>To Table: DEL_Batch50</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: BatchGroup</p></th>
<th><p>To Table: DEL_BatchGroup50</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: BatchJob</p></th>
<th><p>To Table: DEL_BatchJob</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: BatchConstraints</p></th>
<th><p>To Table: DEL_BatchConstraints</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  


