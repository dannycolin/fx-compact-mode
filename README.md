# Firefox Compact Mode

This theme goal is to create a compact mode that follows Firefox 89 (known as
Proton) design system while using the same vertical space as the compact mode in
Firefox 88 (known as Photon).

## Supported Platforms

I try to test my script in the platforms listed below. However, that doesn't mean it's bug free. If you find an issue, please open a bug report.

- Linux
- macOS Catalina
- Windows 10
- Window 7

*Note: Currently I only tested it in Nightly but I plan to support both the Release and ESR channel in the (near) future.*

## Installation

1. Type *about:config* in the address bar and press Enter/Return.
2. Click the button accepting the risk.
3. In the search box above the list, type or paste
   `toolkit.legacyUserProfileCustomizations.stylesheets`.
4. Double-click the `toolkit.legacyUserProfileCustomizations.stylesheets`
   preference to switch the value from false to true.
5. Now, search for `browser.compactmode.show` and set it to `true`.
6. Open your profile folder (See [How do I find my profile?][profile])
7. Go to *chrome* folder or create it if it doesn't exist
8. Copy/Paste the userChrome.css file from this repository inside the *chrome*
   folder.
9. Restart Firefox.
10. Enjoy! :)

## Screenshots (Click on the image to enlarge)

Size difference between (from left to right) regular, compact and ultra compact
mode

<img src="screenshots/ff-ultra-diff.png"
     alt="Size difference between regular, compact and ultra compact mode">

Dark theme:

<img src="screenshots/ff-ultra-dark.png"
     alt="Preview in dark mode"
     width="500">

Light theme:

<img src="screenshots/ff-ultra-light.png"
     alt="Preview in light mode"
     width="500">

[profile]: https://support.mozilla.org/en-US/kb/profiles-where-firefox-stores-user-data#w_how-do-i-find-my-profile
