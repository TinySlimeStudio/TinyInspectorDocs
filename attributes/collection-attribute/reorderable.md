---
description: >-
  Renders lists and arrays using a clean, modern layout with drag-and-drop
  reordering, making collection editing faster and more readable than the
  default Inspector view.
icon: rectangle-list
---

# Reorderable List

{% hint style="info" %}
This attribute can be used only with: <mark style="color:$primary;">**List**</mark>, <mark style="color:$primary;">**Array**</mark>
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

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-01-04" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
