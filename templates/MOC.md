---
type: moc
status: Ideation
parent_moc:
  - "[[MOC - Thesis Master Outline]]"
tags:
  - moc
  - organization
created:
  "{{date}}"
updated:
  "{{date}} {{time}}"
draft: true
---

# {{title}}

## Scope & Objective
*What is the goal of this MOC?*

## 🏗️ The Narrative Structure
*Build outlines with Evergreen Notes and Literature Notes


## 🖇️ Unlinked Mentions
*Use a Dataview query here later to find notes that belong here but aren't linked yet.*

TABLE status, type, updated
FROM [[]]
WHERE !contains(this.file.outlinks, file.link)
SORT updated DESC