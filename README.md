# node_http_soap
Why import an entire client that parses like a hog for one HTTP request?...

I wrote a small wrapper around the node.js http module since I couldn't find a SOAP client package on npm that supported:
* Keep-alive
* Gzip compression
* A XML-to-JSON parser that didn't suck
