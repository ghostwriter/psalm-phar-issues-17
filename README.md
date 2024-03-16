# Issue-17

<https://github.com/psalm/phar/issues/17>

## Setps to reproduce the issue

1. Clone the repository

2. Run the following commands in the terminal:

```bash
cd package-nikic-php-parser-5x;

composer install;

# Run the Phar file
vendor/example/coding-standard/tools/psalm --init;

```

## Expecation

- The `psalm.phar` file should be downloaded as a composer package from the `example/coding-standard` package and the `vendor/example/coding-standard/tools/psalm` should be executed successfully.
