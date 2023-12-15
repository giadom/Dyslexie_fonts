![ALternative text: "American Shipping off the Rock of Gibraltar, Ivan Kostantinovich Aivazovsky (1873)"](https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/Aivazovsky_gibraltar.jpg/575px-Aivazovsky_gibraltar.jpg "American Shipping off the Rock of Gibraltar, Ivan Kostantinovich Aivazovsky (1873)")
# Unordered list
- leggimi© font:  
  <https://www.sinnos.org/leggimi/le-font/>
- Biancoenero© font:  
  <https://www.biancoeneroedizioni.it/font/>
- Sylexiad Serif©, Sylexiad Sans©, Dine© and Circs© fonts:  
  <https://www.sylexiad.com/download-typefaces/index.html>
- Dyslexie font©:  
  <https://www.dyslexiefont.com/en/home/>
- OpenDyslexic© font:  
  <https://opendyslexic.org/>

# How to install a font in a GNU/Linux operating system based on Ubuntu
If you need the fonts to be available system-wide:
1. **copy** the fonts (with super user privileges) into the following directory (or inside its inner directories):  
   `/usr/local/share/fonts`
2. **reboot** the system **or run** the following command (even with low privileges):  
   `fc-cache -f -v`

To **check** that they are correctly installed, just run the following command:  
`fc-list | grep <name-of-the-font-installed>`
