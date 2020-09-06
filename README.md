# Awesome PHP Migrations

Awesome list about PHP code bases migrations, legacy refactoring and instant upgrades. (This list is not about database migrations.)

Do you have an old PHP project that you need to migrate to newer version, different framework, templating system or config format? This is the place.

<br>

## What to Contribute?

The goal of this post is to **keep it short, useful and reliable**. Work with legacy often very frustrating, as behind corner there is a new black hole of problems to suck us in. 

Our mission is to **keep this list practical and light** so we can see the light in every legacy project :)

- Welcomed are: tools, posts, case-studies and short videos.
- Avoid conference videos, as they're long and without clickable resources.
- Avoid books, as they're opinionated, long, often outdated and hard to use. If you need to contribute last 2, try [awesome-php](https://github.com/ziadoz/awesome-php).
 
<br><br>

## Generic Tools

- [rector/rector](https://github.com/rectorphp/rector) - Tool for Instant Upgrades and Instant Refactoring of any PHP 5.3+ code

## Framework Migrations

### Nette to Symfony

- How we Migrated from Nette to Symfony in 3 Weeks **[case study]**
    - [Part 1](https://tomasvotruba.com/blog/2019/02/21/how-we-migrated-from-nette-to-symfony-in-3-weeks-part-1/)
    - [Part 2 -  Escaping Semantic Hell](https://tomasvotruba.com/blog/2019/03/07/why-we-migrated-from-nette-to-symfony-in-3-weeks-part-2/)
    - [Part 3 - Brain Drain Dead Packages-Lock](https://tomasvotruba.com/blog/2019/03/11/why-we-migrated-from-nette-to-symfony-in-3-weeks-part-3/)
    - [Drop RobotLoader and let Composer Deal with Autoloading](https://tomasvotruba.com/blog/2020/06/08/drop-robot-loader-and-let-composer-deal-with-autoloading/)

## Legacy Unfreeze

- [migrify/vendor-patches](https://github.com/migrify/vendor-patches) - PHP tool to effectively and temporarily patch your `/vendor` files

## Static Removal

- [migrify/static-detector](https://github.com/migrify/static-detector) - PHP tool that shows where do you have static method and where they're called from

## Dev Tools

- [migrify/sniffer-fixer-to-ecs](https://github.com/migrify/sniffer-fixer-to-ecs) - Convert PHP CS Fixer or PHP_CodeSniffer config to `ecs.php` for [EasyCodingStandard](https://github.com/symplify/easy-coding-standard) 
    - [How to Migrate From PHP CS Fixer to EasyCodingStandard in 6 Steps](https://tomasvotruba.com/blog/2018/06/07/how-to-migrate-from-php-cs-fixer-to-easy-coding-standard/) **[post]**
    - [How to Migrate From PHP_CodeSniffer to EasyCodingStandard in 7 Steps](https://tomasvotruba.com/blog/2018/06/04/how-to-migrate-from-php-code-sniffer-to-easy-coding-standard/) **[post]**

## Config Migrations

- [migrify/neon-to-yaml](https://github.com/migrify/neon-to-yaml) - PHP tool that migrates NEON to YAML syntax
    - [Neon vs. Yaml and How to Migrate Between Them](https://tomasvotruba.com/blog/2018/03/12/neon-vs-yaml-and-how-to-migrate-between-them/) **[post]**
- [migrify/config-transformer](https://github.com/migrify/config-transformer) - PHP tool that migrates Symfony configs with YAML/XML syntax to PHP 
    - [How to Switch from YAML/XML Configs to PHP Today with Migrify](https://tomasvotruba.com/blog/2020/07/27/how-to-switch-from-yaml-xml-configs-to-php-today-with-migrify/) **[post]**  

## Template Migrations

- [migrify/latte-to-twig](https://github.com/migrify/latte-to-twig) - PHP tool that migrated LATTE templates to TWIG 

## Continuous Integration Checks

- [migrify/template-checker](https://github.com/migrify/template-checker) - PHP tool, that checks `$this->render()` contains existing template files
- [migrify/class-presence](https://github.com/migrify/class-presence) - PHP tool that checks NEON/YAML/TWIG/LATTE files for existing classes and class constants 

## File System Migrations

- [migrify/psr4-switcher](https://github.com/migrify/psr4-switcher) - PHP tool that helps you to migrate random classes to PSR-4
    - [How to Patch a Package in Vendor, Yet Allow its Updates](https://tomasvotruba.com/blog/2020/07/02/how-to-patch-package-in-vendor-yet-allow-its-updates/) **[post]**

## Symfony Dead Code

- [migrify/symfony-route-usage](https://github.com/migrify/symfony-route-usage) - Symfony bundle that logs route usage and show unused routes

## Laravel Dead Code

- [julienbourdeau/route-usage](https://github.com/julienbourdeau/route-usage) - Laravel bundle that logs route usage and show unused routes
