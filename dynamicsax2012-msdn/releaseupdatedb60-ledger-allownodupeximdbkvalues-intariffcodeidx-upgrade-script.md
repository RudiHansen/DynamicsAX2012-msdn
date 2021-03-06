﻿---
title: ReleaseUpdateDB60_Ledger.allowNoDupEximDBKValues_INTariffCodeIdx Upgrade Script
TOCTitle: ReleaseUpdateDB60_Ledger.allowNoDupEximDBKValues_INTariffCodeIdx Upgrade Script
ms:assetid: 40e08b5f-960c-3b49-931a-9fc0c684e068
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ718810(v=AX.60)
ms:contentKeyID: 49707854
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Ledger.allowNoDupEximDBKValues\_INTariffCodeIdx Upgrade Script 


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
<td><p>allowNoDupEximDBKValues_INTariffCodeIdx</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the TariffCodeIdx index in the EximDBKValues_IN table to not allow duplicate records.</p></td>
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
<td><p>EXIMDBKVALUES_IN</p></td>
</tr>
</tbody>
</table>


## Remarks

After updating the CustomsTariffCodeTable surrogate key fields with the value of the RecId field of the tables, the TariffCodeIdx index is reset not to allow duplicate records.

  


