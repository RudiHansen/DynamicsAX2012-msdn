﻿---
title: ReleaseUpdateDB60_Ledger.updateFiscalDocumentTypeModel_BR Upgrade Script
TOCTitle: ReleaseUpdateDB60_Ledger.updateFiscalDocumentTypeModel_BR Upgrade Script
ms:assetid: d90c6cb3-b33e-5aa4-e64a-ab3ce74dc14f
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ687131(v=AX.60)
ms:contentKeyID: 49711577
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Ledger.updateFiscalDocumentTypeModel\_BR Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Ledger</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateFiscalDocumentTypeModel_BR</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates &lt;c&gt;FiscalDocumentModel_BR&lt;/c&gt; field of &lt;c&gt;FiscalDocumentType_BR&lt;/c&gt; table.</p></td>
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
<td><p>FiscalDocumentType_BR</p></td>
</tr>
<tr class="even">
<td><p>DEL_TaxFiscalDocuUpgrade_BR</p></td>
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
<th><p>From Table: DEL_TaxFiscalDocuUpgrade_BR</p></th>
<th><p>To Table: FiscalDocumentType_BR</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>NewFiscalDocumentModel</p></td>
<td><p>FiscalDocumentModel</p></td>
</tr>
</tbody>
</table>

  


