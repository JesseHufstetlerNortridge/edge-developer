---
title: DualEngine Win32 C++ VisibleListUpdateEntry
description: Represents a change to a travel log entry.
author: MSEdgeTeam
ms.author: msedgedevrel
ms.topic: conceptual
ms.service: microsoft-edge
ms.subservice: windows-integration
ms.date: 12/09/2023
keywords: dual engine, dualengine, iemode, win32 apps, win32, edge, ie mode, edge html, VisibleListUpdateEntry
topic_type: 
- APIRef
api_name:
- VisibleListUpdateEntry
- VisibleListUpdateEntry.fIsFrameEntry
- VisibleListUpdateEntry.operation
- VisibleListUpdateEntry.pszTitle
- VisibleListUpdateEntry.pszUrl
- VisibleListUpdateEntry.ulEntryId
api_type:
- COM
api_location:
- ieframe.dll
---

# struct VisibleListUpdateEntry

> [!IMPORTANT]
> The DualEngine API is a limited access feature. Contact dualengineapiaccess@microsoft.com for more information.

Represents a change to a travel log entry.

## Summary

 Members                        | Descriptions
--------------------------------|---------------------------------------------
[fIsFrameEntry](#fisframeentry) | Indicates whether the entry was for a subframe.
[operation](#operation) | The type of change.
[pszTitle](#psztitle) | The page title of the entry.
[pszUrl](#pszurl) | The URL of the entry.
[ulEntryId](#ulentryid) | The ID of the entry.

## Members

#### fIsFrameEntry

Indicates whether the entry was for a subframe.

> public BOOL [fIsFrameEntry](#fisframeentry)

#### operation

The type of change.

> public VisibleEntryUpdateOperation [operation](#operation)

#### pszTitle

The page title of the entry.

> public LPWSTR [pszTitle](#psztitle)

#### pszUrl

The URL of the entry.

> public LPWSTR [pszUrl](#pszurl)

#### ulEntryId

The ID of the entry.

> public ULONG [ulEntryId](#ulentryid)

