﻿---
title: ReleaseUpdateDB60_HRM.updateHcmBenefit Upgrade Script
TOCTitle: ReleaseUpdateDB60_HRM.updateHcmBenefit Upgrade Script
ms:assetid: 8b88484a-20a4-ec08-310e-0d8b12fed4bb
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ736438(v=AX.60)
ms:contentKeyID: 49709627
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_HRM.updateHcmBenefit Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_HRM</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateHcmBenefit</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Inserts a record into the HcmBenefit table for every record in the HcmBenefitPlan table.</p></td>
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
<td><p>Human Resources</p></td>
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
<td><p>HcmBenefit</p></td>
</tr>
</tbody>
</table>


## Remarks

Every record that is inserted into the HcmBenefit table will link to the record that was inserted into the HcmBenefitOption table in the updateBenefitOption method. The ValidFrom field of every record that is inserted into the HcmBenefit table will be set to 1/1/1900 and the ValidTo field will be set to 12/31/2154 so that the upgraded records never expire.

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
<td><p>HcmBenefit</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  


