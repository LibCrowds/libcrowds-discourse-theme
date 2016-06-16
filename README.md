# libcrowds-discourse-theme

A supplementary [Discourse](https://github.com/discourse/discourse) theme for
the [LibCrowds](http://www.libcrowds.com) crowdsourcing platform. The theme basically
just imports the main stylesheet from [libcrowds-pybossa-theme](https://github.com/LibCrowds/libcrowds-pybossa-theme)
and adds a handful of tweaks to tidy things up.


## Installation

- Login to your Discourse instance as an administrator.
- Navigate to **Customize > CSS/HTML**.
- Click **Import**.
- Either copy the raw text from
[libcrowds-theme.dcstyle.json](https://raw.githubusercontent.com/LibCrowds/libcrowds-discourse-theme/master/libcrowds-theme.dcstyle.json) into
the box provided, or import the same file.


## Dependencies

Note that this theme pulls in the following files the [libcrowds-pybossa-theme](https://github.com/LibCrowds/libcrowds-pybossa-theme):

* [styles.min.css](https://github.com/LibCrowds/libcrowds-pybossa-theme/blob/master/static/css/styles.min.css)
* [pybossa.png](https://github.com/LibCrowds/libcrowds-pybossa-theme/blob/master/static/img/pybossa.png)
* [bl-logo.png](https://github.com/LibCrowds/libcrowds-pybossa-theme/blob/master/static/img/bl-logo.png)

This theme should be updated if any of those files are moved.


## Development

To update the theme, edit it from within your Discourse instance , via **Customize > CSS/HTML**. To create a new
[libcrowds-theme.dcstyle.json](https://raw.githubusercontent.com/LibCrowds/libcrowds-discourse-theme/master/libcrowds-theme.dcstyle.json)
file, click the **Export** button.
