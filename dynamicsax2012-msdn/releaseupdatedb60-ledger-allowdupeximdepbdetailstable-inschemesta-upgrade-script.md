﻿---
title: ReleaseUpdateDB60_Ledger.allowDupEximDEPBDetailsTable_INSchemesTa Upgrade Script
TOCTitle: ReleaseUpdateDB60_Ledger.allowDupEximDEPBDetailsTable_INSchemesTa Upgrade Script
ms:assetid: 1ca99f4f-0d87-54cd-7d21-d87ecf326ea7
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ718715(v=AX.60)
ms:contentKeyID: 49706998
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Ledger.allowDupEximDEPBDetailsTable\_INSchemesTa Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Ledger</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>allowDupEximDEPBDetailsTable_INSchemesTa</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the SchemesTableProductGroupIdx index in the EximDEPBDetailsTable_IN table to allow duplicate records.</p></td>
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
<td><p>General ledger</p></td>
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
<td><p>EXIMDEPBDETAILSTABLE_IN</p></td>
</tr>
</tbody>
</table>


## Remarks

The ProductGroup field is replaced with the new EximProductGroupTable surrogate key field the SchemesTableProductGroupIdx index. Initially the EximProductGroupTable field contains no value. So the index is set to allow duplicates before the field is updated with the value of the RecId fields of the EximProductGroupTable\_IN table.

  


