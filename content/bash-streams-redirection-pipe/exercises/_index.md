---
title: "Exercises"
date: 2022-04-08T13:54:05-05:00
draft: false
weight: 3
---

## Exercises

{{% children %}}

## Questions & Answers

### What are the three data streams in Bash?

{{% expand "CLICK FOR ANSWER" %}}
1. `STDIN`
1. `STDOUT`
1. `STDERR`
{{% /expand %}}

### What is the purpose of `STDIN`?

{{% expand "CLICK FOR ANSWER" %}}
`STDIN` is the mechanism for passing data to a `bash` command or script.
{{% /expand %}}

### What is the purpose of `STDOUT`?

{{% expand "CLICK FOR ANSWER" %}}
`STDOUT` is the repository of any standard output generated by the command or script.
{{% /expand %}}

### What is the purpose of `STDERR`?

{{% expand "CLICK FOR ANSWER" %}}
`STDERR` is the repository of any error output generated by a command or script.
{{% /expand %}}

### When running a command or script from a `bash` shell where is `STDOUT` & `STDERR` directed?

{{% expand "CLICK FOR ANSWER" %}}
By default `STDOUT` & `STDERR` are routed to the terminal that invoked the command or script.
{{% /expand %}}

### How can `STDOUT` be redirected from a terminal window to a file?

{{% expand "CLICK FOR ANSWER" %}}
By using the `STDOUT` redirection write operator `>` and designating a file to write the contents to.

Additionally, the `STDOUT` redirection append operator `>>` and designating a file to append the contents to.
{{% /expand %}}

### How can `STDOUT` be redirected to the `STDIN` of the following command?

{{% expand "CLICK FOR ANSWER" %}}
By using the pipe operator `|`, the `STDOUT` generated by one command is converted into the `STDIN` of the following command.
{{% /expand %}}