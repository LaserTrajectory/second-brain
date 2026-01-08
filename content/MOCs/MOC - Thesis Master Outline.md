---
type: moc
status: Ideation
parent_moc:
  - "[[MOC - Thesis Master Outline]]"
tags:
  - moc
  - organization
created:
  "Sunday 04 Jan '26"
updated:
  "Sunday 04 Jan '26 12:23"
draft: true
---

# MOC - Thesis Master Outline

## Scope & Objective
*What is the goal of this MOC?*

## 🏗️ The Narrative Structure
*Build outlines with Evergreen Notes and Literature Notes

# Methodology
[[MOC - Methodology]]

TABLE status, priority, year
FROM #literature
WHERE contains(informs_moc, [[MOC - Chapter 2 Econometric Methodology]])

## 🖇️ Unlinked Mentions
*Use a Dataview query here later to find notes that belong here but aren't linked yet.*

TABLE status, type, updated
FROM [[]]
WHERE !contains(this.file.outlinks, file.link)
SORT updated DESC