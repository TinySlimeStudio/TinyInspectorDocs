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
[Reorderable]
public List<string> StringList = new List<string> { "Item 1", "Item 2", "Item 3" };

[Reorderable]
public List<int> IntList = new List<int> { 10, 20, 30 };

[Reorderable]
public List<Vector3> Vector3List = new List<Vector3> 
{ 
    new Vector3(1, 2, 3), 
    new Vector3(4, 5, 6), 
    new Vector3(7, 8, 9) 
};

[Reorderable]
public List<ExampleCustomClass> CustomClasses = new List<ExampleCustomClass>
{
    new ExampleCustomClass { Name = "First", Value = 1 },
    new ExampleCustomClass { Name = "Second", Value = 2 },
    new ExampleCustomClass { Name = "Third", Value = 3 }
};

[Reorderable, InlineDrawer]
public List<ExampleCustomClass> CustomInlineClasses = new List<ExampleCustomClass>
{
    new ExampleCustomClass { Name = "First", Value = 1 },
    new ExampleCustomClass { Name = "Second", Value = 2 },
    new ExampleCustomClass { Name = "Third", Value = 3 }
};
```

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-01-04" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
