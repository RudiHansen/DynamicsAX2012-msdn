﻿---
title: ReleaseUpdateDB41_Cust.updateCustSettlementClose_W Upgrade Script
TOCTitle: ReleaseUpdateDB41_Cust.updateCustSettlementClose_W Upgrade Script
ms:assetid: b9076b1c-8c05-f38a-a9d3-f5cebf836105
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ737087(v=AX.60)
ms:contentKeyID: 49710769
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB41\_Cust.updateCustSettlementClose\_W Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB41_Cust</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateCustSettlementClose_W</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Corrects the TransDate field in the CustSettlement table, which has been posted as correction of unrealized exchange adjustment during periodic exchange adjustment operation GEERU and GEEW.</p></td>
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
<td><p>CustSettlement</p></td>
</tr>
</tbody>
</table>

  


