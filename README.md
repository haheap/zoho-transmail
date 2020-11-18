# Installation

You can install the package via composer:

```bash
composer require haheap/zoho-transmail
```

You can publish the config file with:
```bash
php artisan vendor:publish --provider="Haheap\ZohoTransmail\ZohoTransmailServiceProvider" --tag="config"
```

This is the contents of the published config file:

```php
return [
];
```

## Usage

``` php
$mailer = new Haheap\ZohoTransmailS();
```

## Testing


## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [:author_name](https://github.com/:author_username)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
