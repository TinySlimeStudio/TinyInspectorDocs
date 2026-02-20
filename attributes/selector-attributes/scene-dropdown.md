---
description: >-
  Displays a dropdown list containing all scenes included in the Build Settings,
  allowing you to select a scene asset safely without relying on string names or
  manual typing.
icon: map
---

# Scene Dropdown

{% hint style="info" %}
This attribute can be used only with: <mark style="color:$primary;">**String**</mark>, <mark style="color:$primary;">**Int**</mark>
{% endhint %}

### <i class="fa-eye">:eye:</i> Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Zrzut ekranu 2026-02-19 020610.png" alt=""><figcaption></figcaption></figure></div>

### <i class="fa-square-code">:square-code:</i> Code

```csharp
[SceneDropdown]
public string SceneName;

[SceneDropdown]
public int IntName;
```

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-02-24" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
