# HTML-Switch-Input-Language

### Inspired by [farsitype v1.3.6](https://translate.google.com/translate?sl=auto&tl=en&u=http%3A%2F%2Fwww.farsitype.ir%2F)

## Change keyboard layout automatically using JavaScript in HTML.
Unfortunatally, we can not change the keyboard layout using JS.
We would need to call Win API function SystemParametersInfo, that is impossible from a browser with JS.

However it could be very useful for users with multi language system (e.g. switch automatically a language when input field gets a focus).

Solution -  Capture the keydown event and replace the character.

Usage
```javascript
<input type="text" name="hebInput" id="hebInput" data-lang="he" />

<textarea cols="22" rows="7" name="hebArea" id="hebArea" data-lang="he"> </textarea>

<script src="./SwitchInputLan.js"></script>
```
[Demo Page](https://albertly.github.io/HTML-Switch-Input-Language/index.html)
