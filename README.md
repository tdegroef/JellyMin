# JellyMin
A minimalistic theme for Jellyfin mediaserver created using CSS overrides

Note that I maintain this theme to be compatible with whatever version of Jellyfin I am currently using. Which is usually the latest stable release. You can therefore assume that using the theme on older versions may not work, but also that if a new release breaks something, that I will fix it. If you encounter unthemed elements or something broken, open an issue.

To use the theme copy paste the line below into "Dashboard > General > Custom CSS" and click save, it will apply immediately server-wide to all users on top of any theme they may be using. To remove the theme, clear the "Custom CSS" field and then click save.

```css
@import url('https://tdegroef.github.io/JellyMin/default_style.css');
```