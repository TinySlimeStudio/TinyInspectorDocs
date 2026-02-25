---
description: >-
  Overrides the default field label and optionally adds an icon for clearer or
  more descriptive Inspector layouts.
icon: font-case
---

# Custom Label

### <i class="fa-eye">:eye:</i> Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Zrzut ekranu 2026-02-19 020656.png" alt=""><figcaption></figcaption></figure></div>

### <i class="fa-square-code">:square-code:</i> Code

```csharp
[CustomLabel("Custom Label")]
public string Defualt;

[CustomLabel("Custom Label with Icon", TinyIcon.Computer)]
public string WithIcon;
```

### <i class="fa-gears">:gears:</i> Parameters

<mark style="color:$danger;background-color:$danger;">**REQUIRED**</mark> <mark style="color:$info;">string</mark> **Label**\
<sup><mark style="color:$info;">Custom label text.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">TinyIcon</mark> **Icon** <mark style="color:$info;">= TinyIcon.None</mark>\
<sup><mark style="color:$info;">Optional icon displayed next to the label.<mark style="color:$info;"></sup>

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-02-24" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
