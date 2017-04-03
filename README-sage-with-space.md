# sage-with-space
[![Build Status](https://travis-ci.org/jojoee/sage-with-space.svg)](https://travis-ci.org/jojoee/sage-with-space)

Alternative repository for [sage](https://github.com/roots/sage) (wordpress starter theme) that have `space` according to [WordPress PHP Coding Standards](https://make.wordpress.org/core/handbook/best-practices/coding-standards/php/)

## My step to add space
1. Open `PhpStorm`
2. Import `Code Style` by copy and paste `sage-with-space.xml` into `PhpStorm` code style folder
3. Reformat code (`Ctrl + Alt + L`) by `Sage with space` scheme
4. Set `Filters` on `Reformat Code` dialog and run
    - Scope: `Project File`
    - File mask(s): `*.php`

## Updates
- [x] Fix `.travis.yml` by implementing [phpcs - WordPress-Coding-Standards](https://github.com/WordPress-Coding-Standards/WordPress-Coding-Standards)
- [ ] Upgrade to 8.5.1

## Changed from original Sage
- Add
  - README-sage-with-space.md
- Modify
  - .travis.yml
  - .gitignore
  - ruleset.xml

## Reference
- [WI-17786 Honor HTML Indentation Settings in PHP Files](https://youtrack.jetbrains.com/issue/WI-17786)
- [Reformatting Source Code](https://www.jetbrains.com/phpstorm/help/reformatting-source-code.html)
- [Reformat Code Dialog](https://www.jetbrains.com/phpstorm/help/reformat-code-dialog.html)
- [Code Style](https://www.jetbrains.com/phpstorm/help/code-style.html)
- [Code Style. PHP](https://www.jetbrains.com/phpstorm/help/code-style-php.html)
- [WordPress PHP Coding Standards](https://codex.wordpress.org/WordPress_Coding_Standards)
- [Delicious Brains WordPress coding styles for PhpStorm](https://github.com/deliciousbrains/wp-phpstorm-code-styles)
