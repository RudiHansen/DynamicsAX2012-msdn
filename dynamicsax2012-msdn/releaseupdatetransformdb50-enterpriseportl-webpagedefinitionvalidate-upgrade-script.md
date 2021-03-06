﻿---
title: ReleaseUpdateTransformDB50_EnterprisePortl.webPageDefinitionValidate Upgrade Script
TOCTitle: ReleaseUpdateTransformDB50_EnterprisePortl.webPageDefinitionValidate Upgrade Script
ms:assetid: c039c0be-ba76-14a6-f60f-5e095dabb2a3
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ686759(v=AX.60)
ms:contentKeyID: 49710957
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateTransformDB50\_EnterprisePortl.webPageDefinitionValidate Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateTransformDB50_EnterprisePortl</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>webPageDefinitionValidate</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Checks through the page definitions for use of webparts that are no longer supported in Microsoft Dynamics AX. Page definitions that still use these legacy webparts are logged so that they can be revised to use the new webparts.</p></td>
</tr>
<tr class="even">
<td><p><strong>Script Type</strong></p></td>
<td><p>Upgrade readiness scripts</p></td>
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
<td><p>Administration</p></td>
</tr>
<tr class="even">
<td><p>Basic</p></td>
</tr>
<tr class="odd">
<td><p>Expense management</p></td>
</tr>
<tr class="even">
<td><p>Human Resources</p></td>
</tr>
<tr class="odd">
<td><p>Production</p></td>
</tr>
<tr class="even">
<td><p>Service</p></td>
</tr>
<tr class="odd">
<td><p>SRM</p></td>
</tr>
</tbody>
</table>


<table xmlns="http://www.w3.org/1999/xhtml">
              <tr><th colspan="2">
		
   <p>
   
	 Validation Issues
  </p>
  </th></tr>
              <tr><td>
		
   <p>
   
	 
            Validation Issues Description
          
  </p>
  </td><td>
		
   <p>
   
	 There are Page Definitions that reference Webparts that are not supported in Microsoft Dynamics AX 2012. See detail messages for the list of Pages and Webparts. Revise each page to use the new Webparts.
  </p>
  </td></tr>
              <tr><td>
		
   <p>
   
	 
            Checked Conditions
          
  </p>
  </td><td>
		
   <p>
   
	 This script scans through page definitions in the AOT for use of webparts that are no longer supported in Microsoft Dynamics AX 2012.
  </p>
  </td></tr>
              <tr><td>
		
   <p>
   
	 
            Mitigation/How-to-fix
          
  </p>
  </td><td>
		
   <p>
   
	 Remove the references to the unsupported webparts and revise pages to use the new webparts.
  </p>
  </td></tr>
            </table>

  


