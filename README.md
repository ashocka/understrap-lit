
## Installation
Have wordpress installed and checkout this repository inside wp-content/themes/ (then enable understrap theme in WP settings).

## Development
This theme is based on [understrap wordpress theme](https://understrap.com/) which utilizes [Bootstrap 4 CSS framework](https://getbootstrap.com/docs/4.0/getting-started/introduction/).
Run `gulp watch` while developing (this will compile sass to css on the fly).
The main css is in sass/theme/_theme.scss and variables in sass/theme/_theme_variables.scss (you can override Bootstrap 4 variables here as well, take a look at [Bootstrap 4 documentation](https://getbootstrap.com/docs/4.0/getting-started/introduction/) for more info).

## Deploy
Run `gulp dist` for deploy, this will compile the theme in the dist/ directory, then upload dist/ to production wordpress' themes/ directory.



