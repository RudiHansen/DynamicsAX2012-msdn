﻿---
title: ReleaseUpdateDB60_Ledger.allowDupExciseNumSequenceRef_INExciseNum
TOCTitle: ReleaseUpdateDB60_Ledger.allowDupExciseNumSequenceRef_INExciseNum
ms:assetid: 02436c21-f9e2-ef7c-134a-8b29903b92ba
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ684641(v=AX.60)
ms:contentKeyID: 49706340
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Ledger.allowDupExciseNumSequenceRef\_INExciseNum 


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
<td><p>allowDupExciseNumSequenceRef_INExciseNum</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the index &lt;c&gt;ExciseNumRefIdx&lt;/c&gt; in the table &lt;c&gt;ExciseNumSequenceRef_IN&lt;/c&gt; to allow duplicate records.</p></td>
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
<td><p>EXCISENUMSEQUENCEREF_IN</p></td>
</tr>
</tbody>
</table>


## Remarks

The RegistrationNumber field is replaced with the new surrogate key field Reference and TaxRegistrationNumberTable in the unique index ExciseNumRefIdx. Initially the TaxRegistrationNumberTable field contains no value. So the index is set to allow duplicates before the field is updated with the value of the RecId fields of the table TaxRegistrationNumberTable\_IN.

  


