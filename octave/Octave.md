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

## Matrices

### Rows
If you have a two dimensional matrix 

    a = ones(3:5)

you can view a row like so

    a(1,:)
    % ans = 1 1 1 1 1

You can also show columns in the same fashion

    a(:,1)
    % ans =     1
    %           1
    %           1

You can also assign to matrices columns or rows

    b = zeros(1,5)

    a(1,:) = b


