---
description: >-
  Displays a live preview of the assigned asset directly in the Inspector,
  allowing quick inspection without opening separate windows.
icon: hexagon-image
---

# Preview Field

{% hint style="info" %}
This attribute can be used only with: <mark style="color:$primary;">**Object**</mark>, <mark style="color:$primary;">**Sprite**</mark>, <mark style="color:$primary;">**Texture**</mark>, <mark style="color:$primary;">**Component**</mark>, <mark style="color:$primary;">**Material**</mark>
{% endhint %}

### <i class="fa-eye">:eye:</i> Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/MinMaxSlider-Dark.png" alt=""><figcaption></figcaption></figure></div>

### <i class="fa-square-code">:square-code:</i> Code

```csharp
[PreviewField]
public Sprite SpritePreview;

[PreviewField(5)]
public Texture TexturePreview;

[PreviewField(false)]
public Material MaterialPreview;
```

### <i class="fa-gears">:gears:</i> Parameters

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">int</mark> **GridSize** <mark style="color:$info;">= 3</mark>\
<sup><mark style="color:$info;">Bar height in pixels.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">bool</mark> **ShowField** <mark style="color:$info;">= true</mark>\
<sup><mark style="color:$info;">Bar height in pixels.<mark style="color:$info;"></sup>

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-01-04" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
