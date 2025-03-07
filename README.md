# Elegant-Floorp 
This is a simple userChrome.css file to make Floorp Browser elegant and more compact than compact mode.
The theme I used is Floorp Fluential UI in Settings>Design>
In the Customize Toolbar settings I dragged bookmark bar to the right side of url bar and enabled compact mode in Density tab located at the bottom

I need to document all the other changes I made in about:flags eventually.
It's easier to install tabliss extension but clutters the URL bar for me 
Go to the url bar and type about:flags 
so I set the flag: 
browser.startup.homepage = https://web.tabliss.io/

floorp.newtab.overrides.newtaburl = https://web.tabliss.io/

Floorp needs a restart after this flag has been set to apply the effect.

## Screenshots
### Dark Mode
![image](https://github.com/user-attachments/assets/09790d43-f390-4cda-90b7-20b1e40e90ec)

### Light Mode
![image](https://github.com/user-attachments/assets/4126c559-8b82-4ce0-b33f-e15327294572)

The codes were modified from https://github.com/datguypiko/Firefox-Mod-Blur
I made this for personal use but turned out quite useful so I hope it's ok with the original author of the theme.
