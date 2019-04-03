[![Analytics](https://ga-beacon.appspot.com/UA-134431636-1/awes-io/awes-io)](https://github.com/awes-io/awes-io)

**Laravel AWES.IO Edition** was created by [Awescode GmbH](https://www.awescode.de), and is maintained by [Awes.IO](https://www.awes.io) Team, and is a platform that 
provides an awesome UI interface and additional packages to build very fast&stable responsible web applications. It is an **unofficial** version of [Laravel](https://laravel.com/).

## What is AWES.IO?

<p align="center">
  <img src="https://static.awes.io/docs/awes-io.png" alt="Awes.IO" />
</p>

**The Platform** consists of 20 dedicated packages on [PHP](http://www.php.net/) and [VueJS](https://vuejs.org/), which have 
issued on [PackageKit](https://www.pkgkit.com). Packages are ready to install through [composer](https://getcomposer.org/).

Please feel free to follow our [official website](https://www.awes.io) to read more.

## Server Requirements

* PHP >= 7.2
* OpenSSL PHP Extension
* PDO PHP Extension
* Mbstring PHP Extension
* Tokenizer PHP Extension
* XML PHP Extension
* Ctype PHP Extension
* JSON PHP Extension
* BCMath PHP Extension

## Installing AwesIO

### Via AwesIO Installer

[Awes.IO](https://www.awes.io) utilizes [Composer](https://getcomposer.org/) to manage its dependencies. So, before using [Awes.IO](https://www.awes.io), make sure you have Composer installed on your machine.

First, download the [Awes.IO](https://www.awes.io) installer using Composer:
```bash
composer global require awes-io/installer
```

Make sure to place composer's system-wide vendor bin directory in your `$PATH` so the awes-io executable can be located by your system. This directory exists in different locations based on your operating system; however, some common locations include:

- macOS: `$HOME/.composer/vendor/bin`, command: `export PATH=~/.composer/vendor/bin:$PATH`
- GNU / Linux Distributions: `$HOME/.config/composer/vendor/bin`
- Windows: `%USERPROFILE%\AppData\Roaming\Composer\vendor\bin`

Once installed, the `awes-io new` command will create a fresh [Awes.IO](https://www.awes.io) installation in the directory you specify. For instance, `awes-io new crm` will create a directory named `crm` containing a fresh [Awes.IO](https://www.awes.io) installation with all of [Awes.IO](https://www.awes.io)'s dependencies already installed:

```bash
awes-io new crm
```

### Manual installation

For the fast start, we recommend using [AwesIO Installer](#via-awesio-installer).
If for some reason it's not an option, please follow the instruction:

1. Clone the repository: `git clone git@github.com:awes-io/awes-io.git`
2. Create a project by the link: [https://www.pkgkit.com/awes-io/create](https://www.pkgkit.com/awes-io/create)
3. Copy project's API key and save it to your `composer.json`
4. `composer install`
5. Done! 🍺

## Documentation

Full documentation please follow to official website of [Awes.IO](https://www.awes.io/documentation).

## Most popular packages

The project contains 
- Indigo Layout
- Form Builder
- Table Builder
- Auth Package

## Security Vulnerabilities

If you discover a security vulnerability within the project, please send an e-mail to [contact@awes.io](mailto:contact@awes.io). All security vulnerabilities will be promptly addressed.

