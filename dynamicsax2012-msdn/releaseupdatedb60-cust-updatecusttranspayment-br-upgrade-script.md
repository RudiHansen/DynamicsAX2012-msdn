﻿---
title: ReleaseUpdateDB60_Cust.updateCustTransPayment_BR Upgrade Script
TOCTitle: ReleaseUpdateDB60_Cust.updateCustTransPayment_BR Upgrade Script
ms:assetid: 3d410c6d-a663-048c-3664-7855994aefe6
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ718736(v=AX.60)
ms:contentKeyID: 49707781
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Cust.updateCustTransPayment\_BR Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Cust</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateCustTransPayment_BR</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the EPPaymentType_BR and EPPaymentWay_BR fields from the CustTrans table to the CustTransPayment_BR table.</p></td>
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
<td><p>CustTransPayment_BR</p></td>
</tr>
</tbody>
</table>


## Data Migration Section

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: CustTrans</p></th>
<th><p>To Table: CustTransPayment_BR</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>RecId</p></td>
<td><p>CustTrans</p></td>
</tr>
<tr class="even">
<td><p>DEL_EPPaymentType_BR</p></td>
<td><p>EPPaymentType_BR</p></td>
</tr>
<tr class="odd">
<td><p>DEL_PaymentWay_BR</p></td>
<td><p>EPPaymentWay_BR</p></td>
</tr>
</tbody>
</table>

  


