﻿---
title: ReleaseUpdateDB41_Cust.updateCustSettlement_W Upgrade Script
TOCTitle: ReleaseUpdateDB41_Cust.updateCustSettlement_W Upgrade Script
ms:assetid: d839462c-9269-156c-83d3-98373de417d2
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ687089(v=AX.60)
ms:contentKeyID: 49711537
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB41\_Cust.updateCustSettlement\_W Upgrade Script 


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
<td><p>updateCustSettlement_W</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Corrects the TransDate field in the CustSettlement table, which has been posted as reverse of unrealized exchange adjustment during settlement routine GEERU and GEEW.</p></td>
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

  


