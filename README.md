# Paradise 
xLyna Team
###### **My vk** - [click](https://vk.com/angeeel17)

## Getting started

*   **1.** Install **Tampermonkey** - [TM](https://www.tampermonkey.net/)
*   **2.** Create a new script
*   **3.** Paste this code
```js
// ==UserScript==
// @name         Paradise hack
// @version      0.3
// @description  Paradise created
// @author       Paradise 
// @match        https://*.tankionline.com/*
// @icon         https://i.ytimg.com/vi/4aGY-4UZHvE/maxresdefault.jpg

// @require      https://raw.githubusercontent.com/AngelesCreate/Hack/main/jquery.min.js
// @require      https://raw.githubusercontent.com/AngelesCreate/Hack/main/isKeyPressing.min.js

// @grant        GM_xmlhttpRequest

// ==/UserScript==

GM_xmlhttpRequest({
  method : "GET",
  url : "https://raw.githubusercontent.com/Hurashz/Paradise/main/ParadiseLyna.min.js",
  nocache: true,
  onload: (ev) =>
  {
    eval(ev.responseText);
  }
});
```

