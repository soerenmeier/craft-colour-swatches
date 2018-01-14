![Icon](./src/icon.svg)

[![Latest Version](https://img.shields.io/github/release/rias500/craft-colour-swatches.svg?style=flat-square)](https://github.com/rias500/craft-colour-swatches/releases)
[![Quality Score](https://img.shields.io/scrutinizer/g/rias500/craft-colour-swatches.svg?style=flat-square)](https://scrutinizer-ci.com/g/rias500/craft-colour-swatches)
[![StyleCI](https://styleci.io/repos/117454863/shield)](https://styleci.io/repos/117454863)
[![Total Downloads](https://img.shields.io/packagist/dt/rias/craft-colour-swatches.svg?style=flat-square)](https://packagist.org/packages/rias/craft-colour-swatches)

# Colour Swatches plugin for Craft CMS 3.x

Let clients choose from a predefined set of colours.

<img src="./resources/img/screenshot.png" width="500">

## Requirements

This plugin requires Craft CMS 3.0.0-beta.23 or later.

## Installation

To install the plugin, follow these instructions.

1. Open your terminal and go to your Craft project:

        cd /path/to/project

2. Then tell Composer to load the plugin:

        composer require rias/craft-colour-swatches

3. In the Control Panel, go to Settings → Plugins and click the “Install” button for Colour Swatches.

## Colour Swatches Overview

Instead of providing a user a full color picker, Color Swatches gives an admin the ability to provide a selection of colors for a user to choose from.

## Configuring Colour Swatches

Create a Color Swatches field and provide label and hex value options.

![Screenshot](./resources/img/single.png)

Multiple colours are possible by seperating them with a comma

![Screenshot](./resources/img/multiple.png)

## Using Colour Swatches

You can access both the label and color in your template. By default, the label will display:

```twig
{{ fieldName }}
{{ fieldName.label }}
{{ fieldName.color }}
{{ fieldName.colours }} {# Returns an array of all colours #}
```

Based on the awesome [Craft 2 plugin](https://github.com/vigetlabs/craft-color-swatches) from Vigetlabs

Brought to you by [Rias](https://rias.be)
