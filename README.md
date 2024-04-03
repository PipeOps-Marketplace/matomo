# Matomo on PipeOps

[![Deploy on PipeOps](https://railway.app/button.svg)](https://railway.app/template/0ELOuE?referralCode=IQhE0B)


Matomo is the leading open-source analytics platform that gives you more than powerful analytics.


Matomo (formerly Piwik)

Matomo (formerly Piwik) is the leading open-source analytics platform that gives you more than just powerful analytics:

Free open-source software
100% data ownership
User privacy protection
User-centric insights
Customisable and extensible



# Supported tags and respective Dockerfile links

    5.0.3-apache, 5.0-apache, 5-apache, apache, 5.0.3, 5.0, 5, latest
    5.0.3-fpm, 5.0-fpm, 5-fpm, fpm
    5.0.3-fpm-alpine, 5.0-fpm-alpine, 5-fpm-alpine, fpm-alpine


#Matomo Installation

Once you're up and running, you'll arrive at the configuration wizard page. If you're using the compose file, at the Database Setup step, please enter the following:

Database Server: db
Login: MYSQL_USER
Password: MYSQL_PASSWORD
Database Name: MYSQL_DATABASE

And leave the rest as default.

Then you can continue the installation with the super user.

The following environment variables are also honored for configuring your Matomo instance:

    MATOMO_DATABASE_HOST
    MATOMO_DATABASE_ADAPTER
    MATOMO_DATABASE_TABLES_PREFIX
    MATOMO_DATABASE_USERNAME
    MATOMO_DATABASE_PASSWORD
    MATOMO_DATABASE_DBNAME

The PHP memory limit can be configured with the following environment variable:

    PHP_MEMORY_LIMIT
