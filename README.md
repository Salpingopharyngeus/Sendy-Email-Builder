# Drag'n'Drop Email Builder for Sendy

Drag'n'drop email builder for [Sendy](https://sendy.co)

![email-builder-ui](https://user-images.githubusercontent.com/10295466/37458623-a03b9c4c-2856-11e8-9061-c8e126937729.png)

## Getting Started
Set the following variables in ```_config.php```: 
```
APP_PATH
SENDY_URL
SENDY_API_KEY
DATABASE HOST, USER PASSWORD AND DATABASE NAME 
```
Do not forget to set writing permissions to ```/uploads/``` folder.


## Installation Instructions
(Previously listed at getemailbuilder.com/sendy/documentation)
Installation of the Email Builder for Sendy is similar to installation process of Sendy

Installation
We recommend you to install Email Builder addon to separate subdomain. You will be able to login to Email Builder with your Sendy credentials.

First of all - upload files to your server, then change the following variables in ```_config.php```:
```
APP_PATH - Email Builder installation URL, for example https://emailbuilder.yourdomain.com
SENDY_URL - Your Sendy URL, for example https://sendy.yourdomain.com
SENDY_API_KEY - Your Sendy API Key
$dbHost - Your Sendy Database Host
$dbUser - Your Sendy Database User
$dbPass - Your Sendy Database Password
$dbName - Your Sendy Database Name
Then set file permissions of /uploads/ folder to 777. It's required for image uploading.
```

## Development
The package is based on [Laravel Mix](https://github.com/JeffreyWay/laravel-mix).
### Installation
```
git clone
npm install
npm run watch
```
### Available NPM commands
```
npm run watch
npm run dev
npm run production
```

## Changelog
```
v1.0.0 - March 15, 2018
** Initial release **
```

## Credits
- [Max Kostinevich](https://maxkostinevich.com)

## [MIT License](https://opensource.org/licenses/MIT)
(c) 2018  [DigitalWheat](https://digitalwheat.com) - All rights reserved.

## About
At [DigitalWheat](https://digitalwheat.com) we create modern web-applications for small and medium-sized business. 

**Have a project in mind? [Let's talk!](https://digitalwheat.com/get-quote)**
