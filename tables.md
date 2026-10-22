## Tables

Markdown tables work perfectly well, and if you already have content with tables in it, those can stay unchanged.

However, if you have new tables to add, or are struggling maintaining complex tables in your documentation, then you might like to try list tables.
List tables are what they sound like: content that is written as a list, but displayed as a table.

{% admonition type="info" name="View source" %}
Read the raw markdown as well as the preview of this page to learn how to mark up text and see how it is displayed.
{% /admonition %}

For example, take this Markdown table containing some geographical and culinary information:

| Country         | Capital       | Favorite Food     |
|-----------------|---------------|-------------------|
| Japan           | Tokyo         | Sushi             |
| Italy           | Rome          | Pizza             |
| Brazil          | Brasília      | Feijoada          |
| South Africa    | Pretoria      | Bobotie           |
| Thailand        | Bangkok       | Pad Thai          |


As a Markdoc table, the result looks the same, but the syntax doesn't require drawing lines with text:

{% table %}

  - Country
  - Capital
  - Favorite Food
---
  - Japan
  - Tokyo
  - Sushi
---
  - Italy
  - Rome
  - Pizza
---
  - Brazil
  - Brasília
  - Feijoada
---
  - South Africa
  - Pretoria
  - Bobotie
---
  - Thailand
  - Bangkok
  - Pad Thai


{% /table %}

Use these tables to more easily handle and maintain content in your projects.
