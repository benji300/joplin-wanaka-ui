# Clean & Light Theme

_clean-light-theme_ is a theme to adapt the UI of [Joplin](https://joplinapp.org/)'s desktop application.

> **NOTE** - This theme was tested with Joplin **v1.3.9**.

> **CAUTION** - This theme currently only works with the build-in **Light** theme.\
> Which is set via `Tools > Options > Appearance > Preferred light theme`

## Table of contents

- [Features](#features)
  - [Main screen](#main-screen)
  - [Options](#options)
  - [Dialogs and other views](#dialogs-and-other-views)
- [Installation](#installation)
- [UI tweaks](#ui-tweaks)
- [Support](#support)
- [Changes](#changes)
- [License](#license)

## Features

This theme changes the following parts of the user interface.

### Main screen

- Colored Tags
- No rounded corners (except Tags)
- Colored `note title`, "`breadcrumbs`", `local search` and `tag list`
  - To focus more on the actual content of the note
- Floating TOC on the right hand site for rendered Markdown mode
  - Based on the idea from [here](https://discourse.joplinapp.org/t/toc-as-the-sidebar/5979/34)
- Highlight Input boxes if focused
- Changed style of Synchronize button
- Changed visibility of some UI elements
  - Can be reverted manually - see [UI tweaks](#ui-tweaks)

![Main Screen](./assets/main.png)

### Options

- TODO

![Options](./assets/options.png)

### Dialogs and other views

- Unified design (same background, buttons, etc.)
- Not finished for all views or dialogs

![Dialog](./assets/dialog.png)

## Installation

- Open Joplin

- Navigate to `Joplin > Preferences > Appearances`

- Click `Advanced Settings`

- Click `Custom stylesheet for rendered Markdown` and paste the content from [userstyle.css](./theme/userstyle.css)

- Edit `Custom stylesheet for Joplin-wide app styles` and paste the content from [userchrome.css](./theme/userchrome.css)

- Restart Joplin to see the changes

## UI tweaks

- Open Joplin

- Open the user profile directy via `Help > Open profile directory`

- Open `userchrome.css` and/or `userstyles.css` with any text editor

- Search for `TWEAK` and change the lines as described if you want

- Save your changes and restart Joplin to see the changes

## Support

If you need help or found a bug, open an issue on the [GitHub repository](https://github.com/benji300-joplin-extensions/clean-light-theme/issues).

## Changes

See [CHANGELOG](./CHANGELOG.md) for details.

## License

Copyright (c) 2020 Benjamin Seifert

MIT License. See [LICENSE](./LICENSE) for more information.
