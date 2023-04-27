# The Curious Instructional Manual For Creating GitHub CLI Extensions

This repository houses a markdown-based guide for making GitHub CLI extensions.
While GitHub's official docs are a great reference and can get you started,
this guide will help you step-by-step to not only start an extension from
scratch but also teaches the basics of making robust CLI applications in Go and
how to make the most of the [go-gh](https://github.com/cli/go-gh) library.

## Intended audience

People with programming experience and familiarity with using CLI applications.
Go is a scrutable language and any previous programming experience should carry
over to reading and writing basic Go programs, though there is a chapter in
this guide on how to extend the GitHub CLI with languages other than Go.

## Contents

0. Prerequisites
1. Introduction
2. Designing our extension
3. Generating scaffolding
4. Command dispatch
5. User Input
6. Output Formatting
7. Configuration
8. Shipping your extension
9. Quick tour of other go-gh features
10. Non-Go extensions: Bash example
11. Non-Go extensions: Rust example

## Author

vilmibm (Nate Smith) <vilmibm@github.com>

- gh lol transform [-f function]
  - gh issue list but with text transform applied
  - if no args, ask which transformation (rot13, yelling, block)
  - topics: interactivity, flag handling, output formatting, REST API
- gh lol roulette [<resource>]
  - close a random resource
  - if no args, multi-select for resource type (issue, pr, discussion, etc)
  - topics: interactivity, arg handling, GraphQL API
- gh lol replace [<from>] [<to>]
  - gh repo view but with find/replace
  - if no args, ask for from and to
  - topics: interactivity, arg handling, REST API

- configuration option: rainbow true/false -- all output is rainbowed. respected in all commands.
- persistent flag: --repo/-R

I might not include replace--showing off multi-select is cool, but i think it's too much. Having two commands shows off dispatching and persistent flags and replace is too redundant with its topics.

TODO: can i work in tty/non-tty behavior detection? yes, with transform.
