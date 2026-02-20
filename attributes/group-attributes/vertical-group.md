---
description: >-
  Collects properties into a vertical group, mainly used in combination with
  other group attributes to control layout structure.
icon: up-down
---

# Vertical Group

### <i class="fa-eye">:eye:</i> Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/MinMaxSlider-Dark.png" alt=""><figcaption></figcaption></figure></div>

### <i class="fa-square-code">:square-code:</i> Code

```csharp
[HorizontalGroup("Split")]

[VerticalGroup("Split/Left")]
[BoxGroup("Split/Left/Box 1")]
public string Box1Value;

[BoxGroup("Split/Left/Box 2")]
public string Box2Value;

[BoxGroup("Split/Right")]
public int RightValue1;
```

### <i class="fa-gears">:gears:</i> Parameters

<mark style="color:$danger;background-color:$danger;">**REQUIRED**</mark> <mark style="color:$info;">string</mark> **GroupName**\
<sup><mark style="color:$info;">Maximum value of the bar.<mark style="color:$info;"></sup>

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-02-24" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
