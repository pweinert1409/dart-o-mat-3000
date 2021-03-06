.. _Recognition:

===========
Recognition
===========

Recommendation on recognition software
======================================

As this project is developed depending on the |recognition_software| of Niels Lüdemann it is recommended to use it.

.. |recognition_software| raw:: html

    <a href="https://github.com/nluede/cvdarts" target="_blank">recognition software</a>

RESTful API Requests
====================

You can use any other recoginition as well, as long as it is propagating it's throws and next player via a GET Request to the scoreboard engine in this format:

1. URL to insert a throw /game/throw/*number-of-throw*/*modifier-of-throw*

  * Example: Single 20 will be /game/throw/20/1
  * Example: Miss will be /game/throw/0/1
  * Example: Double 18 will be /game/throw/18/2

2. URL to switch to next player /game/nextPlayer

For a full overview of possible API calls refer to :ref:`API <API>`
