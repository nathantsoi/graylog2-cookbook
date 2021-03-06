Graylog Chef Cookbook Changes
==============================

## 1.0.1

* reduce file permissions for Graylog config files
* fix empty string for 'graylog2.appender.host' in web.conf

## 1.0.0

* Update Graylog version to 1.0.0
* explicit include of 'authbind' in graylog2::authbind
* improve error handling for api access
* mandatory secrets for server and web interrupt chef run if they are not set
* allow secrets to be set through attributes or an encrypted data bag 'secrets/graylog'
* support chef search for nodes to set up unicast discovery

## 0.3.8 (2015-01-14)

* Bump to 0.92.4
* Restart Graylog server + web interface on package update

## 0.3.7 (2015-01-05)

* Removed dependency on default.rb, you can now use only single parts of the cookbook

## 0.3.6 (2014-12-23)

* Update Graylog2 version to 0.92.3

## 0.3.5 (2014-12-12)

* Update Graylog2 version to 0.92.1

## 0.3.4 (2014-12-01)

* Update Graylog2 version to 0.92.0
* Add new configuration parameters for time based retention and SSL/TLS REST API

## 0.3.3 (2014-11-07)

* Update Graylog2 version to 0.91.3
