---
type: book

title: Status and Statistics
summary: "Users need to know the current information about the number of miRNA targets supported and the database's last update date."

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

date: "2022-01-05T00:00:00Z"

weight: 32

tags:
  - miRNA

categories:
  - miRNA

authors:
  - admin
---

## Overview

MOCKUP

## Problem

Users need to know the current information about the number of miRNA targets supported and the database's last update date.

## Context

Users can choose a database based on information about update frequency and the number of cataloged miRNA targets.


## Solution

Insert a dedicated section to show the date of the last update and the relevant sequence numbers in the database, preferably on the main page. The number of species, cell types, and papers that cited the database can also be highlighted.


## Rationale

[**Status and Statistics**]({{< relref "patterns/mirna-target-database/status-and-statistics" >}}) is an essential INFORMATIONAL ELEMENT. A common problem with databases of miRNAs targets is a lack of updates (Mullany et al., 2015), so the user needs to identify the [**Status and Statistics**]({{< relref "patterns/mirna-target-database/status-and-statistics" >}}) of the tool quickly.

## Related patterns

### Is contained

- [Informational Elements]({{< relref "patterns/mirna-target-database/informational-elements" >}}) from Bioinformatics IDP.

### Used with

- [Methods]({{< relref "patterns/mirna-target-database/methods" >}}) from Bioinformatics IDP.
- [Citaion]({{< relref "patterns/mirna-target-database/citation" >}}) from Bioinformatics IDP.

## Examples

### miRDB

![](mirdb_status.png)
- Link for [**Status and Statistics**]({{< relref "patterns/mirna-target-database/status-and-statistics" >}}) in the left menu.
- Dedicated page displays all database update details.
---

### ENCORI/starBase

![](encori_status.png)

---

### TarBase

![](tarbase_status.png)

- Dedicated page to [**Status and Statistics**]({{< relref "patterns/mirna-target-database/status-and-statistics" >}}).
- Interactive plots allow the user to explore the data.

## References

>Mullany, Lila E., Roger K. Wolff, and Martha L. Slattery. "Effectiveness and usability of bioinformatics tools to analyze pathways associated with miRNA expression." Cancer informatics 14 (2015): CIN-S32716.