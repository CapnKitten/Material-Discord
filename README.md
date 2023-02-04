# Material Discord Theme - [![Paypal][paypal-logo]][paypal-url] [![GitHub][github-logo]][github-url] [![Discord][discord-logo]][discord-url] [![Download][download-logo]][download-url]
#### A theme based on Google's Material Design
<hr>

Current version: v3.0.4 (24/01/2022)

[View add-on themes](https://github.com/CapnKitten/BetterDiscord/tree/master/Themes/Material-Discord/css/addons)

## Previews

(Previews are subject to be out of date)

#### Main chat area

![discord-701](https://user-images.githubusercontent.com/4013216/216792441-cc02a2fc-d175-432d-af75-81975d75e65e.png)

#### User popout info

![discord-702](https://user-images.githubusercontent.com/4013216/216792443-04fe70f0-0cd7-4d98-bb49-c937415c53d0.png)

#### User profile

![discord-703](https://user-images.githubusercontent.com/4013216/216792451-676c4d76-6138-42c3-8ce2-3ee76cb82abf.png)

#### User settings

![discord-704](https://user-images.githubusercontent.com/4013216/216792456-36074914-4cb8-4c0b-aa07-74d09e274bcf.png)

![discord-705](https://user-images.githubusercontent.com/4013216/216792461-30509d7f-30c1-4d31-b4e0-9be858723cfd.png)

#### DMs

![discord-706](https://user-images.githubusercontent.com/4013216/216792463-a2472c19-21bd-48e0-beba-05d092c715dc.png)

&nbsp;

## Variables

** **Indicates that it has two values for both the dark and light themes of Discord. Instead of using `:root`, use `.theme-dark` or `.theme-light`.**

#### App elements
 - `--app-font` - The font used throughout the entire theme. The font must either be installed or imported. Default: `"Google Sans"`
 - `--app-bg` - The background for the entire Discord app. Default: `var(--main-alt)`
 - `--main-color` - The background color for main content areas like in the settings menu. Default: `#16171a` - `#e8eaeb`**
 - `--main-alt` - An alternative background color for main content areas. Default: `#0f1012` - `#ddd`**
 - `--server-color` - The background color for the servers list. Default: `#232327` - `#eee`**
 - `--status-picker-color` - The background color for the status area with the settings button. Default: `#181a1d` - `#dee0e0`**
 - `--sidebar-panel-color` - The background color for the sidebar panels in the channels list. Default: `#111114` - `#d4d6d6`**
 - `--chat-color` - The background color the main chat area. Default: `var(--main-color)`
 - `--avatar-radius` - The border radius of avatars, servers, and change status buttons. Default: `50%`
 - `--tooltip-color` - The background color for tooltips. Default: `rgba(97,97,97,0.9)`
 - `--tooltip-text-color` - The text color for tooltips. Default: `#ddd`
 - `--tooltip-shadow` - The box shadow for tooltips. Default: `0px 5px 15px rgba(0,0,0,0.2)`

#### Accent elements
 - `--accent-hue` - The hue value for the accent color of the theme. Default: `224`
 - `--accent-saturation` - The saturation percentage for the accent color of the theme. Default: `71%`
 - `--accent-lightness` - The lightness percentage for the accent color of the theme. Default: `61%`
 - `--accent-button-action` - The color used for the hover and active states for accent buttons. Default: `#fff`
 - `--accent-text-color` - The text color for buttons and other various elements with the accent background color. Default: `#fff`

#### Message elements
 - `--message-color` - The background color for message bubbles. Default: `#292d30` - `#edeff0`**
 - `--message-color-hover` - The hover background color for message bubbles. Default: `#303438` - `#e1e2e3`**
 - `--message-color-alt` - An alternative background color for message bubbles in areas like pinned messages. Default: `#1c1e21` - `#e8e8e8`**
 - `--message-radius` - The border radius for the message bubbles. Default: `19px`
 - `--message-padding-top` - The top and bottom padding of message bubbles. Default: `8px`
 - `--message-padding-side` - The side padding of message bubbles. Default: `12px`
 - `--media-radius` - The border radius for images, videos, and audio. Default: `19px`
 - `--attachment-color` - The background color for all attachments. Default: `rgb(0,0,0,0.325)` - `rgba(0,0,0,0.1)`**
 - `--main-textarea-color` - The background color for the main chat text box. Default: `#2c2f33` - `#fff`**
 - `--main-textarea-color-alt` - An alternative background color for the main chat text box. Default: `#3b3f42` - `#ccc`**
 - `--main-textarea-border` - The border color for the main chat text box. Default: `#3a3e45` - `#dadce0`**
 - `--main-textarea-radius` - The border radius for the main chat text box. Default: `24px`
 - `--typing-color` - The background color for the typing indicator. Default: `rgba(22,23,26,0.9)` - `rgba(249,249,249,0.9)`**

#### Popout menu elements
 - `--popout-color` - The background color for popout menus and modals. Default: `#2c2f33` - `#fff`**
 - `--popout-color-alt` - An alternative background color for popout menus and modals. Default: `#202225` - `#e5e5e5`**
 - `--popout-header-border` - The border color for popout menu headers. Default: `#444` - `#aaa`**
 - `--separator-color` - The background color for the separator lines in various popout menus. Default: `#444` - `#ccc`**
 - `--popout-radius` - The border radius for popout menus. Default: `8px`
 - `--popout-radius-big` - The bigger border radius for modals. Default: `18px`

#### Card elements
 - `--card-color-filled` - The background color for cards. Default: `hsl(225,6%,13%)` - `hsl(0,0%,92%)`**
 - `--card-color-hover` - The background color for hovering over cards. Default: `hsl(225,6%,16%)` - `hsl(0,0%,85%)`**
 - `--card-color-active`- The background color for active cards. Default: `hsl(225,6%,25%)` - `hsl(0,0%,80%)`**
 - `--card-color-alt` - An background color for cards. Default: `hsl(225,6%,18%)` - `hsl(0,0%,98%)`**
 - `--card-color-alt-hover` - An background color for hovering over cards. Default: `hsl(225,6%,21%)` - `hsl(0,0%,88%)`**
 - `--card-border-color` - The border color for outlined cards. Default `hsl(220,3%,26%)` - `hsl(0,0%,78%)`**
 - `--card-header-text-color` - The text color for card headers. Default: `#eee` - `#333`**
 - `--card-radius` - The border radius for cards. Default: `8px`
 - `--card-radius-big` - The bigger border radius for cards. Default: `18px`

#### Button elements
 - `--button-height` - The height for buttons. Default: `36px`
 - `--button-padding` - The left and right padding for buttons. Default: `0 24px`
 - `--button-radius` - The border radius for buttons. Default: `18px`
 - `--button-link-color` - The background color for transparent buttons. Default: `0,0%,100%` - `0,0%,0%`**
 - `--button-link-text-color` - The text color for transparent buttons. Default: `#fff` - `#333`**

#### Slider and switch elements
 - `--switch-knob-color` - The background color for the knob on switches. Default: `hsl(0,0%,47%)` - `hsl(0,0%,47%)`**
 - `--switch-slider-color` - The background color for the background slider on switches. Default: `hsl(240,1%,20%)` - `hsl(240,1%,20%)`**

#### Input elements
 - `--input-color` - The background color for text fields that don't have the animated border. Default: `rgb(38,38,41)` - `rgb(38,38,41)`**
 - `--input-border-color` - The border color for text fields. Default: `#444` - `#aaa`**

#### Various elements
 - `--md-ripple-color` - The color of the ripple effect. Default: `255,255,255` - `0,0,0`**
 - `--emoji-category-header` - The background color for the headers in the emoji panel. Default: `rgba(44,47,51,0.95)` - `rgba(255,255,255,0.9)`**
 - `--scrollbar-color` - The background color for scrollbars. Default: `255,255,255` - `0,0,0`**

** **Indicates that it has two values for both the dark and light themes of Discord. Instead of using `:root`, use `.theme-dark` or `.theme-light`.**

&nbsp;

## Changelog

#### v3.0.3 (24/02/2021)
* Font changed to Google Sans
* Delete message modal updated


[View previous changelogs](https://github.com/CapnKitten/BetterDiscord/blob/master/Themes/Material-Discord/changelog.md)

[paypal-logo]: https://img.shields.io/static/v1?label=PayPal&message=Donate&style=flat&logo=paypal&color=blue
[paypal-url]: https://paypal.me/capnkitten

[github-logo]: https://img.shields.io/static/v1?label=GitHub&message=Sponsor&style=flat&logo=github&color=black
[github-url]: https://github.com/sponsors/CapnKitten

[download-logo]: https://img.shields.io/static/v1?label=Download&message=Theme&style=flat&color=blue
[download-url]: https://betterdiscord.app/theme/MaterialDiscord

[discord-logo]: https://img.shields.io/static/v1?label=Discord&message=Server&style=flat&logo=discord&color=blue
[discord-url]: https://discord.gg/jzJkA6Z
