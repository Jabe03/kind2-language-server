# Kind2 Language Server

## Gateway

The gateway is a small Node.js WebSocket bridge used to connect a browser-based client to the Java language server. It listens on a local WebSocket endpoint, starts the Java server on an ephemeral TCP port, and forwards LSP messages back and forth so the browser can talk to the server without needing a direct socket connection.
