# cgr-info

A bash shell script to display a summary of all projects installed via [cgr](https://github.com/consolidation/cgr).

## Overview

The `cgr info` command displays detailed information about installed projects.  This command removes the extra "unnecessary" details and displays a summary of the information.

## Installation
```
$ git clone https://github.com/uberhacker/cgr-info.git
$ sudo cp cgr-info/cgr-info /usr/local/bin/
```

# Usage
```
$ cgr-info

Sample output:

 Name                       Version      Description
 ----                       -------      -----------
 drupal/coder               8.2.12       Coder is a library to review Drupal code.
 drupal/console             0.11.3       The Drupal Console is a CLI tool to generate boilerplate code, interact and debug Drupal 8.
 drupal/site_audit          dev-8.x-3.x  Site Audit is a Drupal static site analysis platform that generates reports with actionable best practice recommendations.
 drush/config-extra         1.0.1        Drush config-extra contains additional configuration Drush commands, notably config-merge.
 pantheon-systems/terminus  1.1.2        A command line interface for Pantheon
```
