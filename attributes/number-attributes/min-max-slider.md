---
description: >-
  Limits a value using a single dual-handle slider, making it ideal for
  randomness ranges, clamps, and min–max constraints.
icon: sliders-simple
---

# Min Max Slider

{% hint style="info" %}
This attribute can be used only with: <mark style="color:$primary;">**Vector2**</mark>, <mark style="color:$primary;">**Vector2Int**</mark>
{% endhint %}

### <i class="fa-eye">:eye:</i> Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Zrzut ekranu 2026-02-19 020617.png" alt=""><figcaption></figcaption></figure></div>

<p align="center"><sup><mark style="color:$primary;">Min Max Slider</mark></sup> <sup><mark style="color:$primary;">Attribute</mark> adds a Description to the Tooltip Informing About the Set Attributes</sup></p>

### <i class="fa-square-code">:square-code:</i> Code

```csharp
[MinMaxSlider(0, 100)]
public Vector2Int Slider1 = new Vector2Int(25, 75);

[MinMaxSlider(0, 100)]
public Vector2 Slider2 = new Vector2(25, 75);
```

### <i class="fa-gears">:gears:</i> Parameters

<mark style="color:$danger;background-color:$danger;">**REQUIRED**</mark> <mark style="color:$info;">float</mark> **MinLimit**\
<sup><mark style="color:$info;">Maximum value of the bar.<mark style="color:$info;"></sup>

<mark style="color:$danger;background-color:$danger;">**REQUIRED**</mark> <mark style="color:$info;">float</mark> **MaxLimit**\
<sup><mark style="color:$info;">Maximum value of the bar.<mark style="color:$info;"></sup>

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-02-24" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
