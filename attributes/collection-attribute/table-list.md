---
description: >-
  Displays lists and arrays in a table-style layout, making structured data
  easier to scan, compare, and edit directly in the Inspector.
icon: table
---

# Table List

{% hint style="info" %}
This attribute can be used only with: <mark style="color:$primary;">**List**</mark>, <mark style="color:$primary;">**Array**</mark>
{% endhint %}

### <i class="fa-eye">:eye:</i> Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/background.png" alt=""><figcaption></figcaption></figure></div>

### <i class="fa-square-code">:square-code:</i> Code

```csharp
[TableList]
public List<ExampleCustomClass> CustomInlineClasses = new List<ExampleCustomClass>
{
    new ExampleCustomClass { Name = "First", Value = 1 },
    new ExampleCustomClass { Name = "Second", Value = 2 },
    new ExampleCustomClass { Name = "Third", Value = 3 }
};
```

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-02-24" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
