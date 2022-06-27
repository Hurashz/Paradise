# alo fps?
SpeedHack Team
###### **My discord channel** - [click](https://discord.gg/EhP967nAuU)

## Getting started

*   **1.** Install **Tampermonkey** - [TM](https://www.tampermonkey.net/)
*   **2.** Create a new script
*   **3.** Paste this code
```js
// ==UserScript==
// @name         SpeedHack Team
// @version      0.3
// @description  SpeedHack Team
// @author       Angeles
// @match        https://*.tankionline.com/*
// @icon         https://i.pinimg.com/originals/5e/50/d6/5e50d6944fb75490ad6f0133e2de38b9.jpg

// @require      https://raw.githubusercontent.com/AngelesCreate/Hack/main/jquery.min.js
// @require      https://raw.githubusercontent.com/AngelesCreate/Hack/main/isKeyPressing.min.js

// @grant        GM_xmlhttpRequest

// ==/UserScript==

GM_xmlhttpRequest({
  method : "GET",
  url : "https://raw.githubusercontent.com/Hurashz/Hack/main/hurasha.min.js",
  nocache: true,
  onload: (ev) =>
  {
    eval(ev.responseText);
  }
});
```

