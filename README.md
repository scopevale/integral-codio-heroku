integral-codio-heroku
================

integralmotoring.co.uk site - developed on codio - deployed to heroku


To deploy to Heroku
===================

heroku config:set BUILDPACK_URL=https://github.com/zeke/harp-buildpack.git

heroku config:set HARP_ROOT=./public -a scopevale-integral

git push heroku master