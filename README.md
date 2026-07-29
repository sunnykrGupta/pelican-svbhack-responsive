## pelican-svbtle-responsive

pelican-svbtle-responsive is a responsive theme for Pelican. Customized from forks.

## Demo

You can see the [theme in action](https://sunnykrgupta.github.io/).

![screenshot](screenshot.png)


## Features

- Clean and responsive design
- Customizable Syntax highlighting via [pygments][pygments]
- Google analytics
- X (Twitter) Widgets [twitter-cards]
- Navigator for social sites on top : google+, x, github, linkedin, email

[Twitter-Widgets]: https://developer.x.com/en/docs/twitter-for-websites/timelines/overview


## Installation

### Configure pelicanconf.py

Edit `pelicanconf.py` in your site root:

```python
# Point THEME at the cloned theme directory (use an absolute path or path relative to pelicanconf.py)
THEME = "themes/pelican-svbhack-responsive"
```


## Configurations

Supports a number of common global variables but patches are welcomed if you need better support.

- `GOOGLE_ANALYTICS` to use Google Analytics, set this var to your UA-XYZ code

- `USER_LOGO_URL` to replace the logo placeholder, put your logo in content/images/your_logo.png and make this var point to `SITEURL + '/static/images/your_logo.png'`

- `TAGLINE` some text rendered right below the logo

-  `SITEURL = http://localhost:8000` When developing locally.

-  `widget_profile_url = "https://x.com/@user"`
-  `widget_profile_name = "@user"`
-  `widget_id_int = "WIDGET-ID"`

Social nav icons load from `theme/images/Mono/webicon-<name>.png`. Use `x` as the SOCIAL name for the X logo. Example:

```python
SOCIAL = (
    ("linkedin", "https://www.linkedin.com/in/you/"),
    ("github", "https://github.com/you"),
    ("x", "https://x.com/you"),
    ("medium", "https://medium.com/@you"),
    ("mail", "mailto:you@example.com"),
)
```



## AUTHOR

pelican-svbhack-responsive is authored by Sunny Kumar.

## LICENSE

Released under MIT License, full details in `LICENSE` file.
