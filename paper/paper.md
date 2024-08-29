---
title: 'BioHackathon 2024 report: Ruby coding with help of LLMs'
title_short: 'BioHackathon 2024 #26: Ruby coding with LLMs'
tags:
  - bioinformatics
  - Ruby
  - LLM
authors:
  - name: Naohisa Goto
    orcid: 0000-0000-0000-0000
    affiliation: 1
  - name: Second Author
    orcid: 0000-0000-0000-0000
    affiliation: 2
  - name: Last Author
    orcid: 0000-0000-0000-0000
    affiliation: 3
affiliations:
  - name: Bioinformatics Center, Research Institute for Microbial Informatics, Osaka University, Japan
    index: 1
  - name: Second Affiliation
    index: 2
  - name: Third Affiliation
    index: 3
date: 30 August 2024
cito-bibliography: paper.bib
event: BH24JA
biohackathon_name: "DBCLS BioHackathon 2024"
biohackathon_url:   "http://2024.biohackathon.org/"
biohackathon_location: "Fukushima, Japan, 2024"
group: Project 26
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/biohackathon-japan/bh24-ruby-coding-with-help-of-llms.git
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: First Author \emph{et al.}
---


# Introduction

As part of the DBCLS BioHackathon 2024, we here report...

# Formatting

This document use Markdown and you can look at [this tutorial](https://www.markdowntutorial.com/).

## Subsection level 2

Please keep sections to a maximum of only two levels.

## Tables and figures

Tables can be added in the following way, though alternatives are possible:

Table: Note that table caption is automatically numbered and should be
given before the table itself.

| Header 1 | Header 2 |
| -------- | -------- |
| item 1 | item 2 |
| item 3 | item 4 |

A figure is added with:

![Caption for BioHackrXiv logo figure](./biohackrxiv.png)

# Other main section on your manuscript level 1

Lists can be added with:

1. Item 1
2. Item 2

# Citation Typing Ontology annotation

You can use [CiTO](http://purl.org/spar/cito/2018-02-12) annotations, as explained in [this BioHackathon Europe 2021 write up](https://raw.githubusercontent.com/biohackrxiv/bhxiv-metadata/main/doc/elixir_biohackathon2021/paper.md) and [this CiTO Pilot](https://www.biomedcentral.com/collections/cito).
Using this template, you can cite an article and indicate _why_ you cite that article, for instance DisGeNET-RDF [@citesAsAuthority:Queralt2016].

The syntax in Markdown is as follows: a single intention annotation looks like
`[@usesMethodIn:Krewinkel2017]`; two or more intentions are separated
with colons, like `[@extends:discusses:Nielsen2017Scholia]`. When you cite two
different articles, you use this syntax: `[@citesAsDataSource:Ammar2022ETL; @citesAsDataSource:Arend2022BioHackEU22]`.

Possible CiTO typing annotation include:

* citesAsDataSource: when you point the reader to a source of data which may explain a claim
* usesDataFrom: when you reuse somehow (and elaborate on) the data in the cited entity
* usesMethodIn
* citesAsAuthority
* citesAsEvidence
* citesAsPotentialSolution
* citesAsRecommendedReading
* citesAsRelated
* citesAsSourceDocument
* citesForInformation
* confirms
* documents
* providesDataFor
* obtainsSupportFrom
* discusses
* extends
* agreesWith
* disagreesWith
* updates
* citation: generic citation


# Results


# Discussion

...

## Acknowledgements

...

## References
