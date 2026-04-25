# Gregory Dale Collins

I build tools that fix broken AI output.

## Current focus

Fixing broken JSON from AI.

You get JSON from ChatGPT or Claude.

It looks right.

## Example

This looks fine:

```
{ name: "Greg", items: ["a", "b",], done: True }
```
But it breaks when you use it.

Fixed version:

```json
{
  "name": "Greg",
  "items": ["a", "b"],
  "done": true
}
```
That’s what I’m working on.

---

## Tools

These are built around making AI output usable.

- https://datatool.dev  
  Fix broken AI-generated JSON.

- https://toolidx.dev  
  Find AI tools that actually work. Structured. Verified. Ready to use.

- https://agenticwatch.dev  
  Real-world testing and notes on AI tools.

---

## What I care about

- fix structure first  
- don’t guess missing data  
- fail safely  
- test against real examples  

---

## Background

Former Oracle Senior Systems Administrator.  
Founder. Patent holder.

Still building systems that solve real problems.
