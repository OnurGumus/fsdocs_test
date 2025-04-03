---
title: Documentation
category: Home
categoryindex: 1
index: 1
---

# Project Documentation

Welcome to the documentation for this project.

## Contents

* [Examples](examples.html)
* [Other documentation](other.html)

<!-- Fix case inconsistency - should be capital F to match directory name -->
- [Tutorials](Foo/index.html)

## Project Flow Diagram

<div class="mermaid text-center">
graph TD
    A[Start] --> B[Process Data]
    B --> C{Decision Point}
    C -->|Option 1| D[Result 1]
    C -->|Option 2| E[Result 2]
    D --> F[End]
    E --> F
</div>

# First-level heading

    [hide]
    let print s = printfn "%s" s

Some more documentation using `Markdown`.

    [module=Hello]
    let helloWorld() = print "Hello world!2"

## Second-level heading
With some more documentation

    [lang=csharp]
    Console.WriteLine("Hello world!");
