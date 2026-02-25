---
description: >-
  Displays a clickable button in the Inspector that allows you to execute a
  method directly without writing custom editor code.
icon: hand-point-down
---

# Button

{% hint style="info" %}
This attribute can be used only with: <mark style="color:$primary;">**Void**</mark>
{% endhint %}

### <i class="fa-eye">:eye:</i> Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Zrzut ekranu 2026-02-19 020727.png" alt=""><figcaption></figcaption></figure></div>

### <i class="fa-square-code">:square-code:</i> Code

```csharp
[Button("Base Button")]
public void SomeFunction()
{
    Debug.Log("Test");
}
[Button("Button (Custom Height)", 64)]
public void SomeFunction1() 
{
    Debug.Log("Test");
}
[Button("Button with Icon", Icon: TinyIcon.Add)]
public void SomeFunction2()
{
    Debug.Log("Test");
}
[Button("Colored Button", Color: TinyColor.Green)]
public void SomeFunction3()
{
    Debug.Log("Test");
}

[Button("Button with Attributes")]
public void SomeFunctionWithAttributes(string val1, int val2, bool var3)
{
    Debug.Log("Test");
}
```

### <i class="fa-gears">:gears:</i> Parameters

<mark style="color:$danger;background-color:$danger;">**REQUIRED**</mark> <mark style="color:$info;">string</mark> **Label**\
<sup><mark style="color:$info;">Custom text displayed on the button.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">float</mark> **Height** <mark style="color:$info;">= 32</mark>\
<sup><mark style="color:$info;">Button height in pixels.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">TinyIcon</mark> **Icon** <mark style="color:$info;">= TinyIcon.None</mark>\
<sup><mark style="color:$info;">Optional icon displayed on the button.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">TinyColor</mark> **Color** <mark style="color:$info;">= TinyColor.Defualt</mark>\
<sup><mark style="color:$info;">Optional button color override.<mark style="color:$info;"></sup>

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-02-26" %}
## Version 1.0.0b

* Fix Missing Icon & Color
* Improved Label Detection
{% endupdate %}

{% update date="2026-02-24" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
