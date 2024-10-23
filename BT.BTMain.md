# <a id="BT_BTMain"></a> Class BTMain

Namespace: [BT](BT.md)  
Assembly: BananasToolbox.dll  

```csharp
public class BTMain : IBTMain
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BTMain](BT.BTMain.md)

#### Implements

[IBTMain](BT.IBTMain.md)

#### Inherited Members

[object.Equals\(object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), 
[object.ReferenceEquals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring)

## Fields

### <a id="BT_BTMain_Logger"></a> Logger

```csharp
public static Logger Logger
```

#### Field Value

 [Logger](BT.Logger.md)

## Properties

### <a id="BT_BTMain_CurrentMainForm"></a> CurrentMainForm

```csharp
public BTMainForm CurrentMainForm { get; }
```

#### Property Value

 [BTMainForm](BT.Forms.BTMainForm.md)

### <a id="BT_BTMain_MQTTHandler"></a> MQTTHandler

```csharp
public MQTTHandler MQTTHandler { get; set; }
```

#### Property Value

 [MQTTHandler](BT.MQTTHandler.md)

### <a id="BT_BTMain_OverlayHandler"></a> OverlayHandler

```csharp
public OverlayHandler OverlayHandler { get; }
```

#### Property Value

 [OverlayHandler](BT.OverlayHandler.md)

## Methods

### <a id="BT_BTMain_AddPluginOptionsForm_System_String_System_Windows_Forms_Form_"></a> AddPluginOptionsForm\(string, Form\)

```csharp
public void AddPluginOptionsForm(string pluginName, Form form)
```

#### Parameters

`pluginName` [string](https://learn.microsoft.com/dotnet/api/system.string)

`form` [Form](https://learn.microsoft.com/dotnet/api/system.windows.forms.form)

### <a id="BT_BTMain_ExitBT"></a> ExitBT\(\)

```csharp
public static void ExitBT()
```

### <a id="BT_BTMain_Init"></a> Init\(\)

```csharp
public void Init()
```

### <a id="BT_BTMain_MinimizeToTray"></a> MinimizeToTray\(\)

```csharp
public void MinimizeToTray()
```

### <a id="BT_BTMain_RegisterHotkey_BT_HotkeyObject_"></a> RegisterHotkey\(HotkeyObject\)

```csharp
public void RegisterHotkey(HotkeyObject hotkeyObject)
```

#### Parameters

`hotkeyObject` [HotkeyObject](BT.HotkeyObject.md)

### <a id="BT_BTMain_UnregisterHotkey_System_String_System_Int32_"></a> UnregisterHotkey\(string, int\)

```csharp
public void UnregisterHotkey(string pluginName, int pluginHotkeyID)
```

#### Parameters

`pluginName` [string](https://learn.microsoft.com/dotnet/api/system.string)

`pluginHotkeyID` [int](https://learn.microsoft.com/dotnet/api/system.int32)

