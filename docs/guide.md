# Auto-generated Test Document

This file is generated for E2E parsing.

**Document ID:** 0v8a2jcn4v0m-mspjp6g0

This document contains a variety of concise, self-contained code examples across multiple programming languages, demonstrating common patterns, data structures, I/O, and control flow to exercise parsing in a realistic yet compact way.

Each example includes a short description followed by a fenced code block.

Where helpful, examples may include brief variations in syntax or structure so the parser encounters a wider range of constructs across different ecosystems.

## PHP: JSON Response

Outputs a JSON response in PHP for a simple API endpoint. Illustrates header setting and encoding.

```php
<?php
header('Content-Type: application/json');
echo json_encode(['status' => 'ok', 'time' => time()]);
```


## Ruby: Word Count

Counts word frequencies in a sentence using Ruby’s expressive standard library. Simple and readable.

```ruby
text = "to be or not to be"
counts = Hash.new(0)
text.split.each { |w| counts[w] += 1 }
puts counts
```


## Python: Fibonacci Generator

A simple, readable Python generator for producing Fibonacci numbers. It illustrates lazy iteration and clarity.

```python
def fib(n):
    a, b = 0, 1
    for _ in range(n):
        yield a
        a, b = b, a + b

print(list(fib(10)))
```


