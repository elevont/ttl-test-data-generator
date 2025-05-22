<!--
SPDX-FileCopyrightText: 2025 Robin Vobruba <hoijui.quaero@gmail.com>

SPDX-License-Identifier: CC0-1.0
-->

# RDF/Turtle test files

[![REUSE status](
    https://api.reuse.software/badge/github.com/elevont/ttl-test-data-generator)](
    https://api.reuse.software/info/github.com/elevont/ttl-test-data-generator)

This repo contains an few [RDF/Turtle] test files, partly originating from [turtlefmt].
It also conaitns a CI script, that on each change to the repos sources,
gathers all the sources in this repo,
and combines them with a (much bigger) set of [RDF/Turtle] test files from [W3C],
specifically:

- <https://github.com/w3c/rdf-tests>
- <https://www.w3.org/2013/TurtleTests>

These combined sources -
which is probably what yo uare looking to use when reading this -
can be found in [the generated repo][target]

The primary use-case of having this test files is for unit-testing serializers
and pretty-printers for the [RDF/Turtle] syntax.

[RDF/Turtle]: https://dvcs.w3.org/hg/rdf/raw-file/default/rdf-turtle/index.html
[turtlefmt]: https://github.com/helsing-ai/turtlefmt
[W3C]: https://www.w3.org/
[target]: https://github.com/elevont/ttl-test-data/tree/master/input