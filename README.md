# Docker Customer bootstrap

## How to launch it?
----

Clone the project and inside, at the root, launch

    docker-compose up -d

Then, you can access the website at [http://localhost](http://localhost) and PHPMyAdmin at [http://localhost:8080](http://localhost:8080)

## What to know?
----

All the files are shared in the `data` folder. The database is also shared but, not in a specific folder, it's handled by Docker.

Clone the Drupal project to `data/drupal` to make it run at [http://localhost](http://localhost).

## How to stop it?
----

To simply shut it down, run

    docker-compose down

To shut it down and delete the database, run

    docker-compose down -v

## What's missing?
----

Here are some points missing or not working

* Have a proper URL for the project
* A mail cather is not integrated
