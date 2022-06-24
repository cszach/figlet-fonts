```
 _____ ___ ____ _      _      __             _       
|  ___|_ _/ ___| | ___| |_   / _| ___  _ __ | |_ ___ 
| |_   | | |  _| |/ _ \ __| | |_ / _ \| '_ \| __/ __|
|  _|  | | |_| | |  __/ |_  |  _| (_) | | | | |_\__ \
|_|   |___\____|_|\___|\__| |_|  \___/|_| |_|\__|___/
```

[live]: https://cszach.github.io/figlet-fonts

Fonts for FIGlet and TOIlet with a preview webpage. See it [here][live].

Fonts were collected by [xero](https://github.com/xero). I wrote the scripts to
build the preview webpage and install the fonts.

Directory structure
-------------------

- `control`: control files for FIGlet;
- `fonts`: font files for FIGlet and TOIlet;
- `misc`: other files found in the original collection.

Install
-------

You can install the fonts by simply running

```bash
sudo ./install.sh
```

This will install the fonts to `/usr/share/figlet/`.

Build the preview
-----------------

Build the preview by running

```bash
./build.sh
```

Options (all are optional):

- `-w`: output width for FIGlet's formatting. Default is `180`;
- `-t`: the preview text. Default is `FIGlet`;
- `-f`: output file name. Default is `index.html`;
- `-v`: print the configuration before generating the preview.

Example:

```bash
./build.sh -v -w 120 -t "Moo"
```

Contribute
----------

Feel free to open a pull request if you have a font that is missing.
