# Drupal Console Yaml

Drupal Console Yaml, this project contains YAML console commands shared across projects.

### Commands:
```
* yaml:diff             Compare two YAML files in order to find differences between them.
* yaml:get:value        Get value for a specific key inside the YAML file.
* yaml:merge            Merge two or more YAML files in a new YAML file. Latest values are preserved.
* yaml:split            Split a YAML file using indent as separator criteria
* yaml:yaml:unset:key   Unset/remote a specific key inside the YAML file.
* yaml:update:key       Replace a YAML key in a YAML file.
* yaml:update:value     Update a value for a specific key in a YAML file.
```

### Install on a site:
```
cd /path/to/drupal/

composer require drupal/console-yaml
```

### Install globally:
```
cd cd ~/.console/extend/

composer require drupal/console-yaml

```
* For more information about adding commands globally [Drupal Console Extend](https://github.com/hechoendrupal/drupal-console-extend#drupal-console-extend)