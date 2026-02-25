---
description: >-
  Replaces the default boolean field with a styled switch control that supports
  custom on/off labels and color styling.
icon: toggle-large-on
---

# Switch

{% hint style="info" %}
This attribute can be used only with: <mark style="color:$primary;">**Bool**</mark>
{% endhint %}

### <i class="fa-eye">:eye:</i> Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Zrzut ekranu 2026-02-19 020711.png" alt=""><figcaption></figcaption></figure></div>

### <i class="fa-square-code">:square-code:</i> Code

```csharp
[Switch]
public bool Defualt;

[Switch(Expand: true)]
public bool Expanded;

[Switch("Custom OFF", "Custom ON")]
public bool Labels;

[Switch("Custom OFF", "Custom ON", Expand: true)]
public bool LabelsAndExpanded;

[Switch(TinyColor.Red)]
public bool Color;

[Switch(TinyColor.Green, Expand: true)]
public bool ColorAndExpanded;
```

### <i class="fa-gears">:gears:</i> Parameters

<mark style="color:$warning;background-color:$warning;">**REQUIRED**</mark> <mark style="color:$info;">string</mark> **LabelWhenOn** <mark style="color:$info;">= "ON"</mark>\
<sup><mark style="color:$info;">Label displayed when the value is true.<mark style="color:$info;"></sup>

<mark style="color:$warning;background-color:$warning;">**REQUIRED**</mark> <mark style="color:$info;">string</mark> **LabelWhenOFF** <mark style="color:$info;">= "OFF"</mark>\
<sup><mark style="color:$info;">Label displayed when the value is false.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">TinyColor</mark> **Color** <mark style="color:$info;">= TinyColor.Defualt</mark>\
<sup><mark style="color:$info;">Optional color applied to the switch.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">bool</mark> **Expand** <mark style="color:$info;">= false</mark>\
<sup><mark style="color:$info;">If true, the switch expands to full width.<mark style="color:$info;"></sup>

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-02-25" %}
## Version 1.0.0b

* Added Missing Light Mode Support
{% endupdate %}

{% update date="2026-02-24" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
