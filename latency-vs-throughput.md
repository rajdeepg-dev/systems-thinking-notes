# Latency vs Throughput

Understanding the difference between latency and throughput is important in backend systems.

## Latency
Latency is the time required for a request to travel through the system and return a response.

Example:
User sends request → server processes → response returned.

If the total time is 120 ms, the latency is 120 ms.

Lower latency improves user experience.

## Throughput
Throughput measures how many requests a system can handle in a given time.

Example:
A system handling 10,000 requests per second has high throughput.

## Relationship Between Them

When throughput increases, latency may also increase if system resources become limited.

System design is often about balancing these two.

## Why It Matters

Large systems like authentication services or payment gateways must maintain both:

- low latency for fast response
- high throughput for large numbers of users
