.. _deployment:

배포 옵션
==================

사용가능한 것을 무엇인지에 따라 플라스크 어플리케이션을 실행할 수 있는 다양한 방법이 있다.
개발하는 동안에는 내장 서버를 사용할 수 있지만, 운영을 위해서는 모든 배포 옵션을 사용해야 한다.
(운영할 때에는 내장 개발 서버를 사용하지 마라.)
다양한 옵션들을 사용할 수 있으며, 사용 방법은 아래를 참조하라.

만약 다른 WSGI 서버가 있다면, 그 서버에서 WSGI 어플리케이션을 사용하는 방법에 대해 해당 서버 문서를 참조하라.
:class:`Flask` 어플리케이션 객체가 실제로 WSGI 어플리케이션임을 기억하라.

For hosted options to get up and running quickly, see
:ref:`quickstart_deployment` in the Quickstart.

.. toctree::
   :maxdepth: 2

   mod_wsgi
   wsgi-standalone
   uwsgi
   fastcgi
   cgi
