﻿---
title: ReleaseUpdateDB60_Vend.copyDuplicatePurchParmLine Upgrade Script
TOCTitle: ReleaseUpdateDB60_Vend.copyDuplicatePurchParmLine Upgrade Script
ms:assetid: 72b3bac2-b6b8-2af0-0cfc-0599fd251295
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ685829(v=AX.60)
ms:contentKeyID: 49709030
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Vend.copyDuplicatePurchParmLine Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Vend</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>copyDuplicatePurchParmLine</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Copies the duplicate rows from the PurchParmLine table to the VendInvoiceInfoLine table, row by row.</p></td>
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
<td><p>Accounts payable</p></td>
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
<td><p>MarkupTrans</p></td>
</tr>
<tr class="even">
<td><p>PurchParmLine</p></td>
</tr>
<tr class="odd">
<td><p>PurchParmLine_Asset</p></td>
</tr>
<tr class="even">
<td><p>PurchParmSubLine</p></td>
</tr>
<tr class="odd">
<td><p>PurchParmTable</p></td>
</tr>
<tr class="even">
<td><p>VendInvoiceInfoLine</p></td>
</tr>
<tr class="odd">
<td><p>VendInvoiceInfoLine_Asset</p></td>
</tr>
<tr class="even">
<td><p>VendInvoiceInfoSubLine</p></td>
</tr>
<tr class="odd">
<td><p>vendInvoiceMatchingLine</p></td>
</tr>
</tbody>
</table>


## Remarks

The duplicate data have the values in the ParmId, TableRefId, OrigPurchId, and LineNum fields.

  


