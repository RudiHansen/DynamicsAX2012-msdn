﻿---
title: ReleaseUpdateDB60_Trv.allowDupTrvKmSumEmplDateSats Upgrade Script
TOCTitle: ReleaseUpdateDB60_Trv.allowDupTrvKmSumEmplDateSats Upgrade Script
ms:assetid: 18940898-834f-3e5b-4b3a-4d21c67ebe16
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ718611(v=AX.60)
ms:contentKeyID: 49706895
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Trv.allowDupTrvKmSumEmplDateSats Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Trv</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>allowDupTrvKmSumEmplDateSats</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the EmpExpIdx index to allow for duplicate records.</p></td>
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
<td><p>Expense management</p></td>
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
<td><p>TrvKmSum</p></td>
</tr>
</tbody>
</table>


## Remarks

Sets the EmpExpIdx index to allow for duplicate records in the Worker field during the upgrade. This value is zero by default during the bulk copy. A post script populates this value and then the index is enabled.

  


