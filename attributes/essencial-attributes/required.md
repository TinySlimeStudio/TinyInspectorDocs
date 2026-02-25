---
description: >-
  Displays a validation message in the Inspector when the field value is null or
  empty, making missing references or data immediately visible.
icon: hexagon-exclamation
---

# Required

{% hint style="info" %}
This attribute can be used only with: <mark style="color:$primary;">**ObjectReference**</mark>, <mark style="color:$primary;">**Array**</mark>, <mark style="color:$primary;">**List**</mark>, <mark style="color:$primary;">**String**</mark>, <mark style="color:$primary;">**Integer**</mark>, <mark style="color:$primary;">**Float**</mark>, <mark style="color:$primary;">**Bool**</mark>
{% endhint %}

### <i class="fa-eye">:eye:</i> Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Zrzut ekranu 2026-02-19 020814.png" alt=""><figcaption></figcaption></figure></div>

### <i class="fa-square-code">:square-code:</i> Code

```csharp
[Required]
public GameObject Error;

[Required(false)]
public GameObject Warning;
```

### <i class="fa-gears">:gears:</i> Parameters

<mark style="color:$warning;background-color:$warning;">**REQUIRED**</mark> <mark style="color:$info;">bool</mark> **IsRequired**\
<sup><mark style="color:$info;">Enables or disables the required validation check.<mark style="color:$info;"></sup>

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-02-24" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
