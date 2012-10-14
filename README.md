# Drupal 7 web.config file for use with boost module

[Drupal 7](http://drupal.org/) web.config file for use with [Boost](http://drupal.org/project/boost) module on Windows servers.

The file includes two fixes:

- Fix default favicon rewrite rules. See [this](http://drupal.org/node/1041580) issue on Drupal.org for more information.
- Force of www in front of the domain name to avoid duplicate content on search engines.

Tested on Windows Server 2008 and IIS 7.0. This web.config works for single and multi site installs.

See also [regular web.config for Drupal on IIS](http://github.com/topsitemakers/drupal7webconfig).

<hr>

By: [topsitemakers.com](http://www.topsitemakers.com).

