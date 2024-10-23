# <a id="BT_Logger"></a> Class Logger

Namespace: [BT](BT.md)  
Assembly: BananasToolbox.dll  

```csharp
public class Logger
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Logger](BT.Logger.md)

#### Inherited Members

[object.Equals\(object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), 
[object.ReferenceEquals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring)

## Constructors

### <a id="BT_Logger__ctor"></a> Logger\(\)

```csharp
public Logger()
```

## Fields

### <a id="BT_Logger_liveLogBuffer"></a> liveLogBuffer

```csharp
public readonly List<string> liveLogBuffer
```

#### Field Value

 [List](https://learn.microsoft.com/dotnet/api/system.collections.generic.list\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

## Methods

### <a id="BT_Logger_Debug_System_String_"></a> Debug\(string\)

Logs message of LogType.Debug

```csharp
public void Debug(string message)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="BT_Logger_Dispose"></a> Dispose\(\)

```csharp
public void Dispose()
```

### <a id="BT_Logger_Error_System_String_"></a> Error\(string\)

Logs message of LogType.Error

```csharp
public void Error(string message)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="BT_Logger_Log_System_String_"></a> Log\(string\)

Logs message of LogType.Info

```csharp
public void Log(string message)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="BT_Logger_Warning_System_String_"></a> Warning\(string\)

Logs message of LogType.Warning

```csharp
public void Warning(string message)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="BT_Logger_OnLogWrite"></a> OnLogWrite

Called when a message is logged. Passes the logged message in LogEventArgs.Message

```csharp
public event LogEventHandler OnLogWrite
```

#### Event Type

 [LogEventHandler](BT.LogEventHandler.md)

