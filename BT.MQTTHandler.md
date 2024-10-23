# <a id="BT_MQTTHandler"></a> Class MQTTHandler

Namespace: [BT](BT.md)  
Assembly: BananasToolbox.dll  

```csharp
public class MQTTHandler
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[MQTTHandler](BT.MQTTHandler.md)

#### Inherited Members

[object.Equals\(object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), 
[object.ReferenceEquals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring)

## Properties

### <a id="BT_MQTTHandler_MqttClientLocal"></a> MqttClientLocal

```csharp
public MqttClient MqttClientLocal { get; }
```

#### Property Value

 MqttClient

### <a id="BT_MQTTHandler_MqttHost"></a> MqttHost

```csharp
public string MqttHost { get; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="BT_MQTTHandler_Connect_Client"></a> Connect\_Client\(\)

```csharp
public void Connect_Client()
```

### <a id="BT_MQTTHandler_Publish_System_String_System_String_"></a> Publish\(string, string\)

```csharp
public void Publish(string topic, string payload)
```

#### Parameters

`topic` [string](https://learn.microsoft.com/dotnet/api/system.string)

`payload` [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="BT_MQTTHandler_Subscribe_System_String_"></a> Subscribe\(string\)

```csharp
public void Subscribe(string topic)
```

#### Parameters

`topic` [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="BT_MQTTHandler_OnMqttReceive"></a> OnMqttReceive

```csharp
public event EventHandler<MqttMsg> OnMqttReceive
```

#### Event Type

 [EventHandler](https://learn.microsoft.com/dotnet/api/system.eventhandler\-1)<[MqttMsg](BT.MqttMsg.md)\>

