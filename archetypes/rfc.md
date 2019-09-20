---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
date: {{ dateFormat "2006-01-02" .Date }}
# tags could be list of anything, like for eg.: `[ type_system language_construct vm ]` etc.
tags: [ ] 
author: Name Surname <email@php.net>
proposedVersion: 8.0
description: |
    Short description in form of article pitch 
draft: true
---

## Introduction

Short introduction
<!--more-->

## Proposal

## Backwards Incompatible Changes

## Proposed PHP Version(s)

Targets next PHP 8.x.

## RFC Impact

### To SAPIs

None.

### To Existing Extensions

None.

### To Opcache

None.

### New Constants

None.

## Future Scope

## Proposed Voting Choices

As this is a language change, a 2/3 majority is required.

The vote is a straight Yes/No vote for accepting the RFC and merging the patch.

## Patches and Tests

Not implemented.

## Implementation

## References

* [ref](https://php.net/link)
