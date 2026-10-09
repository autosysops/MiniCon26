# Pack It, Parse It, Pass It! Build a Custom AST-Powered QA Module for PSADT Packages

**Speaker(s):** Christian Ritter — session on the [MiniCon26](https://synedgy.com/psconfeu-minicon/) agenda.

## Abstract

You wrote a neat PSADT install script. It works. But is it good? Does it follow best practices and your organization's guidelines? And, most importantly: how do you know?

Just be honest: writing a new package often means taking an old one, ripping things apart, hot-gluing new bits onto it, and shipping it. Nothing wrong with reusing what works, until you realize you copied the mistakes along with it.

Quality Assurance is about defining what "good" means, identifying common pitfalls, and applying those rules consistently. Doing this manually for every package is tedious, time-consuming, and, well, humans make mistakes. So why not automate it?

In this session, we’ll explore what QA means for software packaging, how to turn QA rules into automated checks, and how the PowerShell Abstract Syntax Tree (AST) can become our new best friend for analyzing PowerShell code.

Using PSADT as our primary example, we’ll build our own QA checks, catch common packaging pitfalls, and integrate them into modern workflows using GitHub, CI/CD, pull requests, and automated quality gates.

The focus is PSADT, but the principles apply to other PowerShell-based packaging frameworks as well. By the end, you’ll know how to turn manual package reviews into an automated safety net, giving you more time for the important things in life, like grabbing another coffee.

