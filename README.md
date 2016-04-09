Movie manager
=============

This is a demo project illustrating the use of a [Angular.js](https://angularjs.org/) front-end and a [REST](http://en.wikipedia.org/wiki/Representational_state_transfer) back-end.

Check out
---------

```sh
$ git clone https://github.com/miladhub/movie-manager-angular.git
```

Build
-----

```sh
$ cd movie-manager-angular
$ mvn clean install
...
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 2.913 s
[INFO] Finished at: 2016-04-09T20:23:42+02:00
[INFO] Final Memory: 18M/170M
[INFO] ------------------------------------------------------------------------
```

Deploy
------

The WAR can be deployed on any servlet 3.0+ container. For [JBoss WildFly](http://wildfly.org/downloads/), drop the WAR into `standalone/deployments` and open page [http://localhost:8080/movie/](http://localhost:8080/movie/).

```sh
$ git clone https://github.com/miladhub/movie-manager-angular.git
$ cd movie-manager-angular
$ mvn clean install
...
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 2.913 s
[INFO] Finished at: 2016-04-09T20:23:42+02:00
[INFO] Final Memory: 18M/170M
[INFO] ------------------------------------------------------------------------
$ cp target/movie.war ~/wildfly-8.1.0.Final/standalone/deployments
$ ~/wildfly-8.1.0.Final/bin/standalone.sh
```