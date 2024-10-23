# <a id="BT_Base_OverlayHandler"></a> Class OverlayHandler

Namespace: [BT.Base](BT.Base.md)  
Assembly: BananasToolbox.dll  

```csharp
public class OverlayHandler
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[OverlayHandler](BT.Base.OverlayHandler.md)

#### Inherited Members

[object.Equals\(object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), 
[object.ReferenceEquals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring)

## Constructors

### <a id="BT_Base_OverlayHandler__ctor_System_Windows_Forms_Screen_System_Int32_"></a> OverlayHandler\(Screen, int\)

```csharp
public OverlayHandler(Screen screen, int FPS)
```

#### Parameters

`screen` [Screen](https://learn.microsoft.com/dotnet/api/system.windows.forms.screen)

`FPS` [int](https://learn.microsoft.com/dotnet/api/system.int32)

## Methods

### <a id="BT_Base_OverlayHandler_AddBrush_System_String_GameOverlay_Drawing_SolidBrush_"></a> AddBrush\(string, SolidBrush\)

```csharp
public void AddBrush(string key, SolidBrush brush)
```

#### Parameters

`key` [string](https://learn.microsoft.com/dotnet/api/system.string)

`brush` SolidBrush

### <a id="BT_Base_OverlayHandler_AddFont_System_String_GameOverlay_Drawing_Font_"></a> AddFont\(string, Font\)

```csharp
public void AddFont(string key, Font font)
```

#### Parameters

`key` [string](https://learn.microsoft.com/dotnet/api/system.string)

`font` Font

### <a id="BT_Base_OverlayHandler_DestroyGraphics_System_Object_GameOverlay_Windows_DestroyGraphicsEventArgs_"></a> DestroyGraphics\(object?, DestroyGraphicsEventArgs\)

```csharp
public virtual void DestroyGraphics(object? sender, DestroyGraphicsEventArgs e)
```

#### Parameters

`sender` [object](https://learn.microsoft.com/dotnet/api/system.object)?

`e` DestroyGraphicsEventArgs

### <a id="BT_Base_OverlayHandler_DrawGraphics_System_Object_GameOverlay_Windows_DrawGraphicsEventArgs_"></a> DrawGraphics\(object?, DrawGraphicsEventArgs\)

```csharp
public virtual void DrawGraphics(object? sender, DrawGraphicsEventArgs e)
```

#### Parameters

`sender` [object](https://learn.microsoft.com/dotnet/api/system.object)?

`e` DrawGraphicsEventArgs

### <a id="BT_Base_OverlayHandler_RemoveBrush_System_String_"></a> RemoveBrush\(string\)

```csharp
public void RemoveBrush(string key)
```

#### Parameters

`key` [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="BT_Base_OverlayHandler_RemoveFont_System_String_"></a> RemoveFont\(string\)

```csharp
public void RemoveFont(string key)
```

#### Parameters

`key` [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="BT_Base_OverlayHandler_Run"></a> Run\(\)

```csharp
public void Run()
```

### <a id="BT_Base_OverlayHandler_SetupGraphics_System_Object_GameOverlay_Windows_SetupGraphicsEventArgs_"></a> SetupGraphics\(object?, SetupGraphicsEventArgs\)

```csharp
public virtual void SetupGraphics(object? sender, SetupGraphicsEventArgs e)
```

#### Parameters

`sender` [object](https://learn.microsoft.com/dotnet/api/system.object)?

`e` SetupGraphicsEventArgs

