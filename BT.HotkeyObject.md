# <a id="BT_HotkeyObject"></a> Class HotkeyObject

Namespace: [BT](BT.md)  
Assembly: BananasToolbox.dll  

```csharp
public class HotkeyObject
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[HotkeyObject](BT.HotkeyObject.md)

#### Inherited Members

[object.Equals\(object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), 
[object.ReferenceEquals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring)

## Constructors

### <a id="BT_HotkeyObject__ctor_BT_KeyModifier___System_Windows_Forms_Keys_System_String_System_Int32_System_Func_System_Threading_Tasks_Task__"></a> HotkeyObject\(KeyModifier\[\], Keys, string, int, Func<Task\>\)

```csharp
public HotkeyObject(KeyModifier[] KeyMods, Keys HotKey, string pluginName, int pluginHotkeyID, Func<Task> callback)
```

#### Parameters

`KeyMods` [KeyModifier](BT.KeyModifier.md)\[\]

`HotKey` [Keys](https://learn.microsoft.com/dotnet/api/system.windows.forms.keys)

`pluginName` [string](https://learn.microsoft.com/dotnet/api/system.string)

`pluginHotkeyID` [int](https://learn.microsoft.com/dotnet/api/system.int32)

`callback` [Func](https://learn.microsoft.com/dotnet/api/system.func\-1)<[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)\>

## Fields

### <a id="BT_HotkeyObject_HotKey"></a> HotKey

```csharp
public Keys HotKey
```

#### Field Value

 [Keys](https://learn.microsoft.com/dotnet/api/system.windows.forms.keys)

### <a id="BT_HotkeyObject_KeyMods"></a> KeyMods

```csharp
public KeyModifier[] KeyMods
```

#### Field Value

 [KeyModifier](BT.KeyModifier.md)\[\]

### <a id="BT_HotkeyObject_callback"></a> callback

```csharp
public Func<Task> callback
```

#### Field Value

 [Func](https://learn.microsoft.com/dotnet/api/system.func\-1)<[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)\>

### <a id="BT_HotkeyObject_globalHotkeyID"></a> globalHotkeyID

```csharp
public int globalHotkeyID
```

#### Field Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="BT_HotkeyObject_pluginHotkeyID"></a> pluginHotkeyID

```csharp
public int pluginHotkeyID
```

#### Field Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="BT_HotkeyObject_pluginName"></a> pluginName

```csharp
public string pluginName
```

#### Field Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="BT_HotkeyObject_Equals_System_Object_"></a> Equals\(object?\)

Determines whether the specified object is equal to the current object.

```csharp
public override bool Equals(object? obj)
```

#### Parameters

`obj` [object](https://learn.microsoft.com/dotnet/api/system.object)?

The object to compare with the current object.

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

<a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/bool">true</a> if the specified object  is equal to the current object; otherwise, <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/bool">false</a>.

### <a id="BT_HotkeyObject_GetHashCode"></a> GetHashCode\(\)

Serves as the default hash function.

```csharp
public override int GetHashCode()
```

#### Returns

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

A hash code for the current object.

## Operators

### <a id="BT_HotkeyObject_op_Equality_BT_HotkeyObject_BT_HotkeyObject_"></a> operator ==\(HotkeyObject, HotkeyObject\)

```csharp
public static bool operator ==(HotkeyObject h1, HotkeyObject h2)
```

#### Parameters

`h1` [HotkeyObject](BT.HotkeyObject.md)

`h2` [HotkeyObject](BT.HotkeyObject.md)

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="BT_HotkeyObject_op_Inequality_BT_HotkeyObject_BT_HotkeyObject_"></a> operator \!=\(HotkeyObject, HotkeyObject\)

```csharp
public static bool operator !=(HotkeyObject h1, HotkeyObject h2)
```

#### Parameters

`h1` [HotkeyObject](BT.HotkeyObject.md)

`h2` [HotkeyObject](BT.HotkeyObject.md)

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

