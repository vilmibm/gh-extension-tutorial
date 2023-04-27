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
6. Calling the GitHub API
7. Output Formatting
8. Configuration
9. Shipping your extension
10. Non-Go extensions: Bash example
11. Non-Go extensions: Rust example

## Author

vilmibm (Nate Smith) <vilmibm@github.com>
