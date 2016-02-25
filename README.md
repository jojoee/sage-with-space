# sage-with-space
Alternative repository for [sage](https://github.com/roots/sage) (wordpress starter theme) that have `space` according to [WordPress PHP Coding Standards](https://make.wordpress.org/core/handbook/best-practices/coding-standards/php/)

## My step to add space
1. Open `PhpStorm`
2. Import `Code Style` from `PhpStorm-settings.jar`
3. Reformat code (`Ctrl + Alt + L`) by `Sage with space` scheme
4. Set `Filters` on `Reformat Code` dialog and run
    - Scope: `Project File`
    - File mask(s): `*.php`
5. Fix `base.php` (`php` code in `html` comment)
6. Fix `templates/entry-meta.php` (indent `html` in `php` file)

## PhpStorm settings
1. Go to `Settings` panel (`Ctrl + Alt + S`)
2. `Editor > Code Style > Default Indent Options`
    - [ ] Use tab character
    - Tab size: 2
    - Indent size: 2
    - Continuation indent: 2

3. `Editor > Code Style > PHP`
    - `Set from > Predefined style > Wordpress`
    - [ ] Use tab character
    - Tab size: 2
    - Indent size: 2
    - Continuation indent: 2

## TODO
- [ ] Check `ruleset.xml`
- [ ] Check step 5
- [ ] Check step 6

## Reference
- [WI-17786 Honor HTML Indentation Settings in PHP Files](https://youtrack.jetbrains.com/issue/WI-17786)
- [Reformatting Source Code](https://www.jetbrains.com/phpstorm/help/reformatting-source-code.html)
- [Reformat Code Dialog](https://www.jetbrains.com/phpstorm/help/reformat-code-dialog.html)
- [Code Style](https://www.jetbrains.com/phpstorm/help/code-style.html)
- [Code Style. PHP](https://www.jetbrains.com/phpstorm/help/code-style-php.html)
- [WordPress PHP Coding Standards](https://codex.wordpress.org/WordPress_Coding_Standards)

Now we still have an issue about reformat code in some files that's have mixing content (e.g. `php` file that has `php` and `html` code)
