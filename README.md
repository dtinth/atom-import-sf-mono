# import-sf-mono

[New San Francisco Monospaced font is gorgeous!](https://www.reddit.com/r/apple/comments/4o23fm/new_san_francisco_monospaced_font_is_gorgeous/) Unfortunately, it’s only available inside `Terminal.app` (and `Xcode.app`).

This Atom package imports the “SF Mono” font directly from `Terminal.app`, which allows you to use this font in Atom.

__Usage:__

1. Get a Mac and install Mac OS X Sierra.

2. Install this Atom package.

3. Configure your font in Atom to "SF Mono".

4. Gorgeous.

__Note:__ This package does not contain the fonts file. It only references the font files located in your system. Here is the full package code:

```less
@font-face { font-family: "SF Mono"; font-weight: 200; font-style: normal; src: url(file:///Applications/Utilities/Terminal.app/Contents/Resources/Fonts/SFMono-Light.otf); }
@font-face { font-family: "SF Mono"; font-weight: 200; font-style: italic; src: url(file:///Applications/Utilities/Terminal.app/Contents/Resources/Fonts/SFMono-LightItalic.otf); }
@font-face { font-family: "SF Mono"; font-weight: 400; font-style: normal; src: url(file:///Applications/Utilities/Terminal.app/Contents/Resources/Fonts/SFMono-Regular.otf); }
@font-face { font-family: "SF Mono"; font-weight: 400; font-style: italic; src: url(file:///Applications/Utilities/Terminal.app/Contents/Resources/Fonts/SFMono-RegularItalic.otf); }
@font-face { font-family: "SF Mono"; font-weight: 500; font-style: normal; src: url(file:///Applications/Utilities/Terminal.app/Contents/Resources/Fonts/SFMono-Medium.otf); }
@font-face { font-family: "SF Mono"; font-weight: 500; font-style: italic; src: url(file:///Applications/Utilities/Terminal.app/Contents/Resources/Fonts/SFMono-MediumItalic.otf); }
@font-face { font-family: "SF Mono"; font-weight: 600; font-style: normal; src: url(file:///Applications/Utilities/Terminal.app/Contents/Resources/Fonts/SFMono-Semibold.otf); }
@font-face { font-family: "SF Mono"; font-weight: 600; font-style: italic; src: url(file:///Applications/Utilities/Terminal.app/Contents/Resources/Fonts/SFMono-SemiboldItalic.otf); }
@font-face { font-family: "SF Mono"; font-weight: 700; font-style: normal; src: url(file:///Applications/Utilities/Terminal.app/Contents/Resources/Fonts/SFMono-Bold.otf); }
@font-face { font-family: "SF Mono"; font-weight: 700; font-style: italic; src: url(file:///Applications/Utilities/Terminal.app/Contents/Resources/Fonts/SFMono-BoldItalic.otf); }
@font-face { font-family: "SF Mono"; font-weight: 800; font-style: normal; src: url(file:///Applications/Utilities/Terminal.app/Contents/Resources/Fonts/SFMono-Heavy.otf); }
@font-face { font-family: "SF Mono"; font-weight: 800; font-style: italic; src: url(file:///Applications/Utilities/Terminal.app/Contents/Resources/Fonts/SFMono-HeavyItalic.otf); }
```
