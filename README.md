# Material Discord Theme - [![Paypal][paypal-logo]][paypal-url] [![GitHub][github-logo]][github-url] [![Download][download-logo]][download-url]
#### A theme based on Google's Material Design
<hr>

Current version: v3.0.3 (24/02/2021) - Old messages add-on: **[Download](https://betterdiscord.net/ghdl?url=https://raw.githubusercontent.com/CapnKitten/BetterDiscord/master/Themes/Material-Discord/css/Material-Discord_addon-messages.theme.css)** | Status picker add-on: **[Download](https://betterdiscord.net/ghdl?url=https://raw.githubusercontent.com/CapnKitten/BetterDiscord/master/Themes/Material-Discord/css/Material-Discord_addon-status-picker.theme.css)**

Assets located at: https://github.com/CapnKitten/BetterDiscord/tree/master/Themes/Material-Discord

## Previews

(Previews are subject to be out of date / Animations in the GIFs are sped up)
#### Changing status

![discord-status](https://user-images.githubusercontent.com/4013216/36956319-bea5497a-1ffb-11e8-862c-d8a926b1f6a1.gif)

#### Changing user roles

![discord-roles](https://user-images.githubusercontent.com/4013216/36956334-d69b0b82-1ffb-11e8-8860-a171d0887f5c.gif)

#### Audio notification

![discord-audio](https://user-images.githubusercontent.com/4013216/35309728-dc958f5c-007b-11e8-8ff7-dee70cc82e22.gif)

#### Main chat area

![discord-001](https://user-images.githubusercontent.com/4013216/40872156-c597347a-6617-11e8-9e30-0dce8965bcc6.png)

#### User server info

![discord-009](https://user-images.githubusercontent.com/4013216/40872157-c5a3c4d8-6617-11e8-8dc4-0cb4222286e6.png)

#### User info popout

![discord-010](https://user-images.githubusercontent.com/4013216/40872158-c5ae8846-6617-11e8-84d8-bb9fb7a701c8.png)

#### User settings

![discord-104](https://user-images.githubusercontent.com/4013216/40872159-c5bc4760-6617-11e8-8965-5c3dc75715e8.png)

![discord-004](https://user-images.githubusercontent.com/4013216/40872160-c5c7333c-6617-11e8-8d43-03005569e24a.png)

#### DMs

![discord-005](https://user-images.githubusercontent.com/4013216/40872161-c5d33d4e-6617-11e8-8b73-7b474325fb79.png)

#### Home tab

![discord-401](https://user-images.githubusercontent.com/4013216/53679347-a3f64780-3c99-11e9-833b-640bba0b8825.png)

![discord-402](https://user-images.githubusercontent.com/4013216/53679536-95a92b00-3c9b-11e9-8c15-e71452e91df7.png)

&nbsp;

## Variables

#### App elements
 - `--app-bg` - The background for the entire Discord app. Default: `var(--main-alt)`
 - `--main-color` - The background color for main content areas like in the settings menu. Default: `#16171a` - `#e8eaeb`**
 - `--main-alt` - An alternative background color for main content areas. Default: `#0f1012` - `#ddd`**
 - `--server-color` - The background color for the servers list. Default: `#232327` - `#eee`**
 - `--status-picker-color` - The background color for the status picker popout. Default: `#181a1d` - `#dee0e0`**
 - `--sidebar-panel-color` - The background color for the sidebar panels in the channels list. Default: `#111114` - `#d4d6d6`**
 - `--chat-color` - The background color the main chat area. Default: `#202225` - `#fff`**

#### Accent elements
 - `--accent-color` - The main accent color for the theme. Default: `#3f51b5`
 - `--accent-rgb` - The accent color RGB values for elements that require an opacity. Default: `63,81,181`
 - `--accent-button-action` - The color used for the hover and active states for accent buttons. Default: `#fff`
 - `--accent-button-action-hover` - The opacity for the accent button hover state. Default: `0.06`
 - `--accent-button-action-active` - The opacity for the accent button active state. Default: `0.12`
 - `--accent-text-color` - The text color for buttons and other various elements with the accent background color. Default: `#fff`

#### Message elements
 - `--message-color` - The background color for message bubbles. Default: `#292d30` - `#edeff0`**
 - `--message-color-alt` - An alternative background color for message bubbles. Default: `#1c1e21` - `#e8e8e8`**
 - `--message-radius` - The border radius for the message bubbles. Default: `19px`
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
[download-url]: https://betterdiscord.net/ghdl?url=https://raw.githubusercontent.com/CapnKitten/Material-Discord/master/Material-Discord.theme.css
