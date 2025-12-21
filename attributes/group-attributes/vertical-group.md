---
description: >-
  This attribuVerticalGroup is used to collect properties into a vertical group
  in the Inspector. On its own it does very little, but when combined with other
  groupste is not yet available at this time.
icon: up-down
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
---

# Vertical Group

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

### <i class="fa-rectangle-history-circle-user">:rectangle-history-circle-user:</i>  Change History

{% columns %}
{% column width="25%" %}
**Version 1.0.0a**
{% endcolumn %}

{% column width="75%" %}
* Attribute Added
{% endcolumn %}
{% endcolumns %}