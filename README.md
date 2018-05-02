# drupal-docker
Use this to create a drupal project in a docker container. This contains the latest files. This repository has specifically only Mariadb container from apache.
To create a project clone this repository and follow the following steps:
Make sure that you have all neccessary tools such as composer, docker,
Then after cloning this in to your directory
do
docker-compose up -d : to build the project(all the neccessary containers will be built)
then ssh into your site:
then using composer install drupal
that is it.
