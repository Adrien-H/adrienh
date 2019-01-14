### Adrien H

This is my website's codebase. This is not really meant to be reused,
it's open source mostly for philosophical reasons, but it's GPL-3.0
anyway so feel free to pick stuff and things up.

### Installation

Note that Symfony Dotenv Component is exceptionally a production
dependency, since this project is deployed in shared web hosting
service where I don't have access to environment variables. (: 

##### Development 
```bash
$ composer install
```

##### Production
```bash
$ composer install --no-dev -o -a
```