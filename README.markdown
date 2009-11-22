Compojure is an open source web framework for the [Clojure](http://clojure.org)
programming language. It emphasizes a thin I/O layer and a functional approach
to web development.

Compojure is still in active development. The current stable branch has been
released as version 0.2.

Sample Code
-----------

Here's a small web application written in Compojure:

    (use 'compojure)

    (defroutes my-app
      (GET "/"
        (html [:h1 "Hello World"]))
      (ANY "*"
        (page-not-found)))

    (run-server {:port 8080}
      "/*" (servlet my-app))

Dependencies
------------

javagem install compojure will install all necessary dependencies.

Documentation
-------------

For information on how to get started and use Compojure, please see our
[Wiki](http://en.wikibooks.org/wiki/Compojure).

There is also a rough draft of a [Compojure Tutorial](http://groups.google.com/group/compojure/browse_thread/thread/3c507da23540da6e)
available to read.

Community
---------

The [Compojure Group](http://groups.google.com/group/compojure) is the best place
to ask questions about Compojure, suggest improvements or to report bugs.

Tutorials
---------

Eric Lavigne has written a series of excellent tutorials on Compojure:

* [Install Compojure on a Slicehost VPS](http://ericlavigne.wordpress.com/2008/12/18/compojure-on-a-slicehost-vps/)
* [Using PostgreSQL with Compojure](http://ericlavigne.wordpress.com/2008/12/28/using-postgresql-with-compojure/)
* [Compojure security: authentication and authorization](http://ericlavigne.wordpress.com/2009/01/04/compojure-security-authentication-and-authorization/)
