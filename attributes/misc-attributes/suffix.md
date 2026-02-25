---
description: >-
  Adds extra contextual information to a field by displaying a text or icon
  suffix next to it, optionally overlaid on the field itself.
icon: text-size
---

# Suffix

### <i class="fa-eye">:eye:</i> Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Zrzut ekranu 2026-02-19 020641.png" alt=""><figcaption></figcaption></figure></div>

### <i class="fa-square-code">:square-code:</i> Code

```csharp
[Suffix("Suffix")]
public string Test;

[Suffix("Suffix", IsOverlay: false)]
public string TextSpacing;

[Suffix(Icon: TinyIcon.Audio)]
public string Icon;

[Suffix(Icon: TinyIcon.Download, IsOverlay: false)]
public string IconSpasing;

[Suffix("Suffix", TinyIcon.Audio)]
public string TextIcon;

[Suffix("Suffix", TinyIcon.Download, false)]
public string TextIconSpasing;
```

### <i class="fa-gears">:gears:</i> Parameters

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">string</mark> **Label** <mark style="color:$info;">= null</mark>\
<sup><mark style="color:$info;">Text displayed as the field suffix.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">TinyIcon</mark> **Icon** <mark style="color:$info;">= TinyIcon.None</mark>\
<sup><mark style="color:$info;">Optional icon displayed alongside the suffix.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">bool</mark> **IsOverlay** <mark style="color:$info;">= true</mark>\
<sup><mark style="color:$info;">If true, the suffix is rendered as an overlay.<mark style="color:$info;"></sup>

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-02-24" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
