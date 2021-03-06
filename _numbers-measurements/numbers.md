---
title: "Numbers"
order: 0
exclude_from_search: true
---

Use digits instead of words for most numbers.

Use a comma between the third and fourth digit from the right, for numbers 10,000 and above.

Use words for ordinals, except for dates.

Use the word million instead of digits for 1 million and above.

{% include guide_example.liquid
  title = "numbers"
  content= "
- 1 to 9 --- not one to nine
- 10 to 9999
- 10,000 to 1 million
- first, second, third
- 100s of them
- 5kg
- 50KB
- 10am
- $2
- 75%
- Section 10
- 19th century
- 1980s
- 25 people went to the launch"
%}

Abbreviate million, billion and trillion in headings, tables and graphics.

{% include guide_example.liquid
  title = "abbreviating large numbers"
  content= "
- 1m
- 2bn
- 3tn
"
%}

Use digits at the beginning of a line, bulleted item or sentence.

{% include guide_example.liquid
  title = "using digits at the start of a line"
  content= "
We are cataloging the collection. 19th century works of art are the focus.
"
%}
