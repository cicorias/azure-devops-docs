---
title: VSS/References/VSS.SDK.Interfaces IContributedTab API | Extensions for Azure DevOps Services
description: Data representation of iContributed tab.
ms.assetid: 18284bee-cdea-00d5-9d1f-21fa6189fd62
ms.technology: devops-ecosystem
generated: true
ms.author: chcomley
author: chcomley
ms.topic: article
monikerRange: '>= tfs-2017'
ms.date: 08/04/2016
---

# IContributedTab

Defined in vss.d.ts



### Members

* `isInvisible`: (context: any): boolean or IPromise&lt;boolean&gt;. Optional. Determines if this tab should be displayed

* `pageTitle`: string or IPromise&lt;string&gt; or (context: any): string or IPromise&lt;string&gt;. Page title, which is displayed above the list of Tabs

* `name`: string or IPromise&lt;string&gt; or (context: any): string or IPromise&lt;string&gt;. Name of the tab

* `title`: string or IPromise&lt;string&gt; or (context: any): string or IPromise&lt;string&gt;. Optional. Title text for the tab, i.e., the tooltip

* `uri`: string. URI to the page that this tab displays (i.e. in a frame)

* `updateContext`: (context: any): void or IPromise&lt;void&gt;. Function that is invoked when there is a new context available for the extension.

