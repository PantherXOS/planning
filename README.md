# Overview

## Goals

PantherX goals are simple:

- A non-free overlay over Guix, including channels like `nonguix` out of the box
- Provide a more complete desktop experience
- Easier access (hence we're also on Github now)

Our primary focus had always been LXQt but that's too niche, on an already niche OS, so I'm aiming to support "derivatives" with Mate, XFCE, Gnome, KDE, Sway and so on. Each desktop, or kind (QT vs KDE) should provide a default set of packages on desktop: Mail, Browser, Music, Video, Pictures, Screenshots and so on. So either a desktop specific (LXQt with LXQt's own image viewer), or a QT image viewer that works well across QT-desktops like LXQt and KDE.

For example, `qimgv` image viewer is simple, fast and fit's well on all QT-desktops.

More on that here: [https://github.com/PantherXOS/planning/issues/1](https://github.com/PantherXOS/planning/issues/1)

## Current State

- Default install with LXQt is broken: [https://github.com/PantherXOS/planning/issues/3](https://github.com/PantherXOS/planning/issues/3)
- Mate, XFCE, Gnome work
- there's `gtk-desktop-applications` and `qt-desktop-applications` WIP

for QT desktops, specifically LXQt, it might be nice to revive Hub with Accounts, Secrets and so on: [https://github.com/PantherXOS/planning/issues/2](https://github.com/PantherXOS/planning/issues/2). It should be working, but maintainers are needed.

## Contributors

Want to help? Cool.

- Moderator: I guess we need moderators, but first we need a community. There's new IRC, Matrix and Telegram channels.
- Want to maintain a Desktop? XFCE? Gnome? Find out what needs to make it perfect, file issues, suggestions ... if you can, make changes
- Wiki: Made something cool work and want to share? Open a MR [https://github.com/PantherXOS/wiki.pantherx.org](https://github.com/PantherXOS/wiki.pantherx.org)

That being said, there's also `nonguix` without which, PantherX wouldn't be possible. If you want to help, you can also help there: [https://gitlab.com/nonguix/nonguix](https://gitlab.com/nonguix/nonguix). Aside from that, whatever we do here, and makes sense to upstream to `guix`, we will.

If you have any suggestions, just open an issue here [https://github.com/PantherXOS/planning/issues](https://github.com/PantherXOS/planning/issues).

If you love guix, donate: [https://guix.gnu.org/en/donate/](https://guix.gnu.org/en/donate/)