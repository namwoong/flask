.. _deployment:

배포 옵션
==================

사용가능한 것을 무엇인지에 따라 플라스크 어플리케이션을 실행할 수 있는 다양한 방법이 있다.
You can use the builtin server during development,
but you should use a full deployment option for production applications.
(Do not use the builtin development server in production.)  Several
options are available and documented here.

If you have a different WSGI server look up the server documentation
about how to use a WSGI app with it.  Just remember that your
:class:`Flask` application object is the actual WSGI application.

For hosted options to get up and running quickly, see
:ref:`quickstart_deployment` in the Quickstart.

.. toctree::
   :maxdepth: 2

   mod_wsgi
   wsgi-standalone
   uwsgi
   fastcgi
   cgi
