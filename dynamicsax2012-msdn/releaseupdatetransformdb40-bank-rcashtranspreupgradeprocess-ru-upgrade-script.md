﻿---
title: ReleaseUpdateTransformDB40_Bank.rCashTransPreUpgradeProcess_RU Upgrade Script
TOCTitle: ReleaseUpdateTransformDB40_Bank.rCashTransPreUpgradeProcess_RU Upgrade Script
ms:assetid: 713a3c40-f17c-15fb-d650-de8f001a779a
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ685795(v=AX.60)
ms:contentKeyID: 49708995
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateTransformDB40\_Bank.rCashTransPreUpgradeProcess\_RU Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateTransformDB40_Bank</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>rCashTransPreUpgradeProcess_RU</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Update ReportingCurrencyAmount, LedgerDimension, DefaultDimension, OffsetLedgerDimension, OffsetDefaultDimension, OffsetLedgerDimensionNum and OffsetLedgerDimensionNum fields in &lt;c&gt;RCashTrans&lt;/c&gt; table.</p></td>
</tr>
<tr class="even">
<td><p><strong>Script Type</strong></p></td>
<td><p>Preprocessing 60: Live</p></td>
</tr>
<tr class="odd">
<td><p><strong>Ax Version</strong></p></td>
<td><p>Microsoft Dynamics AX 4.0</p></td>
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
<td><p>Bank</p></td>
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
<td><p>RCashTrans</p></td>
</tr>
<tr class="even">
<td><p>Shadow_RCashTrans</p></td>
</tr>
</tbody>
</table>

  


