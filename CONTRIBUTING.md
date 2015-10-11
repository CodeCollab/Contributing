# Contributing

When contributing to one of the projects under the [CodeCollab][codecollab] organization these guidelines must be followed.

## Coding standards

All projects use the following code style conventions / standards (with a couple of [amendments][amendments]):

- [PSR-1: Basic Coding Standard][psr1]
- [PSR-2: Coding Style Guide][psr2]
- [PSR-4: Autoloading Standard][psr4]

### Amendments

Additionally all code needs to be run in strict mode. The strict mode declaration must be on the first line of the file with a single space between the PHP opening tag and `declare()`:

    <?php declare(strict_types=1);

Also changes with regards to the PSR coding standards:

- Property names MUST be declared in camelCase
- Non property variable names MUST be declared in camelCase
- All files MUST have declared strict types
- The strict type declaration MUST be on the first lines in a file with a space between the PHP open tag and the declaration
- Method arguments MUST be type hinted (including for scalar types)
- Abstract classes MUST NOT have an `Abstract` prefix
- Interfaces MUST NOT have an `Interface` suffix
- Traits MUST NOT be used

## Feature requests or bug reports

If you would like to see a feature or you have found a bug please open on GitHub on the repository of the specific project.

## Contributing code

### Creating a pull request

- Submit one pull request per fix or feature
- If your changes are not up to date - rebase your branch on master
- Follow the conventions used in the project

### Unit tests

This project has unit tests for most code. When adding a new feature or when fixing a bug and sending over a PR adding (passing) test(s) is required and will make it easier to merge code.

### Code style

Always use the codings standards as defined under [Coding standards][coding-standards].

## Licensing

Unless stated otherwise, all content is licensed under the Creative Commons Attribution License and code licensed under the MIT License.

Copies of all licenses are included in this project's root directory.

[codecollab]: https://github.com/CodeCollab
[psr1]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md
[psr2]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md
[psr4]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-4-autoloader.md
[coding-standards]: https://github.com/CodeCollab/Contributing/blob/master/CONTRIBUTING.md#coding-standards
[amendments]: https://github.com/CodeCollab/Contributing/blob/master/CONTRIBUTING.md#amendments
