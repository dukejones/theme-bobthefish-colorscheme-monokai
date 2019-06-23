# theme-bobthefish-colorschemes
A set of custom color schemes for the inimitable Bob the Fish theme.

This could be a bunch of custom themes, or end up just being the Monokai one.  This should be a foundation to work off of for anyone wanting the massive functionality Bob the Fish gives us while also craving a specific aesthetic sensibility, and the ability to share this with others.

Use
---

Examples here are using [triton](https://github.com/dukejones/triton), but it should also work with other fish shell package managers.

```fish

# in ~/.config/fish/config.fish or perhaps ~/.config/fish/conf.d/theme-settings.fish

triton dukejones/theme-bobthefish-colorschemes
set -g theme_color_scheme monokai 


```

RFP
---
Do you have a color scheme that you love, yet also want all the rich features of bob the fish? Copy the `__bobthefish_color_scheme_monokai` function into your own function/file and submit a pull request!

The naming scheme must be:

`function __bobthefish_color_scheme_$myname`

Then

`set -g theme_color_scheme $myname`

to activate it.

TODO
----

Include screenshots of the different themes here in the readme.
