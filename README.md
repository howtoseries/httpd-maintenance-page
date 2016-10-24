# httpd-maintenance-page
Sample "app" and configuration files showing how to display a "maintenance screen" in your Apache httpd server while your app is being deployed.

## Contents
1. Docker file for Apache Httpd server.
1. Apache Httpd configuration file for the "maintenance app".
1. Maintenance App code (HTML+Javascript).

## Requisites
1. Show a standard message to the end-users while an application is deployed to backend server/cluster.
1. Don't intervene directly with Apache config files to put/remove applications from maitenance mode.
