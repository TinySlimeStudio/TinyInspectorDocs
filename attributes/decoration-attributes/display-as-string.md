---
description: >-
  DisplayAsString is used on any property, and displays a string in the
  inspector as text. Use this for when you want to show a string in the
  inspector, but not allow for any editing.
icon: square-quote
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

# Display as String

### <i class="fa-eye">:eye:</i>  Attribute Preview

{% columns fullWidth="false" %}
{% column width="50%" valign="middle" %}
<i class="fa-moon">:moon:</i>  Dark Theme

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/ComingSoon.png" alt="" width="347"><figcaption></figcaption></figure></div>
{% endcolumn %}

{% column width="50%" %}
<i class="fa-brightness">:brightness:</i>  Light Theme

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/ComingSoon.png" alt="" width="347"><figcaption></figcaption></figure></div>
{% endcolumn %}
{% endcolumns %}

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
