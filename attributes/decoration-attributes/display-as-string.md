---
description: >-
  Displays a property value as read-only text in the Inspector, without an
  editable field, useful for diagnostics and runtime information.
icon: square-quote
---

# Display as String

{% hint style="info" %}
This attribute can be used only with: <mark style="color:$primary;">**String**</mark>
{% endhint %}

### <i class="fa-eye">:eye:</i> Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Zrzut ekranu 2026-02-19 020507.png" alt=""><figcaption></figcaption></figure></div>

### <i class="fa-square-code">:square-code:</i> Code

```csharp
[DisplayAsString]
public string String1 = "Property Value";

[DisplayAsString(true)]
public string String2 = "Property Value";

[DisplayAsString(TinyIcon.Mail)]
public string String3 = "Property Value";

[DisplayAsString(true, TinyIcon.Ammo)]
public string String4 = "Property Value";
```

### <i class="fa-gears">:gears:</i> Parameters

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">bool</mark> **ShowPropertyLabel** <mark style="color:$info;">= false</mark>\
<sup><mark style="color:$info;">Bar height in pixels.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">TinyIcon</mark> **Icon** <mark style="color:$info;">= TinyIcon.None</mark>\
<sup><mark style="color:$info;">Bar height in pixels.<mark style="color:$info;"></sup>

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-02-24" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
