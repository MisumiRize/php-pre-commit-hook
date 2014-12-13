# pre-commit-hook

Installs pre-commit hook validation.

This also installs PHPUnit, PHPMD and PHP CS Fixer as validation toolkit.

## Requirement

* PHP >= 5.4
* misumirize/git-validate

### Installation

```json
{
    "require-dev": {
    	"misumirize/pre-commit-hook": "*"
    }
}
```

```sh
$ php composer.phar install
$ ./vendor/bin/pre-commit-install
```
