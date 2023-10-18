# About Stubs

Stubs are useful for type/constant and method arguments checking against:

- Libraries that are not included in the project;
- Libraries that are quite costly to analyse with the static analysis tools
  (so to gain analysis time).

# Stubs in this directory

- Several STUBS taken/updated from [git@github.com:TysonAndre/phan_stubs.git](git@github.com:TysonAndre/phan_stubs.git)
  Suggested on https://github.com/phan/phan/wiki/How-To-Use-Stubs#downloading-internal-stubs

- Some stubs generated with help from `php-stubs/generator`.

  Installed with:

  ```shell
  php .\composer.phar require --dev php-stubs/generator
  ```

  Then run `.../vendor/bin/generate-stub` at the root of the directory of the library
  that you want to generate a stub for.\
  You may clean up the stub to keep only the interfaces that are needed for checking.\
  Some generated stubs were manually updated to add better type hinting.
