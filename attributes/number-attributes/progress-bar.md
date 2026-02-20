---
description: >-
  Replaces the default field with a progress bar, providing a clean and visual
  way to represent numeric values.
icon: bars-progress
---

# Progress Bar

{% hint style="info" %}
This attribute can be used only with: <mark style="color:$primary;">**Numeric**</mark>
{% endhint %}

### <i class="fa-eye">:eye:</i> Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Zrzut ekranu 2026-02-19 020625.png" alt=""><figcaption></figcaption></figure></div>

### <i class="fa-square-code">:square-code:</i> Code

```csharp
[ProgressBar(0, 100)]
public int Progress1 = 75;

[ProgressBar(0, 100, 32)]
public int Progress2 = 75;

[ProgressBar(0, 100, "Health", Color: TinyColor.Red, FullWidth = true)]
public int Progress3 = 75;

[ProgressBar(0, 100, ShowValue = false)]
public int Progress4 = 75;

[ProgressBar(0, 100, 32, ShowValueField = false)]
public int Progress5 = 75;
```

### <i class="fa-gears">:gears:</i> Parameters

<mark style="color:$danger;background-color:$danger;">**REQUIRED**</mark> <mark style="color:$info;">float</mark> **MinValue**\
<sup><mark style="color:$info;">Minimum value of the bar.<mark style="color:$info;"></sup>

<mark style="color:$danger;background-color:$danger;">**REQUIRED**</mark> <mark style="color:$info;">float</mark> **MaxValue**\
<sup><mark style="color:$info;">Maximum value of the bar.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">float</mark> **BarHeight** <mark style="color:$info;">= 16</mark>\
<sup><mark style="color:$info;">Bar height in pixels.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">float</mark> **BarText** <mark style="color:$info;">= null</mark>\
<sup><mark style="color:$info;">Optional text inside the bar.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">TinyColor</mark> **Color** <mark style="color:$info;">= TinyColor.Defualt</mark>\
<sup><mark style="color:$info;">Fill color of the bar.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">bool</mark> **ShowValueText** <mark style="color:$info;">= true</mark>\
<sup><mark style="color:$info;">Show value as text on the bar.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">bool</mark> **FullWidth** <mark style="color:$info;">= true</mark>\
<sup><mark style="color:$info;">Use full inspector width.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">bool</mark> **ShowValueField** <mark style="color:$info;">= true</mark>\
<sup><mark style="color:$info;">Show editable value field.<mark style="color:$info;"></sup>

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-02-24" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
