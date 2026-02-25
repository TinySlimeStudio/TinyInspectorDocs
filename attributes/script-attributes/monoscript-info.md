---
description: >-
  Adds a description and documentation link to the script header in the
  Inspector, right next to the MonoBehaviour or ScriptableObject reference.
icon: subtitles
---

# Monoscript Info

{% hint style="info" %}
This attribute can be used only with: <mark style="color:$primary;">**MonoBehaviour**</mark>, <mark style="color:$primary;">**ScriptableObject**</mark>
{% endhint %}

### <i class="fa-eye">:eye:</i> Attribute Preview

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Zrzut ekranu 2026-02-19 020822.png" alt=""><figcaption></figcaption></figure></div>

### <i class="fa-square-code">:square-code:</i> Code

```csharp
[Serializable, MonoscriptInfo("Script Description", "www.example.com")]
public class MonoscriptInfoExample : MonoBehaviour
{
    public string someValue;
}
```

### <i class="fa-gears">:gears:</i> Parameters

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">string</mark> **Description** <mark style="color:$info;">= null</mark>\
<sup><mark style="color:$info;">Text shown under the script name in the Inspector.<mark style="color:$info;"></sup>

<mark style="color:$primary;background-color:$primary;">**OPTIONAL**</mark> <mark style="color:$info;">string</mark> **URLLink** <mark style="color:$info;">= null</mark>\
<sup><mark style="color:$info;">Optional URL opened from the documentation button.<mark style="color:$info;"></sup>

### <i class="fa-list-timeline">:list-timeline:</i> Change History

{% updates format="full" %}
{% update date="2026-02-24" %}
## Version 1.0.0a

* Attribute Added
{% endupdate %}
{% endupdates %}
