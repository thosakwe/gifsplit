# gifsplit
![](ss/kite.0.gif) ![](ss/kite.1.gif)

![](ss/kite.2.gif) ![](ss/kite.3.gif)

A Python script that splits an animated GIF into four evenly-sized ones.

The goal was to create some nice APNG's to post on Twitter, but after finishing
the project, I realized that Twitter had disabled them... :(

## Licensing
**AGPL**. All distribution of this software must be open-sourced. If you run it on a server,
it also must be open-sourced.

## Requirements
Run `pip install -r requirements.txt`

* Python Pillow (7.1.2?)

## Usage
```
./gifsplit <file>
```

Produces `<file>.0.gif`, and so on, up to `<file>.3.gif`.
