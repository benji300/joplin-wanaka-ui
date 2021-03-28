# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

- None

## [0.5.0] - 2021-03-28

> Tested with Joplin v1.7.x

### Added

- Possibility to hide icons for internal links in viewer
- Styling options for [Embed search in note](https://github.com/ambrt/joplin-plugin-embed-search) plugin
- Styling options for [Rick Markdown](https://github.com/CalebJohn/joplin-rich-markdown) plugin

### Fixed

- Fixed sidebar (incl. sync button) styles

## [0.4.0] - 2021-01-21

### Changed

- Adaptions for latest release v1.6.8
- Remove border between panels
- Disable CodeMirror line numbers hack by default
  - Instead added support for CodeMirror line numbers [plugin](https://github.com/shantanugoel/joplin-plugin-cm-linenumbers/)
- Disable default breadcrumbs by default

### Fixed

- Support two line editor title bar if window size decreases

## [0.3.0] - 2020-11-28

### Changed

- Improve look of column splitters
- Improve look of new dynamic panels
- Change style of note list entries
  - Active/hover items width full width

## [0.2.0] - 2020-11-16

### Added

- Show/hide line numbers in CodeMirror
  - Based on the idea from [here](https://discourse.joplinapp.org/t/option-to-show-line-numbers-in-editor/8313/22)
  - Enabled by default, but can be changed in `userchrome.css`

### Changed

- Improve look of column splitters
  - Including support for horizontal splitters
- Add minimum width to rendered markdown TOC
- Hide `Spell checker` button on note toolbar by default
  - Can be changed in `userchrome.css`
- Improve look of synchronize area in side-bar
- Capitalize `ALL NOTES` entry in side-bar
- Improve look of toolbar buttons to better distinguish disabled ones

## [0.1.0] - 2020-11-07

- Initial Release
