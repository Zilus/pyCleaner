# pycleaner

A very simple php injection cleaner.

I ran into some unfortunate php injection on my server, this script aims to remove safely this sort of things

I found a lot of files with comments and php code like:

- `/*12345*/`
- `@include "rhgsw`

This script looks in all php files for this strings and deletes them (using replace REGEX)