---
type: book

title: Informational Elements
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

![](informational-elements.png)

## Problem

Users need essential information to decide if the database suits their needs.

## Context

Critical information needs to be available in the user interface to support the use of the database. The basic information includes how to interpret the tool's prediction score, if the database is updated and how to cite the database.

## Solution

The **Informational Elements** are usually contained on or accessed from the tool's main page. They do not necessarily compose a single information block in the interface but present related information whose primary purpose is to inform the user about the use and status of the tool. The main page should display the current information about the number of miRNA targets supported and the last update date ([**Status and Statistics**]({{< relref "patterns/mirna-target-database/status-and-statistics" >}})). The main page is also the preferred place to display the [**Citation**]({{< relref "patterns/mirna-target-database/citation" >}}) that users must use to reference the database. The **Informational Elements** must also comprise the [**Methods**]({{< relref "patterns/mirna-target-database/methods" >}}) used to calculate the prediction score shown in the [**Data Presentation**]({{< relref "patterns/mirna-target-database/data-presentation" >}}). A [**Contact**]({{< relref "patterns/mirna-target-database/contact" >}}) information should also be displayed to enable users to reach out for questions and suggestions.

## Rationale

**Informational Elements** should help the user quickly decide on using the database. A common problem with databases of miRNAs targets is a lack of updates (Mullany et al., 2015), so the user needs to quickly identify the [**Status and Statistics**]({{< relref "patterns/mirna-target-database/status-and-statistics" >}}) of the tool. [**Citation**]({{< relref "patterns/mirna-target-database/citation" >}}) is essential so that the user correctly references what database was used to produce the results in their paper. Low interpretability of the results is one problem that affects users (Mullany et al., 2015). Thus, it is important that users can easily consult the [**Methods**]({{< relref "patterns/mirna-target-database/methods" >}}) used for target prediction. Additionally, **Contact** can enable users to keep the database [**Status and Statistics**]({{< relref "patterns/mirna-target-database/status-and-statistics" >}}) up to date by submitting suggestions or updates.

## Related patterns

### Contains

- [Status and Statistics]({{< relref "patterns/mirna-target-database/status-and-statistics" >}}) from Bioinformatics IDP.

- [Methods]({{< relref "patterns/mirna-target-database/methods" >}}) from Bioinformatics IDP.

- [Citation]({{< relref "patterns/mirna-target-database/citation" >}}) from Bioinformatics IDP.

- [Contact]({{< relref "patterns/mirna-target-database/contact" >}}) from Bioinformatics IDP.


## Examples

### TarBase

![](tarbase_info.png)
- [**Citation**]({{< relref "patterns/mirna-target-database/citation" >}}) is highlighted on the main page.
- Statistics button on the left links to a detailed [**Status and Statistics**]({{< relref "patterns/mirna-target-database/status-and-statistics" >}}) page.
- Some [**Status and Statistics**]({{< relref "patterns/mirna-target-database/status-and-statistics" >}}) data are displayed on the bottom of the main page.

---
---

### TargetScan

![](target_scan_info.png)

- The main page display information about the [**Methods**]({{< relref "patterns/mirna-target-database/methods" >}}) used to predict miRNA targets.
- [**Citation**]({{< relref "patterns/mirna-target-database/citation" >}}) is easily visible on the bottom of the main page.

---
---

### ENCORI/starBase

![](encori_info.png)

- [**Status and Statistics**]({{< relref "patterns/mirna-target-database/status-and-statistics" >}}) is displayed on the main page.
- [**Citation**]({{< relref "patterns/mirna-target-database/citation" >}}) is located at the bottom.

---
---

### miRecords

![](mirecords_info.png)
 
 - [**Status and Statistics**]({{< relref "patterns/mirna-target-database/status-and-statistics" >}}) is displayed on the left column of the page.
 - The search tab links to a page containing information about the [**Methods**]({{< relref "patterns/mirna-target-database/methods" >}}) and the [**Citation**]({{< relref "patterns/mirna-target-database/citation" >}}).

---
---

### miRDB
 
 ![](mirdb_info.png)

- The menu on the left of the main page links to [**Status and Statistics**]({{< relref "patterns/mirna-target-database/status-and-statistics" >}}), [**Methods**]({{< relref "patterns/mirna-target-database/methods" >}}) (FAQ) and [**Citation**]({{< relref "patterns/mirna-target-database/citation" >}}).
- [**Citation**]({{< relref "patterns/mirna-target-database/citation" >}}) is also available at the bottom of the main page.

## References

>Mullany, Lila E., Roger K. Wolff, and Martha L. Slattery. "Effectiveness and usability of bioinformatics tools to analyze pathways associated with miRNA expression." Cancer informatics 14 (2015): CIN-S32716.