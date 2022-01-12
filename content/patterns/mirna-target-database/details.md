---
type: book

title: Details
summary: "Users need to explore the relationship between a miRNA and a target gene in-depth."

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

date: "2022-01-06T00:00:00Z"

weight: 21

tags:
  - miRNA

categories:
  - miRNA

authors:
  - admin
---

## Overview

![](details.png)

## Problem

Users need to explore the relationship between a miRNA and a target gene in-depth.

## Context

The details of the miRNA-target relationship are too extensive to appear directly in the [**Data Presentation**]({{< relref "patterns/mirna-target-database/data-presentation" >}}) table. The user's knowledge discovery process may depend on understanding the details of the miRNA-target binding.

## Solution

Dedicate a column in the [**Data Presentation**]({{< relref "patterns/mirna-target-database/data-presentation" >}}) table to reference a page dedicated to the [**Details**]({{< relref "patterns/mirna-target-database/details" >}}) of the miRNA-target pair. This information typically includes the miRNA seed sequence and the result of aligning the miRNA and target sequences. A button, link, or dropdown area should be used to make the details available when needed, thus avoiding information overload in the main interface.

## Rationale

Some users require more information beyond listing target miRNA pairs presented by the search tool. The [**Details**]({{< relref "patterns/mirna-target-database/details" >}}) of the seed sequence and the pairing region can guide users' experimental studies.

## Related patterns

### Is contained

- [Data Presentation]({{< relref "patterns/mirna-target-database/data-presentation" >}}) from Bioinformatics IDP.


## Examples

### miRDB

![](mirdb_details.png)

- [**Details**]({{< relref "patterns/mirna-target-database/details" >}}) link to a new page, avoiding clutter in the table.

![](mirdb_details2.png)
- [**Details**]({{< relref "patterns/mirna-target-database/details" >}}) page shows information about seed and sequence.

---

### miRecords
 
![](mirecords_details.png)

- [**Details**]({{< relref "patterns/mirna-target-database/details" >}}) link to a new page, avoiding clutter in the table.

![](mirecords_details2.png)

- [**Details**]({{< relref "patterns/mirna-target-database/details" >}}) page shows information about seed, sequence, and target validation.

---

### TarBase

![](tarbase_details.png)

- [**Details**]({{< relref "patterns/mirna-target-database/details" >}}) about target validation are exhibited in a dropdown area.

---

### DIANA micro-T

![](diana_microt_details.png)
 
- [**Details**]({{< relref "patterns/mirna-target-database/details" >}}) about miRNA-target binding are exhibited in a dropdown area.

