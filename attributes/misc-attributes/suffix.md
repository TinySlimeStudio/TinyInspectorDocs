---
description: >-
  Adds extra contextual information to a field by displaying a text or icon
  suffix next to it, optionally overlaid on the field itself.
icon: text-size
---

# Suffix

### <i class="fa-eye">:eye:</i> Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/MinMaxSlider-Dark.png" alt=""><figcaption></figcaption></figure></div>

### <i class="fa-square-code">:square-code:</i> Code

```csharp
[MinMaxSlider(0, 100)]
public Vector2Int IntType = new Vector2Int(25, 75);

[MinMaxSlider(0, 100)]
public Vector2 FloatType = new Vector2(25, 75);
```

### <i class="fa-gears">:gears:</i> Parameters

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">string</mark> **Label** <mark style="color:$info;">= null</mark>\
<sup><mark style="color:$info;">Bar height in pixels.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">TinyIcon</mark> **Icon** <mark style="color:$info;">= TinyIcon.None</mark>\
<sup><mark style="color:$info;">Bar height in pixels.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">bool</mark> **IsOverlay** <mark style="color:$info;">= true</mark>\
<sup><mark style="color:$info;">Bar height in pixels.<mark style="color:$info;"></sup>

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-01-04" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
