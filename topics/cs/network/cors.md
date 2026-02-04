# Web Security: CORS

> Understanding how Cross-Origin Resource Sharing works in modern web applications.

## Background / Introduction
CORS is a security mechanism that allows or restricts resources on a web page to be requested from another domain outside the domain from which the first resource was served.

## Core Concepts
- **Preflight Request**: The browser automatically sends an `OPTIONS` request first to check if the server permits the actual request.
- **Allowed Origins**: Servers explicitly define which origins (like `http://localhost:3000`) are permitted to access resources.
- **Access-Control Headers**: A set of HTTP headers used by the server to describe which origins, methods, and headers are allowed.

## Implementation / Usage
In a backend environment (like Go with Gin), it usually involves adding middleware to set the appropriate `Access-Control-Allow-Origin` and other related headers.

## Principle / Deep Dive
The following diagram illustrates the CORS preflight and actual request flow:

![CORS Flow](../../../assets/diagrams/cors.png)

## Pitfalls / Best Practices
- **Never use `*` in production**: Be specific about allowed origins to prevent unauthorized access.
- **Handle Preflight Correctly**: Ensure your server responds to `OPTIONS` requests with a `200 OK` or `204 No Content` and the correct headers.