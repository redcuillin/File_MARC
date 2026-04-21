# Fork of Pear/File_MARC
Created in attempt to update this code and keep in usable in PHP8.4.

Initial objective is to replace the large number of deprecation warnings likely to be thrown.

Fork by redcuillin for PHP8.4 support
-------------------------------------

### Using this fork with Composer

Add the following to your `composer.json` `repositories` and `require` sections (merge with existing entries as needed):

```json
"repositories": [
    {
        "type": "vcs",
        "url": "https://github.com/redcuillin/File_MARC"
    }
],
"require": {
    "pear/file_marc": "dev-master as 1.999.0"
}
```

## Upstream readme:

This package is http://pear.php.net/package/File_MARC and has been migrated from https://svn.php.net/repository/pear/packages/File_MARC

Please report all new issues via the PEAR bug tracker.

If this package is marked as unmaintained and you have fixes, please submit your pull requests and start discussion on the pear-qa mailing list.

To test, run either
$ phpunit tests/
  or
$ pear run-tests -r

To build, simply
$ pear package

To install from scratch
$ pear install package.xml

To upgrade
$ pear upgrade -f package.xml
