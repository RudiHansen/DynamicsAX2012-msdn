﻿---
title: ReleaseUpdateDB60_PBA.allowNoDupPBATreeSimpelPBANodeIdx
TOCTitle: ReleaseUpdateDB60_PBA.allowNoDupPBATreeSimpelPBANodeIdx
ms:assetid: 324a5bc9-feae-0c6d-76cf-d2970abca07a
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ685068(v=AX.60)
ms:contentKeyID: 49707522
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_PBA.allowNoDupPBATreeSimpelPBANodeIdx 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_PBA</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>allowNoDupPBATreeSimpelPBANodeIdx</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Restores the unique &lt;c&gt;PBANodeIdx&lt;/c&gt; index of the &lt;c&gt;PBATreeSimpel&lt;/c&gt; table.</p></td>
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
<td><p>Product Builder</p></td>
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
<td><p>SqlDictionary</p></td>
</tr>
<tr class="even">
<td><p>SysConfig</p></td>
</tr>
<tr class="odd">
<td><p>SysInfolog</p></td>
</tr>
<tr class="even">
<td><p>SysSetupLog</p></td>
</tr>
</tbody>
</table>


## Remarks

As the \<c\>PBANodeIdx\</c\> index changed fields between AX 5.0 and 6.0, the upgrade process requires the index to be marked as non-unique during the upgrade and restored afterwards.

  


