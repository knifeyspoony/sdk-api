---
UID: NF:rpcproxy.CStdStubBuffer2_Disconnect
title: CStdStubBuffer2_Disconnect function (rpcproxy.h)
description: Implements the IRpcStubBuffer::Disconnect method and disconnects the server object from the stub.
helpviewer_keywords: ["CStdStubBuffer2_Disconnect","CStdStubBuffer2_Disconnect function [RPC]","rpc.cstdstubbuffer2_disconnect","rpcproxy/CStdStubBuffer2_Disconnect"]
old-location: rpc\cstdstubbuffer2_disconnect.htm
tech.root: Rpc
ms.assetid: 5593A1C5-37B1-4A83-BEA3-F99AB82CF8FD
ms.date: 12/05/2018
ms.keywords: CStdStubBuffer2_Disconnect, CStdStubBuffer2_Disconnect function [RPC], rpc.cstdstubbuffer2_disconnect, rpcproxy/CStdStubBuffer2_Disconnect
req.header: rpcproxy.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 10 [desktop apps \| UWP apps]
req.target-min-winversvr: Windows Server 2016 [desktop apps \| UWP apps]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Ole32.lib
req.dll: Ole32.dll
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - CStdStubBuffer2_Disconnect
 - rpcproxy/CStdStubBuffer2_Disconnect
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - DllExport
api_location:
 - ole32.dll
 - API-MS-Win-Core-Com-MidlProxyStub-L1-1-0.dll
 - COMBase.dll
api_name:
 - CStdStubBuffer2_Disconnect
---

# CStdStubBuffer2_Disconnect function


## -description

<p class="CCE_Message">[CStdStubBuffer2_Disconnect is not supported and may be altered or unavailable in the future.]

Implements  the <a href="/windows/desktop/api/objidl/nf-objidl-irpcstubbuffer-disconnect">IRpcStubBuffer::Disconnect</a> method and disconnects the server object from the stub.

## -parameters

### -param pthis [in]

Pointer to  the <a href="/windows/desktop/api/objidl/nn-objidl-irpcstubbuffer">IRpcStubBuffer</a> object.

## -remarks

This function is used internally by proxies that are generated by MIDL.