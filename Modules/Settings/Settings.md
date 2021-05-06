### Settings Overview

Settings are a usefull feature. They allow you to store any data (on runtime or editor). Unlike PlayerPrefs which cannot be edited without coding, here you can expose them to the Settings Module. 



There are four Methods in SettingsStore Class:

```csharp
 public static void SetSetting(bool showInSettings, string settingKey, object target)
```

```csharp
public static void SetSetting(string settingKey, object target)
```

These are available if you want to create [Custom Module]():

```csharp
public static void SetSetting(IFlexUiModule module, string settingKey, object target)
```

```csharp
public static void SetSetting(bool showInSettings, IFlexUiModule module, string settingKey, object target)
```


