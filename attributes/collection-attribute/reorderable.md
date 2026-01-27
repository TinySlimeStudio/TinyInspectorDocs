---
description: >-
  Changes the display settings for collections. This attribute allows you to
  enhance the readability of rows, and create arrays where the element
  count/order cannot be changed from the Inspector.
icon: rectangle-list
---

# Reorderable

{% hint style="info" %}
This attribute can be used only with: <mark style="color:$primary;">**Vector2**</mark>, <mark style="color:$primary;">**Vector2Int**</mark>
{% endhint %}

### <i class="fa-eye">:eye:</i>  Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/MinMaxSlider-Dark.png" alt=""><figcaption></figcaption></figure></div>

<p align="center"><sup><mark style="color:$primary;">Min Max Slider</mark></sup> <sup><mark style="color:$primary;">Attribute</mark> adds a Description to the Tooltip Informing About the Set Attributes</sup></p>

### <i class="fa-square-code">:square-code:</i>  Code

```csharp
[MinMaxSlider(0, 100)]
public Vector2Int IntType = new Vector2Int(25, 75);

[MinMaxSlider(0, 100)]
public Vector2 FloatType = new Vector2(25, 75);
```

### <i class="fa-gears">:gears:</i> Parameters

&#x20;  <mark style="color:$danger;background-color:$danger;">**REQUIRED**</mark>  <mark style="color:$info;">float</mark>**&#x20;Max**\
<sup><mark style="color:$info;">Maximum value of the bar.<mark style="color:$info;"></sup>

&#x20;  <mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark>  <mark style="color:$info;">float</mark> **Height** <mark style="color:$info;">= 16</mark>\
<sup><mark style="color:$info;">Bar height in pixels.<mark style="color:$info;"></sup>

### <i class="fa-list-timeline">:list-timeline:</i>  Change History

{% updates format="full" %}
{% update date="2026-01-04" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}

