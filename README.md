# Learning Knowledge Graph

@Author: 王翊嘉 / abcd1234  
@Email: abcd1234dbren@yeah.net

This project is a record for me to learn knowledge graph. And the tutorial of mine is [`https://www.ljjyy.com/archives/2019/11/100629.html`](https://www.ljjyy.com/archives/2019/11/100629.html)

## What will I do?

1. Use this to record, my comprehension of knowledge graph.
2. Use this project, to make a program, based on python, to extract a knowledge-graph from lots of given books.
3. Change this project, first to `Rust`, then `CangJie`, then try to a SaaS.

## Session I. my comprehension & learning-records

### @2024.09.28: the method to modelize a knowledge graph

#### Traid (use `RDF` to represent)

Today, I learnt some basic knowledge. The first thing is that, we always use `traid` to represent a knowledge graph.

In my opinion, the `traid` is like a sentence: `Subject + verb + Object`. As for some examples, `cat is an animal`, can be written as `cat -> is -> animal`. Another example is `Linus is the father of Linux`, can be converted as `Linus -> (is) the father of -> Linux`. Is that appropriate?

And there is a good tutorial from [`runoob.com`](www.runoob.com/rdf/rdf-rules.html).

#### RDFS (RDF -> some fixed keyword -> RDFS)

As for `RDFS`, there are some fixed verbs, such as: Class, subClassOf, Domain, Range, type, etc. And there are two layers now: `schema` and `instance`.

But, there are other questions now: 'What are `schema` and `instance`? Why use them?' From the tutorial, I don't know anything about that. So, I try to skip that.

#### 5 useful structures

As reading more, I know: there are 5 useful structures to represent a knowledge graph: `RDF/(RDFS)`, `OWL`, `SPARQL`, `JSON-LD`, `KG Embedding`.

#### Summarize

When want to modelize a knowledge-graph, we can use one of the 5 structures. And, actually there are the 6th: `HTML5 microdata`.

Emmm, that tutorial is not very concise... At the 2nd chapter, it said that, the 6 frequently-used language are:

- RDF & RDFS
- OWL & OWL2
- SPARQL
- JSON-LD
- RDFa
- HTML5 microdata

**I think, we need to choose the most suitable structure!**

Now, since we have the method to modelize 'Knowledge-Graph', we can try to think the next 2 things:

1. How to choose and how to make it to codes?
2. How to generate it from given knowledge?

Tomorrow, I will try to solve the 2nd problem.
