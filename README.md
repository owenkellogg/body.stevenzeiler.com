
# body.stevenzeiler.com

## API

API and web app that allows Steven to track his weight over time.

An HTTP/JSON interface is provided to be served behind an nginx
reverse-proxy webserver.

SSL encryption is to be provided by the nginx webserver instead of
the application.

Intended to adhere to the 12-Factor software design principles.

## Webapp

HTML & Javascript web application that communicates with the webserver
and is designed to be served as static files from nginx.

