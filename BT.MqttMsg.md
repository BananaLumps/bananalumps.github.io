# <a id="BT_MqttMsg"></a> Class MqttMsg

Namespace: [BT](BT.md)  
Assembly: BananasToolbox.dll  

```csharp
public class MqttMsg : EventArgs
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[MqttMsg](BT.MqttMsg.md)

#### Inherited Members

[EventArgs.Empty](https://learn.microsoft.com/dotnet/api/system.eventargs.empty), 
[object.Equals\(object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), 
[object.ReferenceEquals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring)

## Constructors

### <a id="BT_MqttMsg__ctor_System_String_System_String_"></a> MqttMsg\(string, string\)

```csharp
public MqttMsg(string topic, string msg)
```

#### Parameters

`topic` [string](https://learn.microsoft.com/dotnet/api/system.string)

`msg` [string](https://learn.microsoft.com/dotnet/api/system.string)

## Properties

### <a id="BT_MqttMsg_Msg"></a> Msg

```csharp
public string Msg { get; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="BT_MqttMsg_Topic"></a> Topic

```csharp
public string Topic { get; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

