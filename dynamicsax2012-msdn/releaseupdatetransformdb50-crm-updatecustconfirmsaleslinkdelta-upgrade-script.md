﻿---
title: ReleaseUpdateTransformDB50_CRM.updateCustConfirmSalesLinkDelta Upgrade Script
TOCTitle: ReleaseUpdateTransformDB50_CRM.updateCustConfirmSalesLinkDelta Upgrade Script
ms:assetid: 13d6e949-7f35-679c-bf7c-e8a239e032e8
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ718494(v=AX.60)
ms:contentKeyID: 49706779
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateTransformDB50\_CRM.updateCustConfirmSalesLinkDelta Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateTransformDB50_CRM</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateCustConfirmSalesLinkDelta</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the delivery postal address in the CustConfirmSalesLink table.</p></td>
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
<td><p>CustConfirmSalesLink</p></td>
</tr>
</tbody>
</table>


## Remarks

This upgrade is required in order to uptake to the new logistics postal address model for Microsoft Dynamics AX 2012. The delivery postal address for the CustConfirmSalesLink table will be kept as a reference to the LogisticsPostalAddress record.

## Data Migration Section

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: Shadow_SalesTable_GAB</p></th>
<th><p>To Table: Shadow_CustConfirmSalesLink_GAB</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>DeliveryPostalAddress</p></td>
<td><p>DeliveryPostalAddress</p></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: Shadow_CustConfirmJour_GAB</p></th>
<th><p>To Table: Shadow_CustConfirmSalesLink_GAB</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>DeliveryPostalAddress</p></td>
<td><p>DeliveryPostalAddress</p></td>
</tr>
<tr class="even">
<td><p>DeliveryLocation</p></td>
<td><p>DeliveryLocation</p></td>
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
<td><p>CustConfirmSalesLink</p></td>
<td><p>DeliveryPostalAdress</p></td>
<td><p>LogisticsPostalAddressRecId</p></td>
</tr>
<tr class="even">
<td><p>CustConfirmSalesLink</p></td>
<td><p>DeliveryLocation</p></td>
<td><p>LogisticsLocationRecId</p></td>
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
<td><p>CustConfirmSalesLink</p></td>
<td><p>DeliveryAddress</p></td>
</tr>
</tbody>
</table>

  


