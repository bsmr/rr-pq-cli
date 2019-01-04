<p align="center">
  <img alt="Progress Quest" src="http://progressquest.com/pq.png">
</p>

Relive the great adventure… this time in the terminal realm!

- Progress Quest site:  http://progressquest.com/
- Online version:       http://progressquest.com/play/
- Original version:     https://bitbucket.org/grumdrig/pq

## Features

- Faithful port of the game logic
- Saves (with backups) to `$XDG_CONFIG_HOME/pqcli/save.dat`
- Terminal interface that comes in 3 flavors:
    - Rich and colorful, but CPU intensive (`--urwid`)
    - Simple, but easy on CPU, friendly for embedded environments (`--curses`)
    - Minimal, suitable for raw grind (`--basic`)
- Ideal to run on your server

## How it looks like

Urwid version:

![Screenshot](screen-urwid.png)

Curses version:

![Screenshot](screen-curses.png)

Basic version:

![Screenshot](screen-basic.png)

## How to install

If you have Python 3.7, just run `pip install --user pqcli` and you're good to go!
Then type `pqcli` to run the game.

In case if you want to use the git version, the process is just a little bit
more complex:

```console
$ git clone https://github.com/rr-/pq-cli.git
$ cd pq-cli
$ pip install --user .
```
