# Samizdat-Plugin-Example

The reference **example** module for [Samizdat](https://fakenews.com) — a minimal,
self-contained Plugin+Controller+Model trio with templates and its own database
schema migration. A good starting point when writing a new plugin distribution.
Extracted from the monorepo with history; requires core **Samizdat**.

    perl Makefile.PL && make && make test    # core on PERL5LIB
    make install

Enable via `extraplugins: [Example]`.
