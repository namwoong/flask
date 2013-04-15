.. _deployment:

배포 옵션
==================

사용가능한 것을 무엇인지에 따라 플라스크 어플리케이션을 실행할 수 있는 다양한 방법이 있다.
개발하는 동안에는 내장 서버를 사용할 수 있지만, 운영을 위해서는 모든 배포 옵션을 사용해야 한다.
(운영할 때에는 내장 개발 서버를 사용하지 마라.)
다양한 옵션들을 사용할 수 있으며, 사용 방법은 아래를 참조하라.

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
