# Material Discord Theme - [![Paypal][paypal-logo]][paypal-url] [![GitHub][github-logo]][github-url] [![Discord][discord-logo]][discord-url] [![Download][download-logo]][download-url]
#### A theme based on Google's Material Design
<hr>

Current version: v3.0.4 (24/01/2022)

[View add-on themes](https://github.com/CapnKitten/BetterDiscord/tree/master/Themes/Material-Discord/css/addons)

<hr>

Assets located at: https://github.com/CapnKitten/BetterDiscord/tree/master/Themes/Material-Discord

## Previews

(Previews are subject to be out of date)

#### Main chat area

![discord-601](https://user-images.githubusercontent.com/4013216/151684062-a1f39880-f39e-410a-89e3-c0b8913c225e.png)

#### User popout info

![discord-602](https://user-images.githubusercontent.com/4013216/151684066-302585e8-4266-4c76-8eb2-af4042ba40ce.png)

#### User profile

![discord-603](https://user-images.githubusercontent.com/4013216/151684072-a67ff752-6811-4806-9a9f-24b27ee1ce02.png)

#### User settings

![discord-604](https://user-images.githubusercontent.com/4013216/151684077-902a0e1f-3873-4702-9824-6fa954f37532.png)

![discord-605](https://user-images.githubusercontent.com/4013216/151684081-88791d51-61f5-4cf8-a89b-591cfadef3df.png)

#### DMs

![discord-606](https://user-images.githubusercontent.com/4013216/151684087-a6a29ce8-4939-4964-b427-2ef5c60618f3.png)

&nbsp;

## Variables

** **Indicates that it has two values for both the dark and light themes of Discord. Instead of using `:root`, use `.theme-dark` or `.theme-light`.**

#### App elements
 - `--app-bg` - The background for the entire Discord app. Default: `var(--main-alt)`
 - `--main-color` - The background color for main content areas like in the settings menu. Default: `#16171a` - `#e8eaeb`**
 - `--main-alt` - An alternative background color for main content areas. Default: `#0f1012` - `#ddd`**
 - `--server-color` - The background color for the servers list. Default: `#232327` - `#eee`**
 - `--status-picker-color` - The background color for the status area with the settings button. Default: `#181a1d` - `#dee0e0`**
 - `--sidebar-panel-color` - The background color for the sidebar panels in the channels list. Default: `#111114` - `#d4d6d6`**
 - `--chat-color` - The background color the main chat area. Default: `#202225` - `#fff`**
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
 - `--message-color-alt` - An alternative background color for message bubbles. Default: `#1c1e21` - `#e8e8e8`**
 - `--message-radius` - The border radius for the message bubbles. Default: `19px`
 - `--message-padding-top` - The top and bottom padding of message bubbles. Default: `8px`
 - `--message-padding-side` - The side padding of message bubbles. Default: `12px`
 - `--media-radius` - The border radius for images, videos, and audio. Default: `19px`
 - `--attachment-color` - The background color for all attachments. Default: `rgb(0,0,0,0.325)` - `rgba(0,0,0,0.1)`**
 - `--main-textarea-color` - The background color for the main chat text box. Default: `#303338` - `#fff`**
 - `--main-textarea-color-alt` - An alternative background color for the main chat text box. Default: `#3b3f42` - `#ccc`**
 - `--main-textarea-border` - The border color for the main chat text box. Default: `#3e434a` - `#dadce0`**
 - `--main-textarea-radius` - The border radius for the main chat text box. Default: `24px`
 - `--typing-color` - The background color for the typing indicator. Default: `rgba(32,34,37,0.9)` - `rgba(255,255,255,0.8)`**

#### Popout menu elements
 - `--popout-color` - The background color for popout menus and modals. Default: `#2c2f33` - `#fff`**
 - `--popout-color-alt` - An alternative background color for popout menus and modals. Default: `#202225` - `#e5e5e5`**
 - `--popout-header-border` - The border color for popout menu headers. Default: `#444` - `#aaa`**
 - `--separator-color` - The background color for the separator lines in various popout menus. Default: `#444` - `#ccc`**
 - `--popout-radius` - The border radius for popout menus. Default: `5px`
 - `--popout-radius-big` - The bigger border radius for modals. Default: `10px`

#### Card elements
 - `--card-color` - The background color for cards. Default: `transparent` - `transparent`**
 - `--card-color-hover` - The background color for hovering over cards. Default: `#292b2f` - `#eee`**
 - `--card-color-alt` - An background color for cards. Default: `#2a2c30` - `transparent`**
 - `--card-color-alt-hover` - An background color for hovering over cards. Default: `#35383d` - `#d4d4d4`**
 - `--card-header-text-color` - The text color for card headers. Default: `#dcddde` - `#333`**
 - `--card-radius` - The border radius for cards. Default: `5px`
 - `--card-radius-big` - The bigger border radius for cards. Default: `10px`

#### Button elements
 - `--button-radius` - The border radius for buttons. Default: `5px`
 - `--button-link-color` - The background color for transparent buttons. Default: `255,255,255` - `0,0,0`**
 - `--button-link-text-color` - The text color for transparent buttons. Default: `#fff` - `#333`**

#### Slider and switch elements
 - `--slider-color` - The background color for sliders. Default: `#4f545c` - `#999`**
 - `--switch-knob-color` - The background color for the knob on switches. Default: `#777` - `#fff`**
 - `--switch-slider-color` - The background color for the background slider on switches. Default: `rgba(65,65,65,0.65)` - `rgba(0,0,0,0.2)`**

#### Input elements
 - `--input-color` - The background color for text fields that don't have the animated border. Default: `rgba(255,255,255,0.075)` - `#d2d4d4`**
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
[download-url]: https://capnkitten.github.io/BetterDiscord/Download/?theme=Material-Discord

[discord-logo]: https://img.shields.io/static/v1?label=Discord&message=Server&style=flat&logo=discord&color=blue
[discord-url]: https://discord.gg/jzJkA6Z
