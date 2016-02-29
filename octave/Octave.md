# Gnu Octave 

## Setup on Mac OSX
First of all, use brew

	brew tap homebrew/science
	brew update && brew upgrade
	brew install octave

To use plotting you probably need to reinstall gnuplot with x11 support.

	brew uninstall gnuplot
	brew install gnuplot --with-x

This still won't work until you restart

Note: you'll also need to have Quartz installed.
