﻿---
title: ReleaseUpdateDB60_Ledger.allowNoDupEximEntitlementDetails_IN
TOCTitle: ReleaseUpdateDB60_Ledger.allowNoDupEximEntitlementDetails_IN
ms:assetid: 0172cc76-4d7c-b633-b476-1187445ea614
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ684625(v=AX.60)
ms:contentKeyID: 49706322
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Ledger.allowNoDupEximEntitlementDetails\_IN 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

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
<td><p>allowNoDupEximEntitlementDetails_IN</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the SchemeLineProductGroupIdx index in the EximEntitlementDetails_IN table not to allow for duplicate records.</p></td>
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
<td><p>Ledger</p></td>
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
<td><p>EximEntitlementDetails_IN</p></td>
</tr>
</tbody>
</table>


## Remarks

After updating the surrogate key field of the EximProductGroupTable table with the RecId field of the table. The SchemeTableProductGroupIdx index is reset not to allow for duplicate records.

  


