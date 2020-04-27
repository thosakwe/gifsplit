# gifsplit
A Python script that splits an animated GIF into four evenly-sized ones.

The goal was to create some nice APNG's to post on Twitter, but after finishing
the project, I realized that Twitter had disabled them... :(

## Requirements
Run `pip install -r requirements.txt`

* Python Pillow (7.1.2?)

## Usage
```
./gifsplit <file>
```

Produces `<file>.0.gif`, and so on, up to `<file>.3.gif`.
