# Vuejs  Autocomplete Compopent ([Demo](https://mrabbani.github.io/examples/vue_typeahead))

Hope your are familiar with [node](http://nodejs.org) and able to compile [vuejs](https://vuejs.org/v2/guide/components.html) component.

## Installation

    npm install vuejs-autocomplete --save  

## Properties

- `value`: `String` - The value input field;
- `classes`: `String` - The name of class for input field
- `suggestionTemplate`: `String` - A Custom template which will be displayed as suggestion list
- `defaultSuggestion` : `Boolean` - 'true' if you want to enable default suggestion on focus.
- `local`: `Array` - If you want to pass your existing data for auto-completion items.
- `remote`: `String` - The remote(server) url to fetch auto-completion items.
- `responseWrapper`: `String` - The `key` name which is used ot wrap the response.

## Events

- `selected` : This event is fired when an item is selected and passed as argument.

# [Vuejs-autocomplete Example](https://github.com/mrabbani/vuejs-autocomple-example)

## memo

### to use browserSync

install composer
```
% php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
% php -r "if (hash_file('SHA384', 'composer-setup.php') === '55d6ead61b29c7bdee5cccfb50076874187bd9f21f65d8991d46ec5cc90518f447387fb9f76ebae1fbbacf329e583e30') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
% php composer-setup.php
% php -r "unlink('composer-setup.php');"
% mkdir bin
% hp composer-setup.php --install-dir=bin --filename=composer
% mv composer.phar /usr/local/bin/composer
```

install laravel
```
% composer global require "laravel/installer=~1.1"
```

create laravel projects
```
composer create-project laravel/laravel 4.2 --prefer-dist
```
