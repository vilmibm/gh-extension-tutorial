# The Curious Instructional Manual For Creating GitHub CLI Extensions

This repository houses a markdown-based guide for making GitHub CLI extensions.
While GitHub's official docs are a great reference and can get you started,
this guide will help you step-by-step to not only start an extension from
scratch but also teaches the basics of making robust CLI applications in Go and
how to make the most of the [go-gh](https://github.com/cli/go-gh) library.

## Intended audience

People with programming experience and familiarity with using CLI applications.
Go is a scrutable language and any previous programming experience should carry
over to reading and writing basic Go programs, though there are chapters in
this guide on how to extend the GitHub CLI with languages other than Go.

## Contents

0. [Prerequisites](./chapters/00.md)
1. [Introduction](./chapters/01.md)
2. [Designing our extension](./chapters/02.md)
3. [Generating scaffolding](./chapters/03.md)
4. [Command dispatch](./chapters/04.md)
5. [User Input](./chapters/05.md)
6. [Calling the GitHub API](./chapters/06.md)
7. [Output Formatting](./chapters/07.md)
8. [Configuration](./chapters/08.md)
9. [Shipping your extension](./chapters/09.md)
10. [Non-Go extensions: Bash example](./chapters/10.md)
11. [Non-Go extensions: Rust example](./chapters/11.md)

## Author

vilmibm (Nate Smith) <vilmibm@github.com>
