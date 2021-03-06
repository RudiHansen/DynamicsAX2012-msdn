﻿---
title: ReleaseUpdateDB60_Basic.deleteDupWorkflowTables Upgrade Script
TOCTitle: ReleaseUpdateDB60_Basic.deleteDupWorkflowTables Upgrade Script
ms:assetid: e3569227-9214-4dac-cad8-0324751ee5d0
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ737349(v=AX.60)
ms:contentKeyID: 49711790
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Basic.deleteDupWorkflowTables Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Basic</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>deleteDupWorkflowTables</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>This upgrade script recreates the unique indexes on the workflow and alert tables after the duplicate IDs have been resolved.</p></td>
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
<td><p>Basic</p></td>
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
<td><p>WorkflowElementTable</p></td>
</tr>
<tr class="even">
<td><p>WorkflowStepTable</p></td>
</tr>
<tr class="odd">
<td><p>WorkflowMessageText</p></td>
</tr>
<tr class="even">
<td><p>WorkflowVersionTableNotes</p></td>
</tr>
<tr class="odd">
<td><p>ExpressionTable</p></td>
</tr>
<tr class="even">
<td><p>EventRule</p></td>
</tr>
<tr class="odd">
<td><p>EventRuleData</p></td>
</tr>
<tr class="even">
<td><p>EventRuleField</p></td>
</tr>
<tr class="odd">
<td><p>EventRuleIgnore</p></td>
</tr>
<tr class="even">
<td><p>EventRuleRel</p></td>
</tr>
<tr class="odd">
<td><p>EventRuleRelData</p></td>
</tr>
</tbody>
</table>

  


