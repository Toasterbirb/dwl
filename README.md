# dwl - dwm for Wayland

This is a fork of [dwl](https://github.com/djpohly/dwl) with some arbitrary customizations. Those customizations may or may not be listed in this README file, so use with caution.

**Please don't report any issues you face with this repo to upstream, unless you also experience that same issue with the upstream version of dwl!**

## Main changes
- Colors
- Keybindings
- Finnish keyboard layout
- Turn the Caps Lock -key into Escape
- Alt-tabbing between two tags
- Create /tmp/dwl_startup after dwl has initialized everything to help with desktop startup scripts
- Built in notifications to replace the statusbar
- Several patches

### Notification keybinds
| Key combination | Notification |
| --------------- | ------------ |
| Super + C       | Clock        |
| Super + B       | Battery      |

## Autostart dependencies
- foot

## Compile time dependencies
- libnotify

## Patches applied
- [autostart](https://github.com/djpohly/dwl/wiki/autostart)
- [genericgaps](https://github.com/djpohly/dwl/wiki/genericgaps) [not enabled by default]
- [keycodes](https://github.com/djpohly/dwl/wiki/keycodes)
