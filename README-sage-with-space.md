# sage-with-space
[![Build Status](https://travis-ci.org/jojoee/sage-with-space.svg)](https://travis-ci.org/jojoee/sage-with-space)

Alternative repository for [sage](https://github.com/roots/sage) (wordpress starter theme) that have `space` according to [WordPress PHP Coding Standards](https://make.wordpress.org/core/handbook/best-practices/coding-standards/php/)

## Changed from original Sage
- Add
  - README-sage-with-space.md
- Modify
  - .travis.yml
  - .gitignore
  - ruleset.xml
  - package.json

## My step to change code style
1. Setup
  - WordPress server
  - Node.js, yarn, bower
  - Composer, PHP_CodeSniffer and [phpcs - WordPress-Coding-Standards](https://github.com/WordPress-Coding-Standards/WordPress-Coding-Standards)
2. Using `sage-with-space.xml` to reformat all php files by PhpStorm
3. Fix phpcs by `phpcbf -p ./*.php --standard=ruleset.xml`
4. Fix phpcs (manual)
5. Recheck phpcs by `phpcs -p ./*.php --standard=ruleset.xml`

## Updates 
- [ ] Upgrade to 8.5.1

## Reference
- [WI-17786 Honor HTML Indentation Settings in PHP Files](https://youtrack.jetbrains.com/issue/WI-17786)
- [Reformatting Source Code](https://www.jetbrains.com/phpstorm/help/reformatting-source-code.html)
- [Reformat Code Dialog](https://www.jetbrains.com/phpstorm/help/reformat-code-dialog.html)
- [Code Style](https://www.jetbrains.com/phpstorm/help/code-style.html)
- [Code Style. PHP](https://www.jetbrains.com/phpstorm/help/code-style-php.html)
- [WordPress PHP Coding Standards](https://codex.wordpress.org/WordPress_Coding_Standards)
- [Delicious Brains WordPress coding styles for PhpStorm](https://github.com/deliciousbrains/wp-phpstorm-code-styles)
