# Navimacs

The simpliest WebExtension that introduces Emacs-like navigation keystrokes for all web-pages. Tested with Chrome 61 and Firefox 57.

The keystrokes supported so far:

```
C-p - scroll step up
C-n - scroll step down
C-f - scroll step right
C-b - scroll step left
M-< - scroll to top
M-> - scroll to bottom
C-v - page down
M-v - page up
C-x, f - open a new tab
C-x, k - close the current tab
```

Scrolling step is dynamic and depends on the height/width of the current window. It's supposed to scroll the size of the visible document area in 5 steps.

The software is licensed under [GPL 2.0](https://www.gnu.org/licenses/gpl-2.0.html) license.
