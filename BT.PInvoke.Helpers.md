# <a id="BT_PInvoke_Helpers"></a> Class Helpers

Namespace: [BT.PInvoke](BT.PInvoke.md)  
Assembly: BananasToolbox.dll  

```csharp
public class Helpers
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Helpers](BT.PInvoke.Helpers.md)

#### Inherited Members

[object.Equals\(object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), 
[object.ReferenceEquals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring)

## Fields

### <a id="BT_PInvoke_Helpers_GWL_EXSTYLE"></a> GWL\_EXSTYLE

```csharp
public const int GWL_EXSTYLE = -20
```

#### Field Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="BT_PInvoke_Helpers_SWP_FRAMECHANGED"></a> SWP\_FRAMECHANGED

```csharp
public const uint SWP_FRAMECHANGED = 32
```

#### Field Value

 [uint](https://learn.microsoft.com/dotnet/api/system.uint32)

### <a id="BT_PInvoke_Helpers_SWP_HIDEWINDOW"></a> SWP\_HIDEWINDOW

```csharp
public const uint SWP_HIDEWINDOW = 128
```

#### Field Value

 [uint](https://learn.microsoft.com/dotnet/api/system.uint32)

### <a id="BT_PInvoke_Helpers_SWP_NOACTIVATE"></a> SWP\_NOACTIVATE

```csharp
public const uint SWP_NOACTIVATE = 16
```

#### Field Value

 [uint](https://learn.microsoft.com/dotnet/api/system.uint32)

### <a id="BT_PInvoke_Helpers_SWP_NOCOPYBITS"></a> SWP\_NOCOPYBITS

```csharp
public const uint SWP_NOCOPYBITS = 256
```

#### Field Value

 [uint](https://learn.microsoft.com/dotnet/api/system.uint32)

### <a id="BT_PInvoke_Helpers_SWP_NOMOVE"></a> SWP\_NOMOVE

```csharp
public const uint SWP_NOMOVE = 2
```

#### Field Value

 [uint](https://learn.microsoft.com/dotnet/api/system.uint32)

### <a id="BT_PInvoke_Helpers_SWP_NOOWNERZORDER"></a> SWP\_NOOWNERZORDER

```csharp
public const uint SWP_NOOWNERZORDER = 512
```

#### Field Value

 [uint](https://learn.microsoft.com/dotnet/api/system.uint32)

### <a id="BT_PInvoke_Helpers_SWP_NOREDRAW"></a> SWP\_NOREDRAW

```csharp
public const uint SWP_NOREDRAW = 8
```

#### Field Value

 [uint](https://learn.microsoft.com/dotnet/api/system.uint32)

### <a id="BT_PInvoke_Helpers_SWP_NOSENDCHANGING"></a> SWP\_NOSENDCHANGING

```csharp
public const uint SWP_NOSENDCHANGING = 1024
```

#### Field Value

 [uint](https://learn.microsoft.com/dotnet/api/system.uint32)

### <a id="BT_PInvoke_Helpers_SWP_NOSIZE"></a> SWP\_NOSIZE

```csharp
public const uint SWP_NOSIZE = 1
```

#### Field Value

 [uint](https://learn.microsoft.com/dotnet/api/system.uint32)

### <a id="BT_PInvoke_Helpers_SWP_NOZORDER"></a> SWP\_NOZORDER

```csharp
public const uint SWP_NOZORDER = 4
```

#### Field Value

 [uint](https://learn.microsoft.com/dotnet/api/system.uint32)

### <a id="BT_PInvoke_Helpers_SWP_SHOWWINDOW"></a> SWP\_SHOWWINDOW

```csharp
public const uint SWP_SHOWWINDOW = 64
```

#### Field Value

 [uint](https://learn.microsoft.com/dotnet/api/system.uint32)

### <a id="BT_PInvoke_Helpers_WS_EX_CLIENTEDGE"></a> WS\_EX\_CLIENTEDGE

```csharp
public const int WS_EX_CLIENTEDGE = 512
```

#### Field Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

## Methods

### <a id="BT_PInvoke_Helpers_AllocConsole"></a> AllocConsole\(\)

```csharp
public static extern bool AllocConsole()
```

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="BT_PInvoke_Helpers_GetForegroundWindow"></a> GetForegroundWindow\(\)

```csharp
public static extern nint GetForegroundWindow()
```

#### Returns

 [nint](https://learn.microsoft.com/dotnet/api/system.intptr)

### <a id="BT_PInvoke_Helpers_GetWindowLong_System_IntPtr_System_Int32_"></a> GetWindowLong\(nint, int\)

```csharp
public static extern int GetWindowLong(nint hWnd, int nIndex)
```

#### Parameters

`hWnd` [nint](https://learn.microsoft.com/dotnet/api/system.intptr)

`nIndex` [int](https://learn.microsoft.com/dotnet/api/system.int32)

#### Returns

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="BT_PInvoke_Helpers_RegisterHotKey_System_IntPtr_System_Int32_System_Int32_System_Int32_"></a> RegisterHotKey\(nint, int, int, int\)

```csharp
public static extern bool RegisterHotKey(nint hWnd, int id, int fsModifiers, int vk)
```

#### Parameters

`hWnd` [nint](https://learn.microsoft.com/dotnet/api/system.intptr)

`id` [int](https://learn.microsoft.com/dotnet/api/system.int32)

`fsModifiers` [int](https://learn.microsoft.com/dotnet/api/system.int32)

`vk` [int](https://learn.microsoft.com/dotnet/api/system.int32)

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="BT_PInvoke_Helpers_SetForegroundWindow_System_IntPtr_"></a> SetForegroundWindow\(nint\)

```csharp
public static extern bool SetForegroundWindow(nint WindowHandle)
```

#### Parameters

`WindowHandle` [nint](https://learn.microsoft.com/dotnet/api/system.intptr)

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="BT_PInvoke_Helpers_SetWindowLong_System_IntPtr_System_Int32_System_Int32_"></a> SetWindowLong\(nint, int, int\)

```csharp
public static extern int SetWindowLong(nint hWnd, int nIndex, int dwNewLong)
```

#### Parameters

`hWnd` [nint](https://learn.microsoft.com/dotnet/api/system.intptr)

`nIndex` [int](https://learn.microsoft.com/dotnet/api/system.int32)

`dwNewLong` [int](https://learn.microsoft.com/dotnet/api/system.int32)

#### Returns

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="BT_PInvoke_Helpers_SetWindowPos_System_IntPtr_System_IntPtr_System_Int32_System_Int32_System_Int32_System_Int32_System_UInt32_"></a> SetWindowPos\(nint, nint, int, int, int, int, uint\)

```csharp
public static extern bool SetWindowPos(nint hWnd, nint hWndInsertAfter, int X, int Y, int cx, int cy, uint uFlags)
```

#### Parameters

`hWnd` [nint](https://learn.microsoft.com/dotnet/api/system.intptr)

`hWndInsertAfter` [nint](https://learn.microsoft.com/dotnet/api/system.intptr)

`X` [int](https://learn.microsoft.com/dotnet/api/system.int32)

`Y` [int](https://learn.microsoft.com/dotnet/api/system.int32)

`cx` [int](https://learn.microsoft.com/dotnet/api/system.int32)

`cy` [int](https://learn.microsoft.com/dotnet/api/system.int32)

`uFlags` [uint](https://learn.microsoft.com/dotnet/api/system.uint32)

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="BT_PInvoke_Helpers_UnregisterHotKey_System_IntPtr_System_Int32_"></a> UnregisterHotKey\(nint, int\)

```csharp
public static extern bool UnregisterHotKey(nint hWnd, int id)
```

#### Parameters

`hWnd` [nint](https://learn.microsoft.com/dotnet/api/system.intptr)

`id` [int](https://learn.microsoft.com/dotnet/api/system.int32)

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="BT_PInvoke_Helpers_WindowFromPoint_System_Drawing_Point_"></a> WindowFromPoint\(Point\)

```csharp
public static extern nint WindowFromPoint(Point p)
```

#### Parameters

`p` [Point](https://learn.microsoft.com/dotnet/api/system.drawing.point)

#### Returns

 [nint](https://learn.microsoft.com/dotnet/api/system.intptr)

