---
description: Getting a simple button with your referral link is super easy.
---

# Link Buttons Tutorial

## Simple HTML Button Link

{% hint style="success" %}
**Pro Tip:** This method uses basic HTML button and link elements for simplicity, but you can do more if you [HTML Events](link-buttons-tutorial.md#advanced-html-button-link) or customize styling with a [CSS Button](link-buttons-tutorial.md#stylized-css-button-link).
{% endhint %}

{% tabs %}
{% tab title="RSI Referral Button" %}
Simple one line of basic HTML code.&#x20;

Replace `STAR-XXXX-XXXX` with your referral code.

{% code overflow="wrap" lineNumbers="true" fullWidth="false" %}
```html
<a href="https://https://robertsspaceindustries.com?referral=STAR-XXXX-XXXX" target="_blank"><button name="RSI Referral"  type="button">STAR-XXXX-XXXX</button></a>
```
{% endcode %}
{% endtab %}

{% tab title="Discord Invite Button" %}
Simple one line of basic HTML code.

Replace `nTxQxYGWr3` with your Discord invite code.

{% code overflow="wrap" lineNumbers="true" %}
```html
<a href="https://discord.gg/nTxQxYGWr3" target="_blank"><button name="Discord"  type="button">Discord</button></a>
```
{% endcode %}
{% endtab %}
{% endtabs %}

## Advanced HTML Button Link

This button uses HTML Events.

{% tabs %}
{% tab title="RSI Referral Button" %}
Replace `STAR-XXXX-XXXX` with your referral code.

{% code overflow="wrap" lineNumbers="true" %}
```html
<button id="button" value="New Tab" onclick="window.open('https://robertsspaceindustries.com?referral=STAR-XXXX-XXXX')">STAR-XXXX-XXXX</button>
```
{% endcode %}
{% endtab %}

{% tab title="Discord Invite Button" %}
Replace `nTxQxYGWr3` with your Discord invite code.

{% code overflow="wrap" lineNumbers="true" %}
```html
<button id="button" value="New Tab" onclick="window.open('https://discord.gg/nTxQxYGWr3')">STAR-XXXX-XXXX</button>
```
{% endcode %}
{% endtab %}
{% endtabs %}

The advantage of using HTML Events is that you are now leveraging JavaScript and can call any function or script that you want.

{% tabs %}
{% tab title="RSI Referral Button" %}
Replace `STAR-XXXX-XXXX` with your referral code.

{% code overflow="wrap" lineNumbers="true" %}
```html
<button id="button" onclick="myFunction()">STAR-XXXX-XXXX</button>
<script>
function myFunction() {
  window.open('https://robertsspaceindustries.com?referral=STAR-XXXX-XXXX');
}
</script>
```
{% endcode %}
{% endtab %}

{% tab title="Discord Invite Button" %}
Replace `nTxQxYGWr3` with your Discord invite code.

{% code overflow="wrap" lineNumbers="true" %}
```html
<button id="button" onclick="myFunction()">Discord</button>
<script>
function myFunction() {
  window.open('https://discord.gg/nTxQxYGWr3');
}
</script>
```
{% endcode %}
{% endtab %}
{% endtabs %}

{% hint style="info" %}
Read more about [HTML OnClick Event](https://www.w3schools.com/jsref/event\_onclick.asp) here.
{% endhint %}

## Stylized CSS Button Link

{% tabs %}
{% tab title="RSI Referral Button" %}
```
// Some code
```
{% endtab %}

{% tab title="Discord Invite Button" %}
```
// Some code
```
{% endtab %}
{% endtabs %}

{% hint style="info" %}
Read more about how to customize [CSS Buttons](https://www.w3schools.com/css/css3\_buttons.asp) here.
{% endhint %}
