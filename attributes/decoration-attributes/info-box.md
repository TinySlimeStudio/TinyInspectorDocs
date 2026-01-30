---
description: >-
  Creates a customizable help box with title, message, and type, offering more
  control and styling options than Unity’s default help boxes.
icon: square-question
---

# Info Box

### <i class="fa-eye">:eye:</i> Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/MinMaxSlider-Dark.png" alt=""><figcaption></figcaption></figure></div>

### <i class="fa-square-code">:square-code:</i> Code

```csharp
[InfoBox("Title")]
public string InfoBox1;

[InfoBox("Title", "Long Message")]
public string InfoBox2;

[InfoBox("Title", InfoBoxType.None)]
public string InfoBox3;

[InfoBox("Title", "Long Message", InfoBoxType.Success)]
public string InfoBox4;
```

### <i class="fa-gears">:gears:</i> Parameters

<mark style="color:$danger;background-color:$danger;">**REQUIRED**</mark> <mark style="color:$info;">string</mark> **Title**\
<sup><mark style="color:$info;">Maximum value of the bar.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">string</mark> **Message** <mark style="color:$info;">= 16</mark>\
<sup><mark style="color:$info;">Bar height in pixels.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">InfoBoxType</mark> **Type** <mark style="color:$info;">= InfoBoxType.Info</mark>\
<sup><mark style="color:$info;">Bar height in pixels.<mark style="color:$info;"></sup>

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-01-04" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
