# Fuel Supervisor

[![Build Status](https://travis-ci.org/indigophp/fuel-supervisor.svg?branch=develop)](https://travis-ci.org/indigophp/fuel-supervisor)
[![Latest Stable Version](https://poser.pugx.org/indigophp/fuel-supervisor/v/stable.png)](https://packagist.org/packages/indigophp/fuel-supervisor)
[![Total Downloads](https://poser.pugx.org/indigophp/fuel-supervisor/downloads.png)](https://packagist.org/packages/indigophp/fuel-supervisor)
[![License](https://poser.pugx.org/indigophp/fuel-supervisor/license.png)](https://packagist.org/packages/indigophp/fuel-supervisor)
[![Dependency Status](https://www.versioneye.com/user/projects/53c2bb6bea871eb59200001d/badge.svg?style=flat)](https://www.versioneye.com/user/projects/53c2bb6bea871eb59200001d)

**This package is a wrapper around [indigophp/supervisor](https://github.com/indigophp/supervisor) package.**


## Install

Via Composer

``` json
{
    "require": {
        "indigophp/fuel-supervisor": "@stable"
    }
}
```


## Usage

``` php
\Supervisor::forge('default');
```


## Configuration

``` php
'default' => function() {
    return new Indigo\Supervisor\Connector\SomeConnector;
},
```


## Testing

``` bash
$ codecept run
```


## Credits

- [Márk Sági-Kazár](https://github.com/sagikazarmark)
- [All Contributors](https://github.com/indigophp/fuel-supervisor/contributors)


## License

The MIT License (MIT). Please see [License File](https://github.com/indigophp/fuel-supervisor/blob/develop/LICENSE) for more information.
