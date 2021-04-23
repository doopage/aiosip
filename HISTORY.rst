.. :changelog:

History
-------

1.0.0 (2021-04-23)
------------------

* Fixed error when performing transactions with the server
* Fixed issue where you could not recognize sent calls/messages
* Support making calls with SIP server requires authorization
* Fixed an issue where the call status change could not be detected
* Eliminate pointless authorizations when making calls
* Rebuild the Authorization header in the correct syntax
* Support to terminal the call after making a call (Example TimeoutError)
* Fixed a bug where the CANCEL event in the call was not handled properly
* Upgrade Pipfile.lock to remove potential security problems
* Code refactoring

0.2.0 (2017-09-14)
------------------

* A lot of bugs fixes
* Proxy support
* aiohttp dependency removed in favor of multidict
* Code refactoring
* Special thanks to Simon Gomizelj (vodik) on this release: almost come from his contributions

0.1.0 (2014-12-28)
------------------

* First release on PyPI.
