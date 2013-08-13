A shell extension for [powerline](https://github.com/Lokaltog/powerline)

First do this.

    pip install osx-powerline-battery-segment

Then get your powerline ready to be [customized](https://powerline.readthedocs.org/en/latest/configuration.html#quick-guide).

This extension uses the highlight group `osx_battery`.  That is, you'll have to define colors for it.  I'm using this in my shell colorscheme json file.

    "osx_battery": { "fg": "brightred", "bg": "gray0" }

You'll then want to add something like this to your segment configuration.

    {
        "name": "osx_battery",
        "module": "osx_powerline_battery.segments"
    },
