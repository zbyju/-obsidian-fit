# Book information
- Author: #matthew-boyle
- Tags: #book
---
# Notes
There are 3 main pillars:
1. Ubiquitous language
	- The process of building a common language (between engineers and business)
2. Strategic design
	- The process of mapping out the business domain and bounded contexts
3. Tactical design
	- The process of defining the specifics of the design (entities, aggregates, value objects).

## Ubiquitous language
= overlap of the language engineers and domain experts use

Important that engineers challenge domain experts (especially in the edge cases) such that the definitions are sounded and consistent.

The established language should be used inside the code itself.

Ubiquitous language should always be applied only to one bounded context.
- One word might mean something else in different contexts and that's okay.
- The language should be rigorous, it shouldn't lose its meaning.
	- Customer might mean different things in different contexts, don't try to merge the meanings because we are losing rigorousness.

To capture such language it is needed to talk to domain experts a lot, try to attend their meetings and take notes, especially list all the words that you don't know.
### Bounded context
We should avoid applying the same language across the whole project and we should create contexts in which it makes sense to have a ubiquitous language.

These bounded contexts often need to interact which is done through:
1. Open Host Service
2. Published language
3. Anti-corruption layer
#### Open Host Service
This is the way of giving other systems access to ours. 
## Strategic design
## Tactical design

---

# Summary

---

# Final thoughts
## Content
## Style
## Value
## Comparisons and links

---