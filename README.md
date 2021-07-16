# Binford® Tools: Project 

A template for custom [Magento 2][1] projects.

## Intro

A custom Magento 2 project that provides **a minimal setup** and only contains project-specific store configuration.

It serves as an entry point for further customizations contained in [project-agnostic, standalone components][2], which can be orchestrated as needed via [Composer][3].

## How to install

[Install dependencies][4] via Composer.

```sh
$ composer install
```

[Install the project][5] via Magento’s CLI.

```sh
$ magento setup:install --<option>=<value> ... --<option>=<value>
```

## How to update

[Update dependencies][6] via Composer.

```sh
$ composer update
```

[Update the project][7] via Magento’s CLI.

```sh
$ magento setup:upgrade
$ magento setup:di:compile
```

## We’re hiring!

We’re currently looking for passionate ~~masochists~~ **PHP & Magento developers** to join our e-commerce team **in Munich**. Sounds interesting? Just drop me a line via [j.scherbl@techdivision.com][8].

[1]: https://magento.com/products/magento-open-source
[2]: https://github.com/binford-tools/composer
[3]: https://getcomposer.org
[4]: https://getcomposer.org/doc/03-cli.md#install-i
[5]: https://devdocs.magento.com/guides/v2.3/install-gde/install/cli/install-cli-install.html
[6]: https://getcomposer.org/doc/03-cli.md#update-u
[7]: https://devdocs.magento.com/guides/v2.3/install-gde/install/cli/install-cli-subcommands-db-upgr.html
[8]: mailto:j.scherbl@techdivision.com
