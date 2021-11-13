# Laravel Package Collection

This repository summarizes all useful packages for laravel I have come across. 
A solid summary of all packages can make it easier for everyone who is looking 
for a specific package, solving a special issue (api tokens, 2fa, roles/permissions,
administration, etc.).

## Well known laravel developers

The order of this list has no meaning, rating or whatsoever. I simply added the
creators in the order they have come to my mind.

- [Marcel Pociot](https://github.com/mpociot)
- [BeyondCode](https://github.com/beyondcode) 
- [Barry vd. Heuvel](https://github.com/barryvdh)
- [Spatie](https://github.com/spatie)

## Categories

As some packages could fit in multiple categories, I decided to name the matching categories
alongside the packages in the list down below.

With `CTRL + F` you can search the current page to find the packages, i.e. 
for `Development`, faster.

## Packages

The packages are sorted ascending by `vendor/name`. The structure will be like:
```
[vendor/name](https://www.github.com/link/to/repo) / Category: X, Y
> Citation of the repository description as a brief intro
```

### Used Packages

This area contains all packages, that I can strongly recommend, after thorough use in my own
projects.

- [barryvdh/laravel-debugbar](https://github.com/barryvdh/laravel-debugbar) / Category: `Development`
  > This is a package to integrate PHP Debug Bar with Laravel. It includes a 
  > ServiceProvider to register the debugbar and attach it to the output. You can 
  > publish assets and configure it through Laravel. It bootstraps some Collectors 
  > to work with Laravel and implements a couple custom DataCollectors, specific for 
  > Laravel. It is configured to display Redirects and (jQuery) Ajax Requests. (Shown 
  > in a dropdown) Read the documentation for more configuration options.

- [barryvdh/laravel-ide-helper](https://github.com/barryvdh/laravel-ide-helper) / Category: `Development`
  > Complete PHPDocs, directly from the source
  >
  > This package generates helper files that enable your IDE to provide accurate autocompletion. Generation is done based on the files in your project, so they are always up-to-date.

- [beyondcode/laravel-dump-server](https://github.com/beyondcode/laravel-dump-server) / Category: `Development`
  > Bringing the Symfony Var-Dump Server to Laravel. 
  > 
  > This package will give you a dump server, that collects all your dump call outputs, so that it does not interfere with HTTP / API responses.

- [beyondcode/laravel-websockets](https://github.com/beyondcode/laravel-websockets) / Category: `Broadcasting`, `Websockets`
  > Bring the power of WebSockets to your Laravel application. Drop-in Pusher replacement, SSL support, Laravel Echo support and a debug dashboard are just some of its features.
  
- [laravel/homestead](https://github.com/laravel/homestead) / Category: `Development`, `Container`
  > Laravel Homestead is an official, pre-packaged Vagrant box that provides you a wonderful development environment without requiring you to install PHP, a web server, and any other server software on your local machine. No more worrying about messing up your operating system! Vagrant boxes are completely disposable. If something goes wrong, you can destroy and re-create the box in minutes!
  > 
  > Homestead runs on any Windows, Mac, or Linux system, and includes the Nginx web server, PHP 8.0, MySQL, Postgres, Redis, Memcached, Node, and all of the other goodies you need to develop amazing Laravel applications.

- [laravel/sanctum](https://github.com/laravel/sanctum) / Category: `Security`, `API Token`
  > Laravel Sanctum provides a featherweight authentication system for SPAs and simple APIs.
  
- [maatwebsite/laravel-excel](https://github.com/Maatwebsite/Laravel-Excel) / Category: `Export`, `Import`, `Excel`
  > Supercharged Excel exports and imports
  > 
  > A simple, but elegant Laravel wrapper around PhpSpreadsheet exports and imports.

- [spatie/data-transfer-object](https://github.com/spatie/data-transfer-object) / Category: `DTO`, `Data Transformation`
  > Data transfer objects with batteries included

- [spatie/laravel-activitylog](https://github.com/spatie/laravel-activitylog) / Category: `Logging`
  > The spatie/laravel-activitylog package provides easy to use functions to log the activities of the users of your app. It can also automatically log model events. The Package stores all activity in the activity_log table.

- [spatie/laravel-directory-cleanup](https://github.com/spatie/laravel-directory-cleanup) / Category: `File Management`, `Cleanup`
  > This package will delete old files from directories. You can use a configuration file to specify the maximum age of a file in a certain directory.
  
- [spatie/laravel-permission](https://github.com/spatie/laravel-permission) / Category: `Security`, `Permission`, `Role`
  > Associate users with permissions and roles
  
### Unused Packages

This area contains all packages, that sound promising, but I have not used myself yet.

- [barryvdh/laravel-dompdf](https://github.com/barryvdh/laravel-dompdf) / Category: `PDF`
  > Laravel wrapper for Dompdf HTML to PDF Converter

- [beyondcode/laravel-mailbox](https://github.com/beyondcode/laravel-mailbox) / Category: `Email`
  > Handle incoming emails in your Laravel application.
  
- [beyondcode/laravel-self-diagnosis](https://github.com/beyondcode/laravel-self-diagnosis) / Category: `Setup`, `Security`
  > This package allows you to run self-diagnosis tests on your Laravel application. It comes with multiple checks out of the box and allows you to add custom checks yourself.

- [botman/botman](https://github.com/botman/botman) / Category: `Bot Programming`, `Chat`
  > BotMan is a framework agnostic PHP library that is designed to simplify the task of developing innovative bots for multiple messaging platforms, including Slack, Telegram, Microsoft Bot Framework, Nexmo, HipChat, Facebook Messenger and WeChat.
  
- [mpociot/laravel-apidoc-generator](https://github.com/mpociot/laravel-apidoc-generator) / Category: `API`, `Documentation`
  > Automatically generate your API documentation from your existing Laravel/Lumen/Dingo routes.
  
- [spatie/laravel-backup](https://github.com/spatie/laravel-backup) / Category: `Backup`
  > This Laravel package creates a backup of your application. The backup is a zip file that contains all files in the directories you specify along with a dump of your database. The backup can be stored on any of the filesystems you have configured in Laravel.

- [spatie/laravel-honeypot](https://github.com/spatie/laravel-honeypot) / Category: `Security`
  > Preventing spam submitted through forms
  > 
  > When adding a form to a public site, there's a risk that spam bots will try to submit it with fake values. Luckily, the majority of these bots are pretty dumb. You can thwart most of them by adding an invisible field to your form that should never contain a value when submitted. Such a field is called a honeypot. These spam bots will just fill all fields, including the honeypot.

### Recommended Packages

This area contains all packages, that been recommended by others. Please feel free to 
_submit a pull request_ with some package recommendations.

_Nothing here, yet!_