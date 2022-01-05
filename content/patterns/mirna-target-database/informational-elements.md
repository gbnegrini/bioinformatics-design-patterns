---
type: book

title: Informational elements
summary: "Users need essential information to decide if the database suits their needs."

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

date: "2022-01-04T00:00:00Z"

weight: 30

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

Users need essential information to decide if the database suits their needs.

## Context

Critical information needs to be available in the user interface to support the use of the database. The basic information includes how to interpret the tool's prediction score, if the database is updated and how to cite the database.

## Solution

The INFORMATIONAL ELEMENTS are usually contained on or accessed from the tool's main page. They do not necessarily compose a single information block in the interface but present related information whose primary purpose is to inform the user about the use and status of the tool. The main page should display the current information about the number of miRNA targets supported and the last update date (STATUS AND STATISTICS). The main page is also the preferred place to display the CITATION that users must use to reference the database. The INFORMATIONAL ELEMENTS must also comprise the METHODS used to calculate the prediction score shown in the DATA PRESENTATION.

## Rationale

INFORMATIONAL ELEMENTS should help the user quickly decide on using the database. A common problem with databases of miRNAs targets is a lack of updates (Mullany et al., 2015), so the user needs to quickly identify the STATUS AND STATISTICS of the tool. CITATION is essential so that the user correctly references what database was used to produce the results in their paper. Low interpretability of the results is one problem that affects users (Mullany et al., 2015). Thus, it is important that users can easily consult the METHODS used for target prediction.

## Related patterns

### Contains

- [Status and Statistics]({{< relref "patterns/mirna-target-database/status-and-statistics" >}}) from Bioinformatics IDP.

- [Methods]({{< relref "patterns/mirna-target-database/methods" >}}) from Bioinformatics IDP.

- [Citation]({{< relref "patterns/mirna-target-database/citation" >}}) from Bioinformatics IDP.


## Examples

### TarBase

![](tarbase_info.png)
- CITATION is highlighted on the main page.
- Statistics button on the left links to a detailed STATUS AND STATISTICS page.
- Some STATUS AND STATISTICS data are displayed on the bottom of the main page.

---

### TargetScan

![](target_scan_info.png)

- The main page display information about the METHODS used to predict miRNA targets.
- CITATION is easily visible on the bottom of the main page.

---

### ENCORI/starBase

![](encori_info.png)

- STATUS AND STATISTICS is displayed on the main page.
- CITATION is located at the bottom.

---

### miRecords

![](mirecords_info.png)
 
 - STATUS AND STATISTICS is displayed on the left column of the page.
 - The search tab links to a page containing information about the METHODS and the CITATION.
 
 ### miRDB
 
 ![](mirdb_info.png)

- The menu on the left of the main page links to STATUS AND STATISTICS, METHODS (FAQ) and CITATION.
- CITATION is also available at the bottom of the main page.

## References

>Mullany, Lila E., Roger K. Wolff, and Martha L. Slattery. "Effectiveness and usability of bioinformatics tools to analyze pathways associated with miRNA expression." Cancer informatics 14 (2015): CIN-S32716.