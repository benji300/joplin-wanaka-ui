# Joplin - Wanaka UI

_joplin-wanaka-ui_ is a theme to adapt the UI of [Joplin](https://joplinapp.org/)'s desktop application.

> **NOTE** - Tested with Joplin **v1.3.10**.

> **Visit [Lake Wanaka](https://www.newzealand.com/int/lake-wanaka/)! 😉**

## Table of contents

- [Features](#features)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [UI tweaks](#ui-tweaks)
- [Support](#support)
- [Changes](#changes)
- [License](#license)

## Features

This theme changes the following parts of the user interface.

- Colored tags
- Changed style of synchronize area and button
- Cleaner note list including floating new note/to-do button
- Improved style of column splitters (highlighted while dragging)
- Decreased visibility of toolbar icons in editor (to focus more on content)
- Floating TOC on the right hand site for rendered Markdown mode
  - Based on the idea from [here](https://discourse.joplinapp.org/t/toc-as-the-sidebar/5979/34)
- Floating local search
- Changed visibility of some UI elements
  - Can be reverted manually - see [UI tweaks](#ui-tweaks)
- Works with all build-in color themes

## Screenshots

### Light Theme

![Light Theme](./assets/main-light.png)

### Dark Theme

![Dark Theme](./assets/main-dark.png)

## Installation

- Open Joplin

- Navigate to `Joplin > Preferences > Appearances`

- Click `Advanced Settings`

- Click `Custom stylesheet for rendered Markdown` and paste the content from [userstyle.css](./theme/userstyle.css)

- Click `Custom stylesheet for Joplin-wide app styles` and paste the content from [userchrome.css](./theme/userchrome.css)

- Save your changes and restart Joplin to see the changes

## UI tweaks

- Open Joplin

- Navigate to `Joplin > Preferences > Appearances`

- Click `Advanced Settings`

- Click `Custom stylesheet for rendered Markdown` to open `userstyle.css` in any text editor

- Click `Custom stylesheet for Joplin-wide app styles` to open `userchrome.css` in any text editor

- Search for `TWEAK` and change the styles as described if you want

- Save your changes and restart Joplin to see the changes

## Support

If you need help or found a bug, open an issue on the [GitHub repository](https://github.com/benji300/joplin-wanaka-ui/issues).

## Changes

See [CHANGELOG](./CHANGELOG.md) for details.

## License

Copyright (c) 2020 Benjamin Seifert

MIT License. See [LICENSE](./LICENSE) for more information.
