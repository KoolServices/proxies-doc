API
===

.. _api_key:

/api/v1/proxies
------------


.. code-block:: console

   > GET /api/v1/proxies?service=google.com&country=United%20States&isp=Cox%20Communications&limit=1 HTTP/1.1
   > Accept: */*
   > Authorization: APIKEY dev-key
   >
   * Mark bundle as not supporting multiuse
   < HTTP/1.1 200 OK
   < X-Powered-By: Express
   < Content-Type: application/json; charset=utf-8
   < Content-Length: 2537
   < ETag: W/"9e9-S7LtMa3k2OJQZ0FRSqNQiMd489w"
   < Date: Mon, 25 Apr 2022 20:57:56 GMT
   < Connection: keep-alive
   < Keep-Alive: timeout=5
   
   <
   [{"id":"ef597dfb-6dcc-4db5-bc53-66e17aab5b34","readableName":"proxy-01FXZGX4229N7SSKHZWDV5SYKX","active":true,"ip":"0.0.0.0","port":4145,"protocols":
   ["socks5"],"service":"","reliability":{"uptime":9,"speed":9,"reputation":1},"createdAt":"2022-03-12T16:55:35.235Z", "ipData":{"country":"United States","city":"Baton 
   Rouge","locale":"America/Chicago","isp":"Cox Communications 
   Inc.","ipAddress":"72.195.34.42","ipRange":""},"lastCheckedAt":"2022-04-25T20:57:27.585Z","supportsHTTPS":false}]
   



.. autosummary::
   :toctree: generated

   lumache
