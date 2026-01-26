<div align="center">
  <img src="https://github.com/vKaras1337/kde_modernclock/blob/main/assets/logo.jpg" width=100/>
  <h2>Modern Clock for KDE</h2>
  <p>A modern looking clock widget!</p>
</div>

<div align="center">
<a href="https://github.com/vKaras1337/kde_modernclock/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/vKaras1337/kde_modernclock?color=%233DAEE9&style=for-the-badge"></a>
<a href="https://github.com/vKaras1337/kde_modernclock/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/vKaras1337/kde_modernclock?color=%233DAEE9&style=for-the-badge"></a>
<a href="https://github.com/vKaras1337/kde_modernclock/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/vKaras1337/kde_modernclock?color=%233DAEE9&style=for-the-badge"></a>
</div>

<div align="center">
  <img src="https://github.com/vKaras1337/kde_modernclock/blob/main/assets/ss.png"/>
</div>

## Features
- **Localization Support**: Display day and date names in your local language or keep them in English
  - Toggle "Use local name" for day names (e.g., "SAMSTAG" instead of "SATURDAY")
  - Toggle "Use local name" for date formats with localized month names
- **Customizable Appearance**: Adjust font sizes, letter spacing, and colors for each element
- **Flexible Time Format**: Choose between 12-hour and 24-hour time display
- **Show/Hide Elements**: Independently control visibility of day, date, and time
- **Custom Style Characters**: Add decorative characters around the time display

## Installation
#### KDE Store (Preferred way)
1. Right click on the desktop
2. Click on "Add Widgets"
3. Click on "Get New Widgets"
4. Click on "Download New Plasma Widgets"
5. Search for "Modern Clock"
6. Click on "Install" and you're done!

#### From this repository
1. Clone this repository  
`git clone https://github.com/vKaras1337/kde_modernclock && cd kde_modernclock/`  
2. Install using the script  
`kpackagetool6 -i package/ -t Plasma/Applet`

## Credits
This project is a fork of the original [Modern Clock](https://github.com/prayag2/kde_modernclock) by [Prayag Jain](https://github.com/prayag2). I would like to thank the original author for creating this beautiful clock widget and making it open source.

The localization feature was inspired by [JortonMV's fork](https://github.com/JortonMV/kde_modernclock/commit/25b87b540ea7903ab4d72174d2f77888d2a7a909). Thanks for the great idea!

The custom font selection feature was inspired by [lunar-d's fork](https://github.com/lunar-d/kde_modernclock_fonts/commit/9a881d1e560a2c30c3defde109aaae81fc27baef). Thanks for the implementation!

This fork combines these improvements while maintaining the modern and clean design of the original.
