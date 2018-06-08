﻿---
title: ReleaseUpdateDB60_Proj.allowDupProjRevenueSalesPriceProjCatEmpl Upgrade Script
TOCTitle: ReleaseUpdateDB60_Proj.allowDupProjRevenueSalesPriceProjCatEmpl Upgrade Script
ms:assetid: 29dab792-4bbd-1a52-f33e-d868ccb0d354
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ735901(v=AX.60)
ms:contentKeyID: 49707318
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Proj.allowDupProjRevenueSalesPriceProjCatEmpl Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Proj</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>allowDupProjRevenueSalesPriceProjCatEmpl</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the ProjCatEmplDateIdx index in the ProjRevenueSalesPrice table to allow for duplicate records.</p></td>
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
<td><p>Project</p></td>
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
<td><p>ProjRevenueSalesPrice</p></td>
</tr>
</tbody>
</table>


## Remarks

The EmplId field is replaced with the new Worker surrogate key field in the ProjCatEmplDateIdx unique index. Initially this field contains no value. So the index is set to allow for duplicates before the field is updated with the value of the record ID field of the HcmWorker table.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).
