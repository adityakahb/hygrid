HYGRID
=======
A simple grid generator with lots of options

Installation
============
BOWER: `bower install hygrid`

NPM: `npm install hygrid`

Basic Requirements
==================
* __[SASS](http://sass-lang.com/) for SASS developers.__
* __[LESS](http://lesscss.org/) for LESS developers.__

Supported Browsers
==================
__All modern browsers are supported__

Following variables can be customized
=====================================

### `SASS`

```css
$xs-min: 0px;
$sm-min: 745px;
$md-min: 925px;
$lg-min: 1153px;

$xs-gutter: 5px;
$sm-gutter: 10px;
$md-gutter: 15px;
$lg-gutter: 20px;

$hygrid-columns: 12;

$hygrid-grid-prefix: 'hygrid';
$hygrid-column-prefix: 'hcol';
```

### `LESS`

```css
@xs-min: 0px;
@sm-min: 745px;
@md-min: 925px;
@lg-min: 1153px;

@xs-gutter: 5px;
@sm-gutter: 10px;
@md-gutter: 15px;
@lg-gutter: 20px;

@hygrid-columns: 12;

@hygrid-grid-prefix: hygrid;
@hygrid-column-prefix: hcol;
```

Features
========
* Customize the variables and get it running.
* 4 types of grids supported:
  * Grid with all columns floating to left with no gutter space
  * Grid with all columns floating to left with custom gutter space
  * Grid with all columns centered to parent with no gutter space
  * Grid with all columns centered to parent with custom gutter space
* User defined variables:
  * Breakpoints for mobile, tablet portrait, tablet landscape and desktop
  * Number of grid columns
  * Gutter spaces respective to all breakpoints
  * Prefixes for grid and columns
* Offsets included for floating grid columns
* Examples included