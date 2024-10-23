# <a id="BT_Plugins_PluginHandler"></a> Class PluginHandler

Namespace: [BT.Plugins](BT.Plugins.md)  
Assembly: BananasToolbox.dll  

```csharp
public class PluginHandler
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[PluginHandler](BT.Plugins.PluginHandler.md)

#### Inherited Members

[object.Equals\(object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), 
[object.ReferenceEquals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring)

## Properties

### <a id="BT_Plugins_PluginHandler_PluginStore"></a> PluginStore

```csharp
public static PluginList PluginStore { get; set; }
```

#### Property Value

 [PluginList](BT.Plugins.PluginList.md)

## Methods

### <a id="BT_Plugins_PluginHandler_Init"></a> Init\(\)

```csharp
public static void Init()
```

### <a id="BT_Plugins_PluginHandler_InitializePlugins"></a> InitializePlugins\(\)

```csharp
public static void InitializePlugins()
```

### <a id="BT_Plugins_PluginHandler_LoadPlugins_System_String_"></a> LoadPlugins\(string\)

```csharp
public static void LoadPlugins(string pluginFolderPath)
```

#### Parameters

`pluginFolderPath` [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="BT_Plugins_PluginHandler_ReloadPlugins"></a> ReloadPlugins\(\)

```csharp
public static void ReloadPlugins()
```

