# Saba Theme for Grav

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Saba](assets/readme_1.png)

> **Saba** by [**IslandThemes**](https://github.com/IslandThemes) is a Light & Classy design Theme for [**Grav**](http://getgrav.org) based on [**Skinny-Bones**](https://github.com/mmistakes/skinny-bones-jekyll) Theme by mmistakes. 

##### Table of Contents:

* [Features](#features)
* [Views](#twig-views)
* [Installation](#installation)
* [Updating](#updating)
* [Setup](#setup)
* [Credits](#credits)

## Features
* HTML5 and CSS3
* Fully Responsive
* Bootstrap v3.3.6
* FontAwesome v4.5.0
* Various templates for presenting your content
* Cross browser compatible
* Sharing buttons for Facebook and Twitter.

## Twig views
* default,
* contact form,
* error,

## Installation
Installing the **Saba** Theme can be done in one of two ways. Via GPM (Grav Package Manager) installation method enables you to quickly and easily install the theme with a simple terminal command, while the manual method enables you to do so via a zip file.

#### GPM Installation (Preferred)

The simplest way to install this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm) through your system's Terminal (also called the command line). From the root of your Grav install type:

    bin/gpm install saba

This will install the Saba Theme into your `/user/themes` directory within Grav. Its files can be found under `/your/site/grav/user/themes/saba`.

#### Manual Installation

To install this theme, just download the zip version of this repository and unzip it under `/your/site/grav/user/themes`. Then, rename the folder to `saba`. You can find these files on [GitHub](https://github.com/IslandThemes/grav-theme-saba).

You should now have all the theme files under

    /your/site/grav/user/themes/saba
	
>> NOTE: This theme is a modular component for Grav which requires the [Grav](http://github.com/getgrav/grav), [Error](https://github.com/getgrav/grav-theme-error) and [Problems](https://github.com/getgrav/grav-plugin-problems) plugins.

## Updating
As development for the Saba Theme continues, new versions may become available that add additional features and functionality, improve compatibility with newer Grav releases, and generally provide a better user experience. Updating Bootstrap is easy and can be done through Grav's GPM system, as well as manually.

#### GPM Update (Preferred)

The simplest way to update this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm). You can do this with this by navigating to the root directory of your Grav install using your system's Terminal (also called command line) and typing the following:

    bin/gpm update saba

This command will check your Grav install to see if your Saba Theme is due for an update. If a newer release is found, you will be asked whether or not you wish to update. To continue, type `y` and hit enter. The theme will automatically update and clear Grav's cache.

#### Manual Update

Manually updating Agency is pretty simple. Here is what you will need to do to get this done:

* Delete the `your/site/user/themes/saba` directory.
* Download the new version of the Bootstrap Theme on [GitHub](https://github.com/IslandThemes/grav-theme-saba).
* Unzip the zip file in `your/site/user/themes` and rename the resulting folder to `saba`.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in terminal and typing `bin/grav clear-cache`.

> Note: Any changes you have made to any of the files listed under this directory will also be removed and replaced by the new set. Any files located elsewhere (for example a YAML settings file placed in `user/config/themes`) will remain intact.

## Setup
If you want to set Saba as the default theme, you can do so by following these steps:

* Navigate to `/your/site/grav/user/config`.
* Open the **system.yaml** file.
* Change the `theme:` setting to `theme: saba`.
* Save your changes.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in Terminal and typing `bin/grav clear-cache`.

Once this is done, you should be able to see the new theme on the frontend. Keep in mind any customizations made to the previous theme will not be reflected as all of the theme and templating information is now being pulled from the **saba** folder.

#### Contact Form Configuration
For contact form configuration instructions please refer to [official documentation](http://learn.getgrav.org/advanced/contact-form). Make sure you installed Email and Form plugin though.

If you find bugs in the theme report [here](https://github.com/IslandThemes/grav-theme-saba/issues)

## Credits
* [Grav](http://getgrav.org) by [RocketTheme](http://www.rockettheme.com). Licensed under [MIT](https://github.com/IslandThemes/grav-theme-saba/master/LICENSE.md)
* Inspired by [Skinny Bones Jekyll](https://github.com/mmistakes/skinny-bones-jekyll) by [Michael Rose](https://github.com/mmistakes). Licensed under [MIT](https://github.com/IslandThemes/grav-theme-saba/master/LICENSE.md)
* [Bootstrap](http://getbootstrap.com) 3.3.6. Licensed under [MIT](https://github.com/IslandThemes/grav-theme-saba/master/LICENSE.md)
* [Font Awesome](http://fortawesome.github.io/Font-Awesome/) 4.5.0 by Dave Gandy. Licensed under [MIT](https://github.com/IslandThemes/grav-theme-saba/master/LICENSE.md)

> [IslandThemes](https://github.com/IslandThemes) proudly brought to you by [IDIM<em>web</em>.com](http://idimweb.com)
