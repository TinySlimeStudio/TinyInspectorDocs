---
description: >-
  Constrains a numeric field to a defined range and wraps the value to the
  opposite limit when exceeded.
icon: bring-front
---

# Wrap

{% hint style="info" %}
This attribute can be used only with: <mark style="color:$primary;">**Numeric**</mark>
{% endhint %}

### <i class="fa-eye">:eye:</i> Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Zrzut ekranu 2026-02-19 020633.png" alt=""><figcaption></figcaption></figure></div>

<p align="center"><sup><mark style="color:$primary;">Wrap</mark></sup> <sup><mark style="color:$primary;">Attribute</mark> adds a Description to the Tooltip Informing About the Set Attributes</sup></p>

### <i class="fa-square-code">:square-code:</i> Code

```csharp
[Wrap(0, 100)]
public int WrappedValue1 = 20;

[Wrap(0, 100)]
public float WrappedValue2 = 50;

[Wrap(0, 100)]
public double WrappedValue3 = 80;
```

### <i class="fa-gears">:gears:</i> Parameters

<mark style="color:$danger;background-color:$danger;">**REQUIRED**</mark> <mark style="color:$info;">int / float / double</mark> **Min**\
<sup><mark style="color:$info;">Maximum value of the bar.<mark style="color:$info;"></sup>

<mark style="color:$danger;background-color:$danger;">**REQUIRED**</mark> <mark style="color:$info;">int / float / double</mark> **Max**\
<sup><mark style="color:$info;">Maximum value of the bar.<mark style="color:$info;"></sup>

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-02-24" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
