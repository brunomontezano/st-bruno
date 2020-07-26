# My st (simple terminal) build

![Screenshot2020-07-2615:52:10](https://user-images.githubusercontent.com/65104127/88487071-8396ef00-cf58-11ea-99b3-2a7ad960ce73.png)

st is a simple terminal emulator for X which sucks less (st is created by the [suckless](https://suckless.org) team).  This is my personal build of st, based on DistroTube's build.  I used some patches in this build to make st more like myself.  The patches I added to this build include:
+ alpha (for transparency)
+ font2 (to allow setting more than one font, useful when the default font has missing glyphs)
+ scrollback (scrollback through terminal using Shift+PageUp/PageDown.)
+ scrollback mouse altscreen (allows scrolling using Shift+MouseWheel.)

# How to install st-bruno?

Download the source code from this repository or, preferably, use a git clone:

	git clone https://github.com/brunomontezano/st-bruno
	cd st-bruno
    sudo make clean install
	
NOTE: Installing st-bruno will overwrite your existing st installation so make a backup of your current config if you need.
