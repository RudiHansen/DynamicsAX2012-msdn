﻿---
title: ReleaseUpdateTransformDB50_Ledger.dimensionFocusPreProcessing Upgrade Script
TOCTitle: ReleaseUpdateTransformDB50_Ledger.dimensionFocusPreProcessing Upgrade Script
ms:assetid: 57dfad7f-bf46-7360-5f4a-23cb4c18d72a
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ736240(v=AX.60)
ms:contentKeyID: 49708415
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateTransformDB50\_Ledger.dimensionFocusPreProcessing Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateTransformDB50_Ledger</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>dimensionFocusPreProcessing</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Creates dimension focus records.</p></td>
</tr>
<tr class="even">
<td><p><strong>Script Type</strong></p></td>
<td><p>Preprocessing 60: Live</p></td>
</tr>
<tr class="odd">
<td><p><strong>Microsoft Dynamics AX Source</strong></p></td>
<td><p>Microsoft Dynamics AX 4.0</p>
<p>Microsoft Dynamics AX 2009</p></td>
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
<td><p>DimensionSetTable</p></td>
</tr>
<tr class="even">
<td><p>DimensionPriorityTable</p></td>
</tr>
</tbody>
</table>


## Remarks

Information from the DimensionSetTable and DimensionPriorityTable will be processed and added to the DimensionHierarchy, DimensionHierarchyLevel, and DimensionFocusState tables.

## Data Migration Section

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: DimensionSetTable</p></th>
<th><p>To Table: DimensionHierarchy</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>SetId</p></td>
<td><p>Name</p></td>
</tr>
<tr class="even">
<td><p>Description</p></td>
<td><p>Description</p></td>
</tr>
</tbody>
</table>

  


