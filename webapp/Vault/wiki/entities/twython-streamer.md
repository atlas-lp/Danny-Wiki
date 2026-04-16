---
type: entity
aliases: [TwythonStreamer]
relationships:
  - target: twython
    type: component_of
  - target: twitter-streaming-api
    type: accesses
tags: [python-class, twython]
sourced_from: Data Science From Scratch   First Principles With Python    Joel Grus, (Software Engineer)    O Reil Content
---

# TwythonStreamer

A class from the Twython library that must be subclassed to access the Twitter Streaming API, requiring overrides for its on_success and on_error methods.

## Relationships

- **component_of**: [[twython|Twython]]
- **accesses**: [[twitter-streaming-api|Twitter Streaming Api]]

---
*Extracted from: Data Science From Scratch   First Principles With Python    Joel Grus, (Software Engineer)    O Reil Content*