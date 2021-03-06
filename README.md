# Basic login authentication App

This is a web application that allows the user to try a basic login authentication. It performs creating an account and signing in using the account that the user created. It has modern design and basic functionality.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See the instructions below on how to deploy the project on a live system.

## Preview
![App gif](gif/login.gif)

### Prerequisites

Things you need to be able to use this project:

* [Chrome](https://www.google.com/intl/en_ph/chrome/) or [Firefox](https://www.mozilla.org/en-US/firefox/new/)
* [Yarn](https://classic.yarnpkg.com/en/docs/install/#windows-stable)
* [PHP](https://www.php.net/)
* Command prompt

### Installation

Type this in cmd:

```
cd../Project
```
```
yarn install
```

After that, go to your local host phpMyAdmin
```
create a database with a name of 'simplelogin'
```
![App screenshot](https://i.imgur.com/6G1BRGB.png)

Last is go back to cmd and type:
```
php artisan migrate
```
```
php artisan serve
```

## Built With

* [Vue](https://vuejs.org/)
* [Vuetify](https://vuetifyjs.com/en/)
* [Vuex](https://vuex.vuejs.org/)
* [Vue Router](https://router.vuejs.org/)
* [Laravel](https://laravel.com/)

## Authors

* **Charnel Clamosa** - [charnelclamosa](https://github.com/charnelclamosa)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

