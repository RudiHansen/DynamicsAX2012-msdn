﻿---
title: ReleaseUpdateDB60_Invent.updateInventPackMaterTrans Upgrade Script
TOCTitle: ReleaseUpdateDB60_Invent.updateInventPackMaterTrans Upgrade Script
ms:assetid: 7b91c10c-a359-78e4-f98c-48689cac7f03
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ719438(v=AX.60)
ms:contentKeyID: 49709229
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Invent.updateInventPackMaterTrans Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

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
<td><p>updateInventPackMaterTrans</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the LogisticsPostalAddress field of the InventPackagingMaterialTrans table with the corresponding values from the DeliveryPostalAddress field of the CustInvoiceTrans table.</p></td>
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
<td><p>InventPackagingMaterialTrans</p></td>
</tr>
</tbody>
</table>


## New Tables or Fields

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Table</p></th>
<th><p>Field</p></th>
<th><p>Extended Data Type</p>
<p>-or- Base Enum</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>InventPackagingMaterialTrans</p></td>
<td><p>LogisticsPostalAddress</p></td>
<td><p>RefRecId</p></td>
</tr>
</tbody>
</table>

  


