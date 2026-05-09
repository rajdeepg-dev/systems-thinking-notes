# Caching Basics

Caching is used to reduce repeated computation and improve system performance.

## What is Caching?

A cache stores frequently used data temporarily so that future requests can be served faster.

Instead of processing the same request repeatedly, the system can return the cached result.

## Why Caching Matters

Caching helps:

- reduce server load
- improve response time
- reduce database queries
- improve scalability

## Example

Without cache:

User Request → Server → Database → Response

With cache:

User Request → Cache → Response

If the data is not found in cache:

User Request → Server → Database → Cache → Response

## Common Use Cases

- User session storage
- Frequently visited pages
- API response storage
- Authentication tokens

## Tradeoff

Caching improves speed but may serve outdated data if not refreshed correctly.

This is why cache invalidation is considered an important system design problem.
