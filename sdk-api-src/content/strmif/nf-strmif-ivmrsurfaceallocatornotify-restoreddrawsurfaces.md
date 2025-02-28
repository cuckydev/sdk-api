---
UID: NF:strmif.IVMRSurfaceAllocatorNotify.RestoreDDrawSurfaces
title: IVMRSurfaceAllocatorNotify::RestoreDDrawSurfaces (strmif.h)
description: The RestoreDDrawSurfaces method notifies the VMR that a DirectDraw surface &quot;loss&quot; has been detected.
helpviewer_keywords: ["IVMRSurfaceAllocatorNotify interface [DirectShow]","RestoreDDrawSurfaces method","IVMRSurfaceAllocatorNotify.RestoreDDrawSurfaces","IVMRSurfaceAllocatorNotify::RestoreDDrawSurfaces","IVMRSurfaceAllocatorNotifyRestoreDDrawSurfaces","RestoreDDrawSurfaces","RestoreDDrawSurfaces method [DirectShow]","RestoreDDrawSurfaces method [DirectShow]","IVMRSurfaceAllocatorNotify interface","dshow.ivmrsurfaceallocatornotify_restoreddrawsurfaces","strmif/IVMRSurfaceAllocatorNotify::RestoreDDrawSurfaces"]
old-location: dshow\ivmrsurfaceallocatornotify_restoreddrawsurfaces.htm
tech.root: dshow
ms.assetid: b62df5fb-6759-4869-a6b3-f78978e1f5e2
ms.date: 4/26/2023
ms.keywords: IVMRSurfaceAllocatorNotify interface [DirectShow],RestoreDDrawSurfaces method, IVMRSurfaceAllocatorNotify.RestoreDDrawSurfaces, IVMRSurfaceAllocatorNotify::RestoreDDrawSurfaces, IVMRSurfaceAllocatorNotifyRestoreDDrawSurfaces, RestoreDDrawSurfaces, RestoreDDrawSurfaces method [DirectShow], RestoreDDrawSurfaces method [DirectShow],IVMRSurfaceAllocatorNotify interface, dshow.ivmrsurfaceallocatornotify_restoreddrawsurfaces, strmif/IVMRSurfaceAllocatorNotify::RestoreDDrawSurfaces
req.header: strmif.h
req.include-header: Dshow.h
req.target-type: Windows
req.target-min-winverclnt: Windows XP with SP1 [desktop apps only]
req.target-min-winversvr: Windows Server 2003 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Strmiids.lib
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IVMRSurfaceAllocatorNotify::RestoreDDrawSurfaces
 - strmif/IVMRSurfaceAllocatorNotify::RestoreDDrawSurfaces
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Strmiids.lib
 - Strmiids.dll
api_name:
 - IVMRSurfaceAllocatorNotify.RestoreDDrawSurfaces
---

# IVMRSurfaceAllocatorNotify::RestoreDDrawSurfaces


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <code>RestoreDDrawSurfaces</code> method notifies the VMR that a DirectDraw surface "loss" has been detected.



## -returns

If the method succeeds, it returns S_OK. If it fails, it returns an error code.

## -see-also

<a href="/windows/desktop/api/strmif/nn-strmif-ivmrsurfaceallocatornotify">IVMRSurfaceAllocatorNotify Interface</a>



<a href="/windows/desktop/DirectShow/using-the-video-mixing-renderer">Using the Video Mixing Renderer</a>
