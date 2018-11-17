Balrog
======

Go based webserver. [Caddy][] can do most of what Balrog does and is an awesome static file server. It is feature complete and has support options. Balrog is under initial development and is not ready for external use.


Features / ToDo
---------------

* [ ] Allow for custom error response pages:
	* 404 - File Not Found page
	* 500 - Internal Server Error page
	* Possible Hotlinking Denial:
		* 409 - Conflict
		* 412 - Precondition failed
		* 418 - I'm a Teapot
		* 420 - Enhance Your Calm
		* 502 - Bad Gateway
		* 510 - Not Extended
* [ ] Asset minifier (CSS and JavaScript)
* [ ] Find extensionless resource based on Accept header
* [ ] GZip compression
* [ ] HTTP/2 support
* [ ] HTTPS support
* [ ] Matrix URL handling
* [ ] Static File Server




[Caddy]: https://caddyserver.com/

