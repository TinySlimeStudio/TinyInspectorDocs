---
description: >-
  Renders enum values as a toggle grid instead of a dropdown, enabling faster
  selection and better visibility of all available options at once.
icon: grip
---

# Enum Toggle

{% hint style="info" %}
This attribute can be used only with: <mark style="color:$primary;">**Enum**</mark>
{% endhint %}

### <i class="fa-eye">:eye:</i> Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Zrzut ekranu 2026-02-19 020601.png" alt=""><figcaption></figcaption></figure></div>

### <i class="fa-square-code">:square-code:</i> Code

```csharp
[EnumToggle]
public SampleEnum EnumField;

[EnumToggle]
public SampleFlag FlagField;
```

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-02-24" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
