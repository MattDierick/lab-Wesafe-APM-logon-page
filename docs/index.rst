Welcome to Websafe Encryption on APM Logon Page documentation
=============================================================

Introduction
============

This documentation explains you how to enable Websafe Encryption Layer on APM Logon page in order to protect credentials against “credential grabbing”.

In order to build this lab you need:

*	1 x BIGIP APM+FPS
*	1 x FPS license
*	1 x APM license

To do so, we need to create 2 Virtual Servers :

*	Front end VS with Websafe FPS profile applied + Irule to internal layered VS
* Internal layered VS with APM policy


.. toctree::
   :maxdepth: 2
   :caption: BIGIP Configuration:

   configuration/Front_End_VS.rst
   configuration/Internal_VS.rst

.. toctree::
   :maxdepth: 2
   :caption: Test and check the results:

   configuration/Test.rst

.. raw:: html

  <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/GhMeHxRumf8" frameborder="0" allowfullscreen></iframe>
  </div>
