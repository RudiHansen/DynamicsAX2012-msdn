﻿---
title: ReleaseUpdateDB60_Invent.allowNoDupInventProdComLineWithCodeKeyId
TOCTitle: ReleaseUpdateDB60_Invent.allowNoDupInventProdComLineWithCodeKeyId
ms:assetid: 90eeab28-f88e-e923-5924-21c870ba927e
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ736573(v=AX.60)
ms:contentKeyID: 49709760
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Invent.allowNoDupInventProdComLineWithCodeKeyId 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Invent</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>allowNoDupInventProdComLineWithCodeKeyId</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the index &lt;c&gt;KeyIdx&lt;/c&gt; in the table &lt;c&gt;InventProdComLineWithCode&lt;/c&gt; not to allow duplicate records.</p></td>
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
<td><p>Inventory management</p></td>
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
<td><p>InventProdComLineWithCode</p></td>
</tr>
</tbody>
</table>


## Remarks

Truncated method name from allowNoDupInventProdComLineWithCodeKeyIdx. After updating the surrogate key field InventProdComTable with the value of the RecId field of the table InventProdComTable, the index KeyIdx is reset not to allow duplicate records.

  


