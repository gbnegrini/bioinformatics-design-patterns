---
type: book

title: Data Filter
summary: "Users need to specify filtering criteria for miRNA target search results."

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

date: "2022-01-09T00:00:00Z"

weight: 11

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

Users need to specify filtering criteria for miRNA target search results.

## Context

The [**Data Presentation**]({{< relref "patterns/mirna-target-database/data-presentation" >}}) of the most relevant results depends on the definition of search criteria.

## Solution

Use single and multiple selection menus to compose a filtering strategy. Some filtering criteria can be applied as single or multiple selection boxes in [**Flexible Data Input**]({{< relref "patterns/mirna-target-database/flexible-data-input" >}}), such as the choice of species and miRNA/family of miRNA. The [**Flexible Data Input**]({{< relref "patterns/mirna-target-database/data-filter" >}}) also acts in [**Data Presentation**]({{< relref "patterns/mirna-target-database/data-presentation" >}}). To facilitate exploration of the results, implement a text box to search for specific miRNA/target in a large list. For databases that aggregate results from multiple algorithms or validation methods, implement multiple selection boxes to allow filtering of results.

## Rationale

Tools used for miRNA research sometimes lack flexibility (Mullany et al., 2015) and user-friendly features to improve efficiency (Akthar et al., 2015). A [**Flexible Data Input**]({{< relref "patterns/mirna-target-database/data-filter" >}}) can help users restrict their results based on specific criteria, and explore results in the [**Data Presentation**]({{< relref "patterns/mirna-target-database/data-presentation" >}}). This can facilitate the knowledge discovery process when users are presented with many miRNA-target pairs.

## Related patterns

### Is contained

- [Flexible Data Input]({{< relref "patterns/mirna-target-database/flexible-data-input" >}}) from Bioinformatics IDP.

- [Data Presentation]({{< relref "patterns/mirna-target-database/details" >}}) from Bioinformatics IDP.

### Similar

- [Live Filter](http://ui-patterns.com/patterns/LiveFilter) from UI Patterns.
- [Filtering](https://www.carbondesignsystem.com/patterns/filtering/) from Carbon Design System.

## Examples

### ENCORI/starBase

![](encori_data_filter.png)

- Selection menus are available to restrict the results.
- Search box to filter for miRNA name.

---

 ### miRTarBase
 
![](mirtarbase_data_filter.png)

- Search box to filter for miRNA and target in a 21156 pages result.

### TarBase

![](tarbase_data_filter.png)

- Criteria to filter the results can be set in the left menu of the [**Data Presentation**]({{< relref "patterns/mirna-target-database/data-presentation" >}}) interface.

---

### TargetScan

![](targetscan_data_filter.png)

- Dropdown menus in the [**Flexible Data Input**]({{< relref "patterns/mirna-target-database/flexible-data-input" >}}) interface allow the users to filter the search.

## References

>Akhtar, Most Mauluda, et al. "Bioinformatic tools for microRNA dissection." Nucleic acids research 44.1 (2016): 24-44.

>Mullany, Lila E., Roger K. Wolff, and Martha L. Slattery. "Effectiveness and usability of bioinformatics tools to analyze pathways associated with miRNA expression." Cancer informatics 14 (2015): CIN-S32716.