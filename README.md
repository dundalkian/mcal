# mcal - Mank Calendar

## About
mcal is a very simple calendar program for command line use written in python. 
The program allows for event creation, and sorted recall.

## Usage
Invoking 'mcal' with no arguments fetches existing events:

> mcal

To log the date of a generic event:

> mcal YYYY-MM-DD

Adding a title to the event:

> mcal YYYY-MM-DD -m "Food factory with the gang"

Editing calendar file directly. This command uses the shell env variable $EDITOR, if set, to open in your desired editor.
The fallback editor is vi.

> mcal -e

## Requirements

Python 3.X
