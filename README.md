# NetworkingProject01
COMPUTER NETWORK project of fifth semester engineering.

Project Chosen: Project 1 (Designing a Proxy Server)
Group Number
SECTION - CSE 31

Group Members:
1. Name: ADARSH MALVIYA      - Roll No: 2405703
2. Name: ASHISH KUMAR MANDAL - Roll No: 24158048
3. Name: ANURAG ANAND        - Roll No: 2405417       


WHY WE CHOSE THIS PARTICULAR PROJECT?-

We selected the "Designing a Proxy Server" project for three specific reasons aligned with our educational goals:
* Direct Application-Layer Visibility: Unlike other options that deal with complex bit-level chunking or hardware, a proxy server handles 
  HTTP requests. Because HTTP is human-readable plaintext, we can easily print, inspect, and analyze network packets directly in our console, 
  which accelerates our understanding of how network protocols function.
* Core Networking Fundamentals: This project forces us to deal with essential real-world networking concepts such as socket programming, 
  TCP handshakes, multi-threaded connection handling, data caching and network security (access control lists) within a clean scope.
* Incremental Development: The structure of a proxy server allows for  modular development. We can start with a basic single-client request 
  forwarder, and progressively layer on multi-threading, logging, filtering and performance benchmarking day-by-day.


FEATURES OF THE FINAL PROJECT-

Our completed application will implement the following features to meet 
the core criteria of the assignment description:
* Concurrent Connection Handling: The server will utilize Python's threading module to accept connections from multiple simultaneous 
  clients without letting any single client's request block others.
* HTTP Request Parsing & Forwarding: The proxy will correctly intercept, parse and dynamically forward standard HTTP protocol requests, 
  returning valid server responses cleanly back to the client application.
* Response Caching Mechanism: We will implement an in-memory or disk-based cache to store static web content, applying a validation policy 
  to serve cached data quickly instead of fetching it from the origin server every time.
* Access Control & Domain Filtering: An administrative rule layer will be integrated to block access to specific blacklisted domains/URLs, 
  demonstrating basic network firewall controls.
* Comprehensive Network Logging: The proxy will actively output formatted logs tracking client IP addresses, requested URLs, response statuses, 
  and timestamps for administrative auditing.
* Robust Error Handling: The application will handle malformed requests, destination timeouts, and unreachable host exceptions gracefully 
  without crashing the core listening loop.
* Quantitative Performance Metrics: We will include built-in timing mechanisms to measure and report network latency/throughput, directly 
  comparing connections with and without the proxy's overhead.


DECLARATION OF AI USAGE & LIMITATIONS-
 
To maintain complete academic transparency and ensure deep conceptual readiness for our final demonstration and viva evaluation, we declare our 
intent to use AI tools (such as Claude/ChatGPT) under these strict- pre-defined boundaries:
* Code Template Generation: AI will be used to generate initial boilerplate templates for low-level socket connections and multi-threading loops.
* Architectural & Concepts Guide: We will use AI as a digital textbook to explain networking mechanics line-by-line (e.g., how specific socket 
  flags work, or how HTTP streams split strings into headers).
* Real-Time Error Interpretation: When encountering cryptic runtime errors common to socket interfaces (e.g., Connection Reset, Broken Pipe, 
  Address Already in Use), AI will serve as a debugger to help us isolate the failure points.

Restricting Our AI Use: 
We will explicitly restrict our AI use to the above functions. We will NOT use AI to generate the complete project codebase wholesale without 
oversight. To ensure accountability, every single line of code added to the final project will be manually reviewed, tested, modified, and documented 
with explanatory comments written by our group members to ensure absolute readiness for any live viva or demonstration testing.


