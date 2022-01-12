---
type: book

title: Data Presentation
summary: "Users need to visualize and interact with miRNA target search results."

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

date: "2022-01-04T00:00:00Z"

weight: 20

tags:
  - miRNA
  
categories:
  - miRNA

authors:
- admin

---

## Overview

![](data-presentation.png)

## Problem

Users need to visualize and interact with miRNA target search results.

## Context

The results of the miRNA target search need to be presented to the user in a minimally interactive way. This includes [**Data Filter**]({{< relref "patterns/mirna-target-database/data-filter" >}}), [**Sort by Columns**](http://ui-patterns.com/patterns/SortByColumn), and [**Export**](https://www.carbondesignsystem.com/community/patterns/export-pattern/) the results.

## Solution

Present the search results in tabular format, in which each row corresponds to a miRNA-mRNA interaction pair. At least one of the columns should contain a score used by the tool for predicting the miRNA-target relationship. This score should be described in the [**Methods**]({{< relref "patterns/mirna-target-database/methods" >}}). Columns with numerical values, such as the score, should allow SORT BY COLUMN. [**Data Filter**]({{< relref "patterns/mirna-target-database/data-filter" >}}) should allow the search specification by target, miRNA, or prediction tools. The [**Details**]({{< relref "patterns/mirna-target-database/details" >}}) of the miRNA-target interaction should be referenced in the [**Data Presentation**]({{< relref "patterns/mirna-target-database/data-presentation" >}}). Users should be able to [**Export**](https://www.carbondesignsystem.com/community/patterns/export-pattern/) the results using a download button located in the [**Data Presentation**]({{< relref "patterns/mirna-target-database/data-presentation" >}}) area.

## Rationale

Bioinformatics tool users widely use tabular data due to the ease of working with spreadsheet software (Rideout et al., 2016). A [**Data Presentation**]({{< relref "patterns/mirna-target-database/data-presentation" >}}) containing a table and interactive filters gives the user the possibility to explore the data quickly. This format also favors the export of miRNA-target pairs, which can be easily imported into interaction visualization software such as Cytoscape.

## Related patterns

### Contains

- [Data Filter]({{< relref "patterns/mirna-target-database/data-filter" >}}) from Bioinformatics IDP.

- [Details]({{< relref "patterns/mirna-target-database/details" >}}) from Bioinformatics IDP.

- [Sort by Column](http://ui-patterns.com/patterns/SortByColumn) from UI Patterns.

- [Export](https://www.carbondesignsystem.com/community/patterns/export-pattern/) from Carbon Design System.

### Used with

- [Methods]({{< relref "patterns/mirna-target-database/methods" >}}) from Bioinformatics IDP.

## Examples

### miRDB

![](mirdb_data_presentation.png)

- Tabular format.
- [**Details**]({{< relref "patterns/mirna-target-database/details" >}}) link to a new page, avoiding clutter in the table.
- A score column is present and the interpretation of this value is described at the [**Methods**]({{< relref "patterns/mirna-target-database/methods" >}}).

---

### ENCORI/starBase

![](encori_data_presentation.png)

- miRNA-target organized in tabular format.
- Multiple filter available.
- Data can be exported in Excel or text format.
- Columns can be sorted.

---

### RNA22

![](./rna22_data_presentation.png)

- Scoring metrics are available and some [**Methods**]({{< relref "patterns/mirna-target-database/methods" >}}) explanation is visible.
 - Columns can be sorted.
 - [**Details**]({{< relref "patterns/mirna-target-database/details" >}}) about miRNA-target interaction (heteroduplex) are provided directly at the table.

---

### miRTarBase
 
![](./mirtarbase_data_presentation.png)

- miRNA-target pairs in tabular format.
- One-click to export the results.
- Filter box with an example is provided.

## References

>Rideout, Jai Ram, et al. "Keemei: cloud-based validation of tabular bioinformatics file formats in Google Sheets." Gigascience 5.1 (2016): s13742-016.