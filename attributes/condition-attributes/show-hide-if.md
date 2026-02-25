---
description: >-
  ShowIf & HideIf is used on any property to control whether it is visible in
  the inspector, which shows relevant properties and hides those not based on
  the current state.
icon: eye
---

# Show / Hide IF

{% hint style="info" %}
This attribute can be used only with: <mark style="color:$primary;">**Vector2**</mark>, <mark style="color:$primary;">**Vector2Int**</mark>
{% endhint %}

### <i class="fa-eye">:eye:</i> Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Zrzut ekranu 2026-02-19 020736.png" alt=""><figcaption></figcaption></figure></div>

<p align="center"><sup><mark style="color:$primary;">Min Max Slider</mark></sup> <sup><mark style="color:$primary;">Attribute</mark> adds a Description to the Tooltip Informing About the Set Attributes</sup></p>

### <i class="fa-square-code">:square-code:</i> Code

```csharp
// Demo Purpose Only
public UnityEngine.Object SomeObject;
[EnumToggle] public TestEnum SomeEnum;
[Switch] public bool IsToggled;


[ShowIf("IsToggled")]
public string ShowWhenToggleOn;

[HideIf("IsToggled")]
public string HideWhenToggleOn;

[ShowIf("SomeObject")]
public string ShowWhenNotNull;

[HideIf("SomeObject")]
public string ShowWhenNull;

[ShowIf("SomeEnum", TestEnum.FirstOption)]
public string ShowOnlyWhenFirst;

[HideIf("SomeEnum", TestEnum.FirstOption)]
public string HideWhenFirst;

// Demo Purpose Only
public enum TestEnum
{
    FirstOption,
    SecondOption,
    ThirdOption
}
```

### <i class="fa-gears">:gears:</i> Parameters

<mark style="color:$danger;background-color:$danger;">**REQUIRED**</mark> <mark style="color:$info;">float</mark> **Max**\
<sup><mark style="color:$info;">Maximum value of the bar.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">float</mark> **Height** <mark style="color:$info;">= 16</mark>\
<sup><mark style="color:$info;">Bar height in pixels.<mark style="color:$info;"></sup>

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-02-24" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
