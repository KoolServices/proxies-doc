Usage
=====

.. _api_key:

API Key
------------

To use koolproxies, first get a API key from https://proxies.kool.services

For the documentation, we will be acting like the API key is:

.. code-block:: console

   dev-key

.. _using_api:

Using the API
----------------

There are no language client libraries right now but you can easily use a HTTP client library for your language.
The base API host of koolproxies is ``api.proxies.kool.services``.

When sending requests, add the API key to the ``Authorization`` header, make sure the prefix is **APIKEY**.

To do a basic ping of the API with curl:

.. code-block:: console

   curl -H "Authorization: APIKEY dev-key" https://api.proxies.kool.services/api/v1/ping
   
   
