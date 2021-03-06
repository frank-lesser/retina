# Retina

[![Build Status](https://travis-ci.org/m-ender/retina.svg?branch=master)](https://travis-ci.org/m-ender/retina)
[![Release](https://img.shields.io/github/release/m-ender/retina.svg)](https://github.com/m-ender/retina/releases)

Retina is a regex-based recreational programming language. Every program works by reading a (finite) string from standard input, transforming it via a series of regex operations (e.g. counting matches, filtering lines, and most of all substituting). Retina was built on top of [.NET's regex engine](https://docs.microsoft.com/en-us/dotnet/standard/base-types/regular-expressions), but provides its own, more powerful substitution syntax.

Retina was mainly developed for [code golf](https://en.wikipedia.org/wiki/Code_golf) which may explain its very terse configuration syntax and some weird design decisions.

## Running Retina

The easiest way to try out Retina is to use it right in your browser at [Try It Online!](https://tio.run/#retina1)

Up-to-date .NET Core binaries of Retina are provided as Github releases. Alternatively, you can build it yourself from the C# sources. The code requires .NET Core 2.2.

Source files can simply be passed as command-line arguments. For details of ways to invoke Retina [see the docs](https://github.com/m-ender/retina/wiki/The-Language#basics).

## How does it work?

Full documentation of the language **[can be found in the Wiki](https://github.com/m-ender/retina/wiki/The-Language)**. For a (hopefully) more accessible introduction to the language's basic features see the **[annotated example programs](https://github.com/m-ender/retina/tree/master/Examples)**. It might also be worth having a look at the **[changelog](https://github.com/m-ender/retina/blob/master/CHANGELOG.md)**.

## Using Retina

If you actually go to the trouble of learning Retina's fairly obscure syntax, you'll find that it's a surprisingly effective productivity tool when it comes to transforming text documents. If [VS Code](https://code.visualstudio.com/) is your text editor of choice, you can install the [**Retinate**](https://marketplace.visualstudio.com/items?itemName=m-ender.retinate) extension, which lets you use Retina scripts as a powerful alternative to regular *Search and Replace*.
