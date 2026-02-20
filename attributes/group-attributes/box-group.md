---
description: >-
  BoxGroup is applied to any property and places it inside a boxed section. Use
  it to neatly group related values in the Unity Inspector.
icon: box
---

# Box Group

### <i class="fa-eye">:eye:</i> Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Zrzut ekranu 2026-02-19 020306.png" alt=""><figcaption></figcaption></figure></div>

### <i class="fa-square-code">:square-code:</i> Code

```csharp
[BoxGroup("Base Box")]
public string Value1;

[BoxGroup("Base Box")]
public float Value2;

[BoxGroup("Base Box/Boxed", TinyIcon.Storm)]
public string BoxedValue1;

[BoxGroup("Colored", TinyColor.Red)]
public int ColoredBoxValue1;

// Variables do not have to be in the same order as BoxGroup
[BoxGroup("Base Box/Boxed")]
public float BoxedValue2;
```

### <i class="fa-gears">:gears:</i> Parameters

<mark style="color:$danger;background-color:$danger;">**REQUIRED**</mark> <mark style="color:$info;">string</mark> **GroupName**\
<sup><mark style="color:$info;">Maximum value of the bar.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">TinyIcon</mark> **Icon** <mark style="color:$info;">= TinyIcon.None</mark>\
<sup><mark style="color:$info;">Bar height in pixels.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">TinyColor</mark> **Color** <mark style="color:$info;">= TinyColor.Defualt</mark>\
<sup><mark style="color:$info;">Bar height in pixels.<mark style="color:$info;"></sup>

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-02-24" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
