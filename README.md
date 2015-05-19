# Explaining Rest & HTTP
###What is REST?

**Rest** is the underlying architectural pattern of the web. It allows browsers and servers to communicate in complex ways without either knowing much about one another.

The key constraint is that the server and the client must agree on the media type used. Usually, this is HTML. You can use other media types by specifying other types of headers. The client sends over the application-type/ in its **ACCEPT** header, whereas the server responds with the format as denoted in **CONTENT-TYPE**.

REST uses four standards:
1. **HTTP** -hypertext transfer protocol
2. **URL** -universal resource locator
3. Resource representations -xml, html, json, etc
4. **MIME** (multipurpose internet mail extensions) types - text/html, plain/text, image/gif

###HTTP: The Uniform Interface

