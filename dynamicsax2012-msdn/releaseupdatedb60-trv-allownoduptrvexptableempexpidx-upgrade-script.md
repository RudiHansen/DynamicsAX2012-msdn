﻿---
title: ReleaseUpdateDB60_Trv.allowNoDupTrvExpTableEmpExpIdx Upgrade Script
TOCTitle: ReleaseUpdateDB60_Trv.allowNoDupTrvExpTableEmpExpIdx Upgrade Script
ms:assetid: cebc278a-6928-abf6-b6b5-d78b9d4c0a9c
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ719753(v=AX.60)
ms:contentKeyID: 49711319
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Trv.allowNoDupTrvExpTableEmpExpIdx Upgrade Script 


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
<td><p>allowNoDupTrvExpTableEmpExpIdx</p></td>
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
<td><p>TrvExpTable</p></td>
</tr>
</tbody>
</table>


## Remarks

Resets EmpExpIdx index to not allow for duplicate records in the CreatingWorker, LegalEntity, and ExpNumber field combination.

  


