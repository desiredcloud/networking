# Proxy vs Reverse Proxy

## Proxy Server

- **Forward Proxy:**
  - Acts on behalf of clients and forwards their requests to servers.
  - Sits between client devices (e.g., web browsers) and the internet.
  - Responsible for handling client requests, forwarding them to target servers, and sending back responses.
  - Common use cases include content filtering, access control, and anonymizing client requests.

- **Client Perspective:**
  - Appears as a gateway to clients, intercepting outgoing requests and forwarding them to the target server.

- **Server Perspective:**
  - From the server's perspective, the proxy server is the client making the requests.

## Reverse Proxy

- **Reverse Proxy:**
  - Operates on behalf of servers and handles incoming client requests.
  - Sits between client devices and a server or group of servers (backend servers).
  - Responsible for load balancing, SSL termination, caching, compression, and other tasks before forwarding requests to backend servers.
  - Helps distribute client requests across multiple backend servers for improved performance and fault tolerance.

- **Client Perspective:**
  - Appears as the endpoint for the requested service from the client's perspective.

- **Server Perspective:**
  - From the server's perspective, the reverse proxy acts as the gateway receiving incoming requests.

## Key Differences

- **Direction:**
  - Proxy: Forward direction, handling outgoing client requests.
  - Reverse Proxy: Reverse direction, managing incoming client requests and directing them to backend servers.

- **Perspective:**
  - Proxy: Gateway for clients to access external services.
  - Reverse Proxy: Endpoint for the requested service from the client's perspective.

- **Use Cases:**
  - Proxy: Content filtering, access control, anonymizing client requests.
  - Reverse Proxy: Load balancing, SSL termination, caching, compression, improving server performance, and reliability.
