---
description: >-
  Draws a horizontal progress bar based on the value of the property. Use it for
  displaying a meter to indicate how full an inventory is, or to make a visual
  indication of a health bar.
icon: bars-progress
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

# Progress Bar

### <i class="fa-eye">:eye:</i>  Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/ProgressBar.png" alt=""><figcaption></figcaption></figure></div>

<p align="center"><sup><mark style="color:$primary;">Progress Bar Attribute</mark> uses the color settings from the Color Palette Window</sup> <sup>to customize the appearance.</sup></p>

### <i class="fa-square-code">:square-code:</i>  Code

```csharp
[ProgressBar(0, 100)]
public int Defualt = 75;

[ProgressBar(0, 100, false)]
public float WithoutText = 75;

[ProgressBar(0, 100, TinyInspectorColor.Purple)]
public int CustomColor = 75;

[ProgressBar(0, 100, 32)]
public float CustomHeight = 75;

[ProgressBar(0, 100, 32, TinyInspectorColor.Orange)]
public int CustomHeightAndColor = 75;
```

