---
type: book

title: Citation
summary: "Users need to cite the database."

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

date: "2022-01-04T00:00:00Z"

weight: 31

tags:
  - miRNA

categories:
  - miRNA

authors:
  - admin
---

## Overview

![](citation.png)

## Problem

Users need to cite the database.

## Context

A miRNA target database is usually described in a journal article. Users must consult and cite this journal article when using the database to produce their results.


## Solution

Indicate in the interface the full citation for the database reference article. It is common for a database to have more than one article as it is updated and improved, so provide as many **Citations** as appropriate.


## Rationale

A **Citation** is an essential [**Informational Element**]({{< relref "patterns/mirna-target-database/informational-elements" >}}). **Citation** is necessary so that the user correctly references what database was used to produce the results in their paper. **Citation** is also helpful to point the user to the articles needed to understand the tool used.

## Related patterns

### Is contained

- [Informational Elements]({{< relref "patterns/mirna-target-database/informational-elements" >}}) from Bioinformatics IDP.

### Used with

- [Methods]({{< relref "patterns/mirna-target-database/methods" >}}) from Bioinformatics IDP.
- [Status and Statistics]({{< relref "patterns/mirna-target-database/status-and-statistics" >}}) from Bioinformatics IDP.

## Examples

### TargetScan

![](target_scan_citation.png)

---
---

### ENCORI/starBase

![](encori_citation.png)

---