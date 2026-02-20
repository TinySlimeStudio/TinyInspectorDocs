---
description: >-
  Creates a multiline text area with configurable height and optional character
  limit for flexible inspector input.
icon: message-text
---

# Multiline Text Area

{% hint style="info" %}
This attribute can be used only with: <mark style="color:$primary;">**String**</mark>
{% endhint %}

### <i class="fa-eye">:eye:</i> Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Zrzut ekranu 2026-02-19 020515.png" alt=""><figcaption></figcaption></figure></div>

### <i class="fa-square-code">:square-code:</i> Code

```csharp
[MultilineTextArea(3)]
public string Multiline1;

[MultilineTextArea(6, 300)]
public string Multiline2;

[MultilineTextArea(4, fullWidth: true)]
public string Multiline3;
```

### <i class="fa-gears">:gears:</i> Parameters

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">int</mark> **Lines** <mark style="color:$info;">= 3</mark>\
<sup><mark style="color:$info;">Number of visible text lines. Minimum value is 1.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">int</mark> **MaxCharacter** <mark style="color:$info;">= -1</mark>\
<sup><mark style="color:$info;">Optional maximum number of allowed characters.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">bool</mark> **FullWidth** <mark style="color:$info;">= false</mark>\
<sup><mark style="color:$info;">If true, text area expand to use the full available inspector width.<mark style="color:$info;"></sup>

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-02-24" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
