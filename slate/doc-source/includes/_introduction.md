# Enigma Company Batch

> Artisan command:

```php
cd /path/to/enigma-company-batch

php artisan
```
> Manage the Cron entries:

```php
crontab -e

* * * * * php /path/to/artisan schedule:run >> /dev/null 2>&1
0 8 * * * php /path/to/artisan ftp:import-employee >> /dev/null 2>&1
0 8,10,13,16,19 * * * php /path/to/artisan ftp:import-kintai >> /dev/null 2>&1
0 16 * * * php /path/to/artisan employee:confirm-bank-account >> /dev/null 2>&1
```

- [Product requirements](https://neo-universe.atlassian.net/wiki/spaces/ENIGMA/pages/85117753/Services)

- [Bitbucket](https://bitbucket.org/nldanang/enigma-company-batch)

- We use one of the features of the Laravel web framework - [task scheduling](https://laravel.com/docs/5.3/scheduling)

- Basic authentication: `enigma/cie1yiVa`

## Introduction

- Laravel lumen 5.3
- PHP 7.0
- Postgres 9.5
- Dyanmodb, Urban Airship, AWS S3,..

## Features

**1. Send notification**

**2. Create bizfax**

**3. Reset bizfax**

**4. Confirm employee bank account**

**5. Create branch prepaid schedule**

**6. Create payment schedule**

**7. [Create zengin](#create-zengin)**

**8. Import kintai**

**9. Import employee**

**10. Create account inquiry**

**11. Correspondence file**
