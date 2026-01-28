---
description: >-
  Adds a description and documentation link to the script header in the
  Inspector, right next to the MonoBehaviour or ScriptableObject reference.
icon: subtitles
---

# Monoscript Info

{% hint style="info" %}
This attribute can be used only with: <mark style="color:$primary;">**MonoBehaviour**</mark>, <mark style="color:$primary;">**ScriptableObject**</mark>
{% endhint %}

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

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">string</mark> **Description** <mark style="color:$info;">= null</mark>\
<sup><mark style="color:$info;">Bar height in pixels.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">string</mark> **URLLink** <mark style="color:$info;">= null</mark>\
<sup><mark style="color:$info;">Bar height in pixels.<mark style="color:$info;"></sup>

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-01-04" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
