# queue

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]

**Note:** Replace ```kcloze``` ```kcloze``` ```https://github.com/YaochufaTech/swoole-queue``` ```pei.greet@gmail.com``` ```yaochufa``` ```queue``` ```基于swoole的抢购排队通用中间件，适合抢购秒杀场景，跟具体业务解耦``` with their correct values in [README.md](README.md), [CHANGELOG.md](CHANGELOG.md), [CONTRIBUTING.md](CONTRIBUTING.md), [LICENSE.md](LICENSE.md) and [composer.json](composer.json) files, then delete this line. You can run `$ php prefill.php` in the command line to make all replacements at once. Delete the file prefill.php as well.

This is where your description should go. Try and limit it to a paragraph or two, and maybe throw in a mention of what
PSRs you support to avoid any confusion with users and contributors.

## Structure

If any of the following are applicable to your project, then the directory structure should follow industry best practices by being named the following.

```
bin/        
config/
src/
tests/
vendor/
```


## Install

Via Composer

``` bash
$ composer require yaochufa/queue
```

## Usage

``` php
$skeleton = new Yaochufa\Queue();
echo $skeleton->echoPhrase('Hello, League!');
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) for details.

## Security

If you discover any security related issues, please email pei.greet@gmail.com instead of using the issue tracker.

## Credits

- [kcloze][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/yaochufa/queue.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/yaochufa/queue/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/yaochufa/queue.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/yaochufa/queue.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/yaochufa/queue.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/yaochufa/queue
[link-travis]: https://travis-ci.org/yaochufa/queue
[link-scrutinizer]: https://scrutinizer-ci.com/g/yaochufa/queue/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/yaochufa/queue
[link-downloads]: https://packagist.org/packages/yaochufa/queue
[link-author]: https://github.com/kcloze
[link-contributors]: ../../contributors
