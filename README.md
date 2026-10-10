# Dune Z

> **Personal fork.** This repository is my own fork of [Dune Rev](https://github.com/hugsyf/dune-rev)
> by hugsyf, which itself builds on [Dune](https://github.com/sakasakiking/Dune) by sakasakiking.
> It carries tweaks I made for my own Playnite setup and is shared as-is, without support.
> For the original, maintained theme, releases and issue tracker, use
> **[hugsyf/dune-rev](https://github.com/hugsyf/dune-rev)**.
>
> My changes: source icons on grid covers instead of the banner strip, four stat cards in one
> row, a wider details column in Grid Details, and more compact DLC, Main story estimate and
> Achievements cards.

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Playnite](https://img.shields.io/badge/Playnite-Desktop-6c5ce7.svg)](https://playnite.link/)

A dark, Fluent-inspired theme for Playnite Desktop.

[About](#about) · [Screenshots](#screenshots) · [Changelog](CHANGELOG.md)

**Based on Dune Rev [2.3.0](https://github.com/hugsyf/dune-rev/releases/tag/v2.3.0)**

## Screenshots

These screenshots come from upstream Dune Rev and use optional extensions and game metadata. This fork shows source icons on grid covers instead of the banner strip. Your layout and available content
depend on the extensions, theme settings and data in your library.

### Details View

Game logo and Hero media, play controls, metadata and expandable summary cards.

![Details View with a game logo, Hero video, play controls, summary cards and details sidebar](Screenshots/details-view.png)

### Grid View

Rounded covers with platform or store banners, play time and completion status.

![Grid View with Steam, Windows, Android, PlayStation and Xbox cover banners](Screenshots/grid-view.png)

### Grid Details View

Browse covers alongside a game's Hero, actions and plugin cards.

![Grid Details View with a cover grid beside Hero media and expandable plugin cards](Screenshots/grid-details-view.png)

<details>
<summary><strong>More: estimates, reviews, activity, achievements and screenshots</strong></summary>

**Completion estimates and Steam reviews**

Expand a summary card while keeping the content tabs available below it.

![Expanded HowLongToBeat estimates above the Steam reviews tab and details sidebar](Screenshots/completion-estimates-and-reviews.png)

**Activity and recorded performance**

Session history and a taller performance chart share the expanded activity panel.

![GameActivity session history and recorded CPU, GPU, memory and FPS charts](Screenshots/activity-and-performance.png)

**Achievements**

Latest unlock and the achievement list appear in the expanded card.

![Expanded Playnite Achievements panel with the latest unlock and achievement list](Screenshots/achievements.png)

**Store screenshots in Grid Details**

Store screenshots have their own tab with a preview and selectable thumbnails.

![Grid Details with completion estimates expanded and the store screenshots tab selected](Screenshots/grid-details-store-screenshots.png)

</details>

## About

Based on [Dune](https://github.com/sakasakiking/Dune) by sakasakiking, Dune Rev combines
a low-glare library view with quick access to game information and extension content.

### Features

- **Three library layouts.** Details, Grid and Grid Details with rounded surfaces,
  game logos, screenshots and videos. Missing logos can fall back to the game title.
- **Cover banners.** Edge-to-edge platform or store/source strips follow the cover's
  rounded corners. PC games can show Steam, Epic or Xbox; consoles keep platform labels.
  Playnite/manual games prefer their first platform. Each preference can be switched off.
- **Expandable summaries.** Play time, completion status, achievements, completion
  estimates, activity, requirements, languages and DLC. Click a supported plugin card
  to expand its details; click again to collapse. Separate buttons open plugin windows.
- **Content tabs.** Overview, Related games, Play Notes, Store screenshots, Personal
  screenshots, Reviews and News are peers. Relevant extensions and their integration
  settings determine which tabs are available. Empty related-game sections are hidden.
- **Useful media and records.** Screenshot previews and thumbnails, notes editing,
  latest achievement unlocks, session history and recorded performance charts.
- **Quieter cover controls.** Multi-copy selection appears below covers on hover or
  keyboard focus. Single-copy games omit it. Play/details actions also support keyboard
  focus; personal-score badges and reduced cover motion are optional.
- **Adjustable presentation.** ThemeModifier controls Hero size, blur and shading,
  content widths, summary visibility, panel heights, cover labels and colors.
  The optional top-bar shortcut opens theme settings.
- **Consistent controls.** Matching toolbar feedback, tab fonts, checkboxes,
  translucent dropdown menus and buttons in supported plugin panels.

### Installation

Requires **Playnite 10.57 or newer**. Extensions are optional.

1. Download a published `.pthm` from [Releases](https://github.com/hugsyf/dune-rev/releases)
   and open it to install.
2. Select **Dune Rev** in Playnite's Desktop theme settings.
3. Install any extensions you want from Playnite's add-on browser, then enable their
   theme integrations in the extension settings.

The theme is also available through the
[Playnite add-on page](https://playnite.link/addons.html#DuneRev_aa8df0f9-9406-4ea6-a31a-3bd13853fd40).

Achievement integration uses **Playnite Achievements**. Latest-unlock display requires
**4.0 or newer**. Users keeping SuccessStory can use Dune Rev 1.1.1.

### Optional extensions

Install only the content you want. The theme does not fetch or record extension data itself.

| Extension | What it adds |
| --- | --- |
| Extra Metadata Loader | Game logos and videos |
| BackgroundChanger | Alternative backgrounds |
| Playnite Achievements | Progress, latest unlock and achievement list |
| HowLongToBeat | Available completion estimates and progress |
| GameActivity | Last session, recent activity, session history and recorded performance |
| SystemChecker | System requirements status and details |
| CheckLocalizations | Preferred-language summary and interface/audio/subtitle support |
| CheckDlc | DLC counts, ownership and all/owned/not-owned lists |
| Play Notes | Notes tab with the plugin's editing and import controls |
| Game Relations | Same-series and similar games from your library |
| Steam Store Screenshots Viewer | Store screenshot preview, thumbnails and viewer commands |
| ScreenshotsVisualizer | Personal screenshots and an optional native grid gallery |
| Review Viewer | Steam reviews and review filters |
| Steam News and Players Viewer | News and current players online |
| DuplicateHider | Selection between multiple copies of a game |
| Library Management | Feature icons |
| ThemeExtras | Favorites, completion-status/rating editing, banner overrides and settings command |
| ThemeModifier | Theme layout, visibility and appearance settings |

### Customize the theme

Install **ThemeModifier** to change theme options. The top-bar settings shortcut
also requires **ThemeExtras**. The options are grouped by purpose:

| Settings group | Main controls |
| --- | --- |
| Global layout | Top bar, compact Hero, blur/shading, reduced motion and title fallback |
| Details View layout | Content/sidebar widths and game logos |
| Grid View layout | Details-pane width and logo size |
| Summary and extension content | Summary cards, detailed summaries, language and DLC details |
| Extension panels | Notes, related games, screenshots, rating editing and panel/chart heights |
| Grid cover display | Banners, store preference, manual-game fallback, copy selection and score badges |
| Colors | Window, card, popup, border and icon colors |

Key defaults in a fresh installation:

| Option | Default |
| --- | --- |
| Platform/source cover banners | On |
| Prefer store/source banners for PC games | On |
| Prefer platform banners for Playnite/manual games | On |
| Multi-copy selector on hover/focus | On |
| Notes, related games, store and personal screenshot integrations | On, when available |
| Missing-logo title fallback and theme-settings shortcut | On, when available |
| Personal-rating editing through ThemeExtras | On, when available |
| Compact Hero, detailed summaries and reduced cover motion | Off |
| Personal-score badges on Grid covers | Off |
| Prefer ScreenshotsVisualizer's native grid gallery | Off |
| Performance chart minimum height | 360 px |

To use the personal screenshot grid, enable the matching picture-list integration
in **ScreenshotsVisualizer** as well as the theme preference. Set preferred languages
in **CheckLocalizations** for its summary. GameActivity performance charts require
performance data recorded by the plugin.

#### Custom cover banners

Bundled platform/store artwork works without ThemeExtras. ThemeExtras can supply
banner overrides and preserve the banner folder during theme updates.

Put custom PNGs in the installed theme's folders below, using the corresponding
name or identifier as the filename:

| Folder | Filename example or matching rule |
| --- | --- |
| `Images/Banners/PlatformSpecId` | `pc_windows.png` |
| `Images/Banners/PlatformName` | Exact platform name + `.png` |
| `Images/Banners/PluginId` | Library plugin GUID + `.png` |
| `Images/Banners/SourceName` | Exact source name + `.png` |

Restart Playnite after changing banner files. For a game with several platforms,
the banner uses its first platform; the metadata row can still list all platforms.

### Help and feedback

If a card or tab is missing, check that its extension is installed, its theme
integration is enabled, the theme preference is on, and the selected game has
the relevant data. Play Notes also provides an empty-state prompt for creating notes.

See the [changelog](CHANGELOG.md) for changes. Report problems through
[GitHub Issues](https://github.com/hugsyf/dune-rev/issues), including the view,
a screenshot, relevant extensions and the Playnite log when the theme fails to load.

### Credits

Based on [Dune](https://github.com/sakasakiking/Dune), with design inspiration from Mythic.
Platform and store/source banner artwork comes from
[KNARZnite](https://github.com/HerrKnarz/Playnite-Theme-KNARZnite);
its MIT license and source revision are included with the banners.
Dune Rev is distributed under the [MIT License](LICENSE).
