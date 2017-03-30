Create internal VIP2VIP Virtual Server
======================================

Create an internal Virtual Server. This VS will be called by the Front End VS only. Except if you want to keep this VS available for some customers that will not pass through Websafe protection. In that case, create a standard VS.

.. note::

  SSL concerns :

  * On this VS, you can decide to not assign any SSL profile on client side, this was already done on the front end VS.
  * But if you want to enable Network Access and AppTunnel support, you have to assign SSL client profile on this VS. Don't forget to assign an SSL server profile on the Front End VS.

Assign the right APM policy and test.
