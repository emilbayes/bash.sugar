# Bash.sugar

A sugar adding sweet [Bash][bash] support to [Espresso 2.0][espresso].

[espresso]: <http://macrabbit.com/espresso/> "Espresso, by MacRabbit"
[bash]: <http://www.gnu.org/software/bash/> "Bash – GNU Project"


## Installation

Rename the folder to Bash.sugar and double click. Restart Espresso and you're good to go!

Another option is Terminal:

	cd ~/Library/Application\ Support/Espresso/Sugars/
	git clone git://github.com/tixz/Bash.sugar.git

## Usage

The sugar provides code highlighting and CodeSense for most basic bash scripting.
*Note:* There seems to be a problem with CodeSense when typing on the last line of a document in Espresso. To fix this add a couple of lines to the end of your file and CodeSense functions again. Also not all completions will show up when in the list window or when pressing Esc
CodeSense includes:

	\#! (Shebang)
	<< (Heredoc)

	function
	if … then
	elif … then
	else … then
	case … in
	for … do
	while … do
	until … do

Suggestions and improvements are much appreciated!

## License
Copyright (c) 2011 Emil Melgaard. Originally developed by Martin Kühl, 2009.

This sugar is released under the MIT License. See [`LICENSE`][license] for details.

[license]: http://github.com/mkhl/bash.sugar/raw/master/LICENSE
