---
description: >-
  DisplayAsString is used on any property, and displays a string in the
  inspector as text. Use this for when you want to show a string in the
  inspector, but not allow for any editing.
icon: bring-front
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

# Wrap

### <i class="fa-eye">:eye:</i>  Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Wrap.png" alt=""><figcaption></figcaption></figure></div>

<p align="center"><sup><mark style="color:$primary;">Wrap Attribute</mark> adds a Description to the Tooltip Informing About the Set Attributes</sup></p>

### <i class="fa-square-code">:square-code:</i>  Code

```csharp
[DisplayAsString]
public string DisplayAsString1 = "DisplayAsString w/o Label";

[DisplayAsString(TinyIcon.Mana)] 
public string DisplayAsString3 = "DisplayAsString Icon w/o Label";

[DisplayAsString(true)] 
public string DisplayAsString2 = "DisplayAsString with Label";

[DisplayAsString(true, TinyIcon.Mana)] 
public string DisplayAsString4 = "DisplayAsString Icon with Label";
```
