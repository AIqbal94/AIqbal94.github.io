---
layout: post
title: "Multifast to Fasta"
date: 2020-01-08
published: true
---

Convert a multifasta file to a fasta file with a single header

```bash
grep -v "^>" /path/to/multifasta.fa | awk 'BEGIN { ORS=""; print ">header_name\n" } { print }' > /path/to/singlefasta.fa
```
