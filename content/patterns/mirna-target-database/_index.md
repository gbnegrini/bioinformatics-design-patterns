---
# Course title, summary, and position.
title: Interaction Design Patterns for miRNA target databases
linktitle: miRNA target databases
summary: "A pattern language to communicate the main solutions to common usability problems in microRNA database interfaces"

# Page metadata.
date: "2022-01-04T00:00:00Z"
toc: false  # Show table of contents? true/false
type: book  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
weight: 10
---

## Pattern language overview

```mermaid
erDiagram
    FLEXIBLE-DATA-INPUT ||--|| DATA-FILTER : contains
    FLEXIBLE-DATA-INPUT ||..|| INPUT-PROMPT : improves
    DATA-PRESENTATION ||--|| DATA-FILTER : contains
    DATA-PRESENTATION ||--|{ DETAILS : contains
    DATA-PRESENTATION ||..|{ SORT-BY-COLUMN : contains
    DATA-PRESENTATION ||..|| EXPORT : contains
    DATA-PRESENTATION ||--|| METHODS : used-with
    INFORMATIONAL-ELEMENTS ||--|| STATUS-AND-STATISTICS : contains
    INFORMATIONAL-ELEMENTS ||--|| METHODS : contains
    INFORMATIONAL-ELEMENTS ||--|{ CITATION : contains
    STATUS-AND-STATISTICS ||--|| METHODS : used-with
    STATUS-AND-STATISTICS ||--|| CITATION : used-with
    METHODS ||..|| FAQ : similar
    DATA-FILTER ||..|| LIVE-FILTER : similar
    DATA-FILTER ||..|| FILTERING : similar
```
Dashed lines indicate a design pattern from an external source.

---

## List of design patterns

{{< list_children >}}
