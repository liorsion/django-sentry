Sentry
======

Sentry provides you with a generic interface to view and interact with your error logs. By
default, it will catch any exception thrown by Django and store it in a database. With this
it allows you to interact and view near real-time information to discover issues and more
easily trace them in your application.

Sentry Client Changes
---------------------

As of 1.13.0 the built-in client has been deprecated. A new standalone project (which doesn't require Django)
called `Raven <http://github.com/dcramer/raven>`_ will replace it. If you're just getting started
with Sentry, or you want to use a client in a non-Django application, we suggest taking a look at Raven.


.. toctree::
   :maxdepth: 2

   install/index
   config/index
   technical/index
   contributing/index

.. image:: http://dl.dropbox.com/u/116385/Screenshots/l6xk.png

Deprecation Notes
-----------------

Milestones releases are 1.3 or 1.4, and our deprecation policy is to a two version step. For example,
a feature will be deprecated in 1.3, and completely removed in 1.4.
