---
type: literature
citekey: {{citekey}}
title: "{{title}}"
authors: [{{authors}}]
year: {{date | format("YYYY")}}
publisher: "{{publisher}}"
doi: "{{DOI}}"
zotero_link: "{{zoteroSelectLink}}"
url: "{{url}}"
status: Unread
priority: Medium
created: {{date | format("YYYY-MM-DD")}}
informs_moc: ["[[MOC - ]]"]
tags:
  - literature
  - status/unread
  - topic/{{itemType}}
draft: true
---

# 📑 {{title}}

> [!abstract] Abstract
> {{abstractNote}}

## ❓ Research Question & Goals
*What problem is this paper trying to solve?*

## 📝 Key Findings & Methodology
- **Method:** - **Sample/Data:** - **Results:** ## 💡 My Relevance & Synthesis
**How does this connect to my thesis?**
- 

## 📓 Notes & Annotations
{% for annotation in annotations -%}
{%- if annotation.annotatedText -%}
> {{annotation.annotatedText}} [p. {{annotation.pageLabel}}]({{annotation.desktopURI}})
{%- endif %}
{%- if annotation.comment %}
- **My Note:** {{annotation.comment}}
{% endif %}
{% endfor %}