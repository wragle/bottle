* Message in a Bottle
A command-line based program that stores messages to be accessed at a later date

** Installation
Copy bottle.py into a directory which is part of your system PATH. The bottles will be stored in `$HOME/.local/share/bottle/bottles.json` by default. Changing the `BOTTLES_DIRECTORY` in bottle.py will change where they are stored and read from.

** Usage
Access the help menu
```bash
bottle --help
```
Create a new bottle
```bash
bottle create
```
List bottles
```bash
bottle list
```
Smash (destroy) a bottle
```bash
bottle smash [BOTTLE NUMBER]
```
Count bottles of a specific type
```bash
bottle count [BOTTLE TYPE]
```
