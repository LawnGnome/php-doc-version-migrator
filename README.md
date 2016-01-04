# PHP Documentation Version Migrator

This project can be used with the PHP manual source code to upgrade version
information for a new major version. It's probably useless unless you're a PHP
documentation contributor.

## Requirements

PHP 7.

## Usage

Basic usage (no exclusions):

    upgrade-versions -f "PHP 5" -r "PHP 7" -d en

Using exclusions:

    upgrade-versions -x php-7.0-exclusions -f "PHP 5" -r "PHP 7" -d en

## Bugs

Probably.
