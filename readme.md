# get-github-repos.sh

> **Date started**: 29 Aug 2021

> **Date ended**: 29 Aug 2021

## Description

Learning project for bash.

## Usage

run: `source ./loadenv.sh && ./get-github-repos.sh`

## Learnings

- Tonne of learnings in bash (commented in the script)
- Had a rough time with escaping text for the GQL query.

### Lessons

- Everything inside single quotes is preserved literally without exception. That's why we need a lot of escaping with double quotes

- Ensure the exact text that you want to be sent is being sent. Do some simple tests

## Resources

JQ Play

- https://jqplay.org/

Token for GQL

- https://docs.github.com/en/graphql/guides/forming-calls-with-graphql

JQ for manipulating JSON in bash

- https://stedolan.github.io/jq/manual/#Builtinoperatorsandfunctions

Arrays

- https://opensource.com/article/18/5/you-dont-know-bash-intro-bash-arrays

Loading enviornment variables

- https://gist.github.com/mihow/9c7f559807069a03e302605691f85572

Regex matching

- https://stackoverflow.com/questions/18709962/regex-matching-in-a-bash-if-statement
