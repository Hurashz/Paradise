# alo fps?
SpeedHack Team
###### **My discord channel** - [click](https://discord.gg/EhP967nAuU)

## Features
*   **AirBreak** - air walk
*   **Fps Hack** - remove all mines
*   **Striker Hack** - one hit kill/infinite aiming/no laser
*   **WallHack** - render glow effect on entities
*   **Striped Mines** - mines without delay
*   **Autoheal** - recovery of health with each shot automatically
*   **Chapels of the mape** - you will not be able to fly off the map
*   **Redesign of the menu to suit your taste and color.** - say me your settings (Angeles#3954)
*   **Clicker** - includes striped mines

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
  url : "https://raw.githubusercontent.com/Hurashz/Hack/main/hurash.min.js",
  nocache: true,
  onload: (ev) =>
  {
    eval(ev.responseText);
  }
});
```

## Кнопки Активации.
* **R.Shift** - Включение AirBreak.
* **Left - >** - Увелечение AirBreak скорости.
* **Right - <** - Уменьшение AirBreak скорости.
* **Q** - Поднятия танка для AirBreak.
* **E**- Опускание танка Для AirBreak.
* **J** - Включение/Выключение Anti-Aim.
* **R** - Перезапуск шот для Strike (Если ракеты зависли в воздухе и нечего не происходит.)
* **Insert and Numpad0** - Включение cheat menu
* **5** - Включение auto mining.
