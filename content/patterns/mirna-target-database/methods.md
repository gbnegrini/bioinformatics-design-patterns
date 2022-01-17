---
type: book

title: Methods
summary: "Users need to know the methods used by the miRNA target search and how to interpret the tool's prediction score."

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

date: "2022-01-05T00:00:00Z"

weight: 33

tags:
  - miRNA

categories:
  - miRNA

authors:
  - admin
---

## Overview

![](methods.png)

## Problem

Users need to know the methods used by the miRNA target search and how to interpret the tool's prediction score.

## Context

The knowledge discovery process depends on the correct interpretation of the methods used by the miRNA target search tool. 


## Solution

Insert a text area or a dedicated page to briefly describe the [**Methods**]({{< relref "patterns/mirna-target-database/methods" >}}) used by the database to search for miRNA targets. A more in-depth description of the methods is usually present in the tool's journal article, reinforcing the need to present the [**Citation**]({{< relref "patterns/mirna-target-database/citation" >}}) together in the [**Informational Elements**]({{< relref "patterns/mirna-target-database/informational-elements" >}}). The meaning of classification scores should be available.


## Rationale

Low interpretability of the results is one problem that affects users (Mullany et al., 2015). Thus, it is essential that users can quickly consult the [**Methods**]({{< relref "patterns/mirna-target-database/methods" >}}) used for target prediction.

## Related patterns

### Is contained

- [Informational Elements]({{< relref "patterns/mirna-target-database/informational-elements" >}}) from Bioinformatics IDP.

### Used with

- [Status and Statistics]({{< relref "patterns/mirna-target-database/status-and-statistics" >}}) from Bioinformatics IDP.
- [Citation]({{< relref "patterns/mirna-target-database/citation" >}}) from Bioinformatics IDP.

### Similar
- [FAQ](http://ui-patterns.com/patterns/frequently-asked-questions-faq) from UI Patterns.

## Examples

### miRDB

![](mirdb_methods.png)
- Methods and prediction scores used are explained in a dedicated [**FAQ**](http://ui-patterns.com/patterns/frequently-asked-questions-faq) section.
---

### TargetScan

![](target_scan_methods.png)

- Methods used are briefly explained at the bottom of the main page.
- [**Citation**]({{< relref "patterns/mirna-target-database/citation" >}}) provides the source for an in-depth explanation.

---

### RNA22

![](rna22_methods.png)

- The explanation of how to interpret the p-value is available in the [**Data Presentation**]({{< relref "patterns/mirna-target-database/data-presentation" >}}).

## References

>Mullany, Lila E., Roger K. Wolff, and Martha L. Slattery. "Effectiveness and usability of bioinformatics tools to analyze pathways associated with miRNA expression." Cancer informatics 14 (2015): CIN-S32716.