﻿---
title: ReleaseUpdateTransformDB40_Cust.salesOrderEntryStatDeltPreUpgradeProc Upgrade Script
TOCTitle: ReleaseUpdateTransformDB40_Cust.salesOrderEntryStatDeltPreUpgradeProc Upgrade Script
ms:assetid: c993f48d-6925-fd57-606f-1629515937bf
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ719622(v=AX.60)
ms:contentKeyID: 49711190
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateTransformDB40\_Cust.salesOrderEntryStatDeltPreUpgradeProc Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateTransformDB40_Cust</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>salesOrderEntryStatDeltPreUpgradeProc</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Transforms person data from the SalesResponsible field to the PersonSalesResponsible field in the SalesOrderEntryStatistics table.</p></td>
</tr>
<tr class="even">
<td><p><strong>Script Type</strong></p></td>
<td><p>Preprocessing 60: Delta</p></td>
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
<td><p>Accounts receivable</p></td>
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
<td><p>SalesOrderEntryStatistics</p></td>
</tr>
</tbody>
</table>


## Remarks

This upgrade converts employee data to a new HRM model.

## Data Migration Section

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: SalesOrderEntryStatistics</p></th>
<th><p>To Table: Shadow_SalesOrderEntryStatisticsHcmWrk</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>SalesResponsible</p></td>
<td><p>PersonSalesResponsible</p></td>
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
<td><p>Shadow_SalesOrderEntryStatisticsHcmWrk</p></td>
<td><p>PersonSalesResponsible</p></td>
<td><p>SalesResponsible</p></td>
</tr>
</tbody>
</table>


## Deleted Tables or Fields

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Table</p></th>
<th><p>Field</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>SalesOrderEntryStatistics</p></td>
<td><p>SalesResponsible</p></td>
</tr>
</tbody>
</table>

  


