---
title: Bluetooth and getsockopt
description: Bluetooth uses the getsockopt function to query various parameters associated with the server channel or the connection.
ms.assetid: '9593fd6c-b55d-45d8-a9d9-87ebcd09d1bd'
keywords: ["Bluetooth", "getsockopt", "Bluetooth and getsockopt"]
---

# Bluetooth and getsockopt

Bluetooth uses the [**getsockopt**](https://msdn.microsoft.com/library/windows/desktop/ms738544) function to query various parameters associated with the server channel or the connection. Use of **getsockopt** with Bluetooth has the following requirements:

-   The *s* parameter of [**getsockopt**](https://msdn.microsoft.com/library/windows/desktop/ms738544) must be a valid Bluetooth socket.
-   The *level* parameter of [**getsockopt**](https://msdn.microsoft.com/library/windows/desktop/ms738544) must be SOL\_RFCOMM.

For a listing of available Bluetooth socket options, see [Bluetooth and Socket Options](bluetooth-and-socket-options.md).

## Related topics

<dl> <dt>

[Windows Sockets](https://msdn.microsoft.com/library/windows/desktop/ms740673)
</dt> <dt>

[**getsockopt**](https://msdn.microsoft.com/library/windows/desktop/ms738544)
</dt> </dl>

 

 



