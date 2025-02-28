---
UID: NF:amvideo.COLORS
title: COLORS macro (amvideo.h)
description: The COLORS macro retrieves the palette entries from a VIDEOINFO structure.
helpviewer_keywords: ["COLORS","COLORS function [DirectShow]","amvideo/COLORS","dshow.colors"]
old-location: dshow\colors.htm
tech.root: dshow
ms.assetid: 32541ee4-53ef-4f0a-b823-bb475a93a195
ms.date: 4/26/2023
ms.keywords: COLORS, COLORS function [DirectShow], amvideo/COLORS, dshow.colors
req.header: amvideo.h
req.include-header: Streams.h
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Strmbase.lib (retail builds); Strmbasd.lib (debug builds)
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - COLORS
 - amvideo/COLORS
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - LibDef
api_location:
 - Strmbase.lib
 - Strmbase.dll
 - Strmbasd.lib
 - Strmbasd.dll
api_name:
 - COLORS
---

# COLORS macro


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The COLORS macro retrieves the palette entries from a <a href="/previous-versions/windows/desktop/api/amvideo/ns-amvideo-videoinfo">VIDEOINFO</a> structure.

## -parameters

### -param pbmi

Pointer to a <a href="/previous-versions/windows/desktop/api/amvideo/ns-amvideo-videoinfo">VIDEOINFO</a> structure.

## -remarks

This macro calculates the address as an offset from the start of the <a href="/windows/desktop/api/wingdi/ns-wingdi-bitmapinfoheader">BITMAPINFOHEADER</a> structure, using the value of <b>bmiHeader.biSize</b>. Make sure to initialize the <a href="/previous-versions/windows/desktop/api/amvideo/ns-amvideo-videoinfo">VIDEOINFO</a> structure before calling this macro.

## -see-also

<a href="/windows/desktop/DirectShow/video-and-image-functions">Video and Image Functions</a>