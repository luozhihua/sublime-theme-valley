# Valley

## About

Valley is a simple theme and accompanying color scheme for Sublime Text 2 & 3. It is mostly derived from  [Soda](https://github.com/buymeasoda/soda-theme), the right place to start for any custom theme development for Sublime. Thanks Soda!

## Design

![Screen Shot!](https://raw.github.com/luozhihua/sublime-theme-valley/master/screenshots.png)


## Installation
Alternatively, if you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

While inside the `Packages` directory, clone the theme repository using the command below:

```bash
git clone git://github.com/luozhihua/sublime-theme-valley.git "Theme - Valley"
```

### Manual Installation
You can also install it manually by following these instructions:

1. [Download theme files](https://github.com/luozhihua/sublime-theme-valley/archive/master.zip)
2. Unzip the files and copy the folder newly created folder into your Sublime Text Packages directory with the name `Theme - Valley`. You can find that directory by selecting "Preferences > Browse Packages ...".


## Activating the Theme
Activate the theme by modifying your user preferences to include the following:

```javascript
{
  "theme": "Valley Dark.sublime-theme",
  "color_scheme": "Packages/Theme - Valley/Valley Dark.tmTheme"
}
```

If you need help locating your user preferences file, you can find it selecting "Preferences > Settings - User".

## Optional Settings
The following options can be set in your user preferences:

```javascript
{
  // Monokai color scheme (SublimeText's default) with Valley background color
  "color_scheme": "Packages/Theme - Valley/Valley Monokai.tmTheme",

  // Ability to change row height of sidebar tree
  // Options: xsmall, small, medium, large, xlarge
  "flatland_sidebar_tree_xsmall" : true
}
```
