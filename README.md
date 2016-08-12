Adwaita-dark-gtk2
=================

This is clone of gnome3 Adwaita theme
It is tuned to work with GTK-2 application exactly as with GTK-3
There is still minor issues, but work in progress

INSTALLATION
=================

#### 1. Install theme itself

* Install the theme in either /usr/share/themes, or in your home directory, in ~/.local/share/themes and ~/.themes (see http://worldofgnome.org/gtk-theme-ing-issue-in-gnome-3-10/ for an explaination 
  of why both are required)
* go to the desired theme folder:
`$ cd /usr/share/themes`
* clone theme's repo:
`$ git clone <URI> Adwaita-dark`
* e.g.:
  `$ git clone https://github.com/<github-user>/Adwaita-dark-gtk2 Adwaita-dark`
  * You'll have to use sudo here if installing in a system-wide location
* for versions of gnome-shell <= 3.12 switch to 3.12 tag:
`$ sudo git checkout gnome_3.12`
* launch gnome-tweak-tool
* go to Appearance section
* change "Window" and "GTK+" themes to Adwaita-dark

#### 2. Configure gnome apps
##### Gnome Terminal
* Open gnome-terminal
* go to Edit->Preferences menu
* select "Use dark theme variant" checkbox

##### Gedit
* Open gedit
* go to Preferences (by clicking on the name of application in the top panel of gnome-shell)
* Open tab "Font and Colors"
* Select any dark theme you like (I prefer Oblivion)

AUTHORS
=================
originally cloned by Roi M (https://plus.google.com/+RoiMMrNucky/posts/KsybAs8Htgc)
tuned and updated by axxapy
further tuned by Jeremy N (https://plus.google.com/102019683200554479931)
Thanatermesis did minor changes for compatibility in Elive
