---
title: Blank_Example_File
description: Example_description_text_for_blank_example_file.
status: active
display: true
---

# Main_Title_H1

## Section_Heading_H2
Example_description_text_for_blank_example_file

## Section_Heading_H2
Example_description_text_for_blank_example_file

### Sub-Section_Heading_H3
Example_description_text_for_blank_example_file

### Sub-Section_Heading_H3
Example_description_text_for_blank_example_file

## Link Testing:

### Correct: 

- **[with md: /Website/guides/creator_overview.html](/Website/guides/creator_overview.html)**
- <strong><a href="/Website/guides/creator_overview.html">with html: a href=/Website/guides/creator_overview.html</a></strong>

- [also works: ../guides/creator_overview.html](../guides/creator_overview.html)
- [can also use site.url]({{ site.url }}/guides/creator_overview.html)

### wrong: 

- [nope: /guides/creator_overview.html](/guides/creator_overview.html)
- [nope: /guides/creator_overview.md](guides/creator_overview.md)
- [nope: /Website/guides/creator_overview.md](/Website/guides/guides/creator_overview.md)
- [nope: ../guides/creator_overview.md](../guides/creator_overview.md)


- <a href="{{ site.baseurl }}/Website/guides/creator_overview.html">nope: a href= site.baseurl /Website/guides/guides/creator_overview.html</a>
- <a href="{{ site.baseurl | relative_url }}/Website/guides/creator_overview.html">nope: a href= site.baseurl relative_url</a>

## Button Testing

<a href="{{ site.pages[1].url | relative_url }}" class="default_light">Get Involved</a>


---
## End of File
