# Dark Field theme for Jellyfin

_A modern dark theme with transparency and a nice shade of green._

- [Screenshots](#screenshots)
- [About](#about)
- [Installing](#installing)

## Screenshots

Home Page:

![home](https://github.com/user-attachments/assets/d967f2d9-4476-4c85-862b-29c07d34e645)

Movie Details:

![movie details](https://github.com/user-attachments/assets/90a23921-68e8-4e15-9b4f-e0cff5858855)

TV Show Series:

https://github.com/user-attachments/assets/ddb24b9a-de9f-4019-9fe0-9b0b47da1009

## About

This theme is a tweaked fork of the excellent
[Scyfin](https://github.com/loof2736/scyfin) theme, so full credit there for
the main bulk of this work.

The changes made involve:

- Darker backgrounds, and a nice shade of green as the primary accent color.
- Moving more values to constants for easier overwriting if you want to
consistently edit and tweak things to your own liking.
- A few fixes for things missed or not set in Scyfin.
- More transparency including the now playing bar, and hover background on item
details pages.
- Smaller play state icons so they don't cover up so much of the posters.
- Some padding, margin and border radius tweaks to make some of the hover
interactions a bit cleaner.

Try them both out, to get an idea of what one works best for you.

## Installing

1. Navigate to your Jellyfin server's Admin Dashboard > General tab.
1. In the `Custom CSS code` field add the import url:
`@import url('https://cdn.jsdelivr.net/gh/pointless-existence/jellyfin-dark-field-theme@latest/dark-field-theme.css');`

Force refresh your browser and the theme should load.
