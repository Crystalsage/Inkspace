# Inkspace
This is a framework for blogs, built in Rust. 

## Current progress
*Working towards implementing HTML generator*:

*Goal*: Make the generator capable enough of generating the index template.
*Subgoal*: Generate the page skeleton/boilerplate. 
*Subsubgoal*: Find out a way to assign classes correctly.

We would like to support: 
- [x] Headings
- [x] Paragraphs
- [x] Anchor links
- [x] Lists  

## Roadmap
- [x] Build a HTML template to visualize our design.
- [ ] Write HTML generator.
- [ ] Write a Markdown parser and generate HTML using it.
- [ ] Tend to other features.

## Current design
![Some](./design.png)

## Running the blog
Currently in test mode. Use `cargo run` and it should start a server at 
some port.
