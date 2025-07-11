## WebSocket Echo Server
We run a free very simple endpoint server with support for websockets and server-sent events (SSE) so that you can test your websocket and SSE clients easily.

The server is designed for testing HTTP proxies and clients. It echoes information about HTTP request headers and bodies back to the client.

The endpoint is https://echo.websocket.org/

## Behavior
Any messages sent from a websocket client are echoed as a websocket message.
Visit https://echo.websocket.org/.ws in a browser for a basic UI to connect and send websocket messages.
Request https://echo.websocket.org/.sse to receive the echo response via server-sent events.
Request any other URL to receive the echo response in plain text.
