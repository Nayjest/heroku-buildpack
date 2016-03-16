PHP Staging Heroku Buildpack
=======================
# Overview

This buildpack will just install your app with dev-dependencies using `composer create-project --no-interaction`

# Usage

    $ heroku create --stack cedar --buildpack https://github.com/Nayjest/heroku-buildpack.git

    $ git push heroku master
    
The buildpack will detect that your app has a `composer.json` in the root.

# License 

© 2014—2016 Vitalii Stepanenko

Licensed under the MIT License.
