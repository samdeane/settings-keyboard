# Keyboard Mapping

Add the gb_swapped file into `/usr/share/X11/xkb/symbols`.

Edit `/usr/share/X11/xkb/rules/evdev.xml` to include a section for the `gb_swapped` definitions.

## Xmodmap (Old method)

The Xmodmap method needs resetting every login, and only works for the current user, so isn't so good.
