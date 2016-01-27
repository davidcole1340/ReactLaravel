## ReactLaravel

Simple ReactPHP HTTP server that serves Laravel 5.2 applications.

### Installation and Usage

You can either clone the repository or install it globally via Composer:

#### Globally via Composer (reccomended)

```bash
composer global require david-cole/react-laravel
# Make sure ~/.composer/vendor/bin is in your PATH
react-laravel <path-to-laravel> [port=8080] [ip=127.0.0.1] [loglevel=info]
```

#### Cloning the Repository

```bash
git clone https://github.com/uniquoooo/ReactLaravel.git
cd ReactLaravel
composer install
./react-laravel <path-to-laravel> [port=8080] [ip=127.0.0.1] [loglevel=info]
```