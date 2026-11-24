---
title: "Python Concurrency with asyncio"
author: Matthew Fowler
publisher: Manning Publications
publication_year: 2022
pages: 376
date_added: 2025-04-13
type: book
status: in-progress
progress: "In progress"
categories:
  - Software Development
  - Python
  - Concurrency
  - Asynchronous Programming
formats:
  - Paperback
  - E-book
---

# Python Concurrency with asyncio

![Python Concurrency with asyncio](https://covers.openlibrary.org/b/isbn/9781617298660-L.jpg)

**Author:** Matthew Fowler  
**Reading status:** In progress  
**Publisher:** [Manning Publications](https://www.manning.com/books/python-concurrency-with-asyncio)

## Review

An excellent book covering concurrency and parallelism, the differences between them, multiprocessing, multithreading, the Global Interpreter Lock (GIL), and asynchronous programming with asyncio.

It goes well beyond the basics of async/await, exploring a wide range of asyncio features and their practical applications, including:

- Coroutines, tasks, futures, and the event loop.
- Task cancellation, timeouts, and error handling.
- Combining asyncio with multiprocessing to handle CPU-bound workloads.
- Integrating blocking operations into asynchronous applications using threads without blocking the event loop.
- Concurrent HTTP requests, web applications, and microservices.
- Asynchronous database access and non-blocking database drivers.
- Streams, synchronization primitives, asynchronous queues, and subprocess management.

The book is well structured, easy to follow, and relatively quick to read. I would recommend running and experimenting with the code examples rather than simply reading through them.

What makes this book particularly valuable is that it explains not only how to use asyncio but also why different concurrency techniques work, when to choose one over another, and what can go wrong. It helps build a solid mental model of asynchronous execution rather than simply teaching a collection of APIs. This makes it useful for designing, debugging, and improving real-world Python applications.

The material is excellent overall, although there are occasional typos, including in the original English edition. Since the book was published in 2022, it is also worth consulting the current Python documentation for newer asyncio features, such as `TaskGroup` and `asyncio.timeout()`.

## Resources

- [Official book page](https://www.manning.com/books/python-concurrency-with-asyncio)
- [Chapter-by-chapter contents](https://livebook.manning.com/learn/python-concurrency-with-asyncio)
- [Python asyncio documentation](https://docs.python.org/3/library/asyncio.html)
