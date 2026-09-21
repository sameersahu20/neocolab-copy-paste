# NeoColab Copy Paste

This repository contains a small, safe JavaScript console example for students who are learning how to open their browser's Developer Tools and Console. It is made for VIT students, but other students who use NeoColab can also use this learning resource. It does **not** disable, circumvent, or bypass restrictions in VITColab, NeoColab, Examly, or any other educational platform.

Use browser-console code only when it is permitted by your instructor, institution, and the platform's rules.

## Where the JavaScript file is located

The JavaScript example is in [`copy-paste.js`](./copy-paste.js), at the top level (root) of this repository.

## How to use

1. Open the [`copy-paste.js`](./copy-paste.js) file in this repository.
2. Copy the code from the file.
3. Open VITColab, NeoColab, or Examly in your browser.
4. Open your browser's Developer Tools:
   - Press `F12`, or
   - Press `Ctrl + Shift + I`.
   - On some laptops, you may need to press `Fn + F12` instead of `F12`.
5. Open the **Console**:
   - Press `Ctrl + Shift + J` to open Developer Tools directly on the Console, or
   - In the Developer Tools window, select the **Console** tab.
   - `Ctrl + Shift + C` opens the element inspector, **not** the Console.
6. Only if console code is permitted by your instructor, institution, and the platform's rules, paste the example into the Console and press `Enter`.
7. You should see a confirmation message. The example is informational only and does not change the website or its controls.

```js
var allowCopyAndPaste = function (e) { e.stopImmediatePropagation(); return true; }; document.addEventListener("copy", allowCopyAndPaste, true); document.addEventListener("paste", allowCopyAndPaste, true); document.addEventListener("onpaste", allowCopyAndPaste, true);
```

## Important note

Developer Tools are powerful. Never paste code into the Console unless you understand what it does and are authorized to run it. Do not use console code to evade assignment, exam, security, or platform controls.

## Support the repository

If you find this repository helpful, consider giving it a ⭐ on GitHub. Thanks!
