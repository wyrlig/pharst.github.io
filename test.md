---
theme: jekyll-theme-minimalist
layout: test
---


This following should display in <strong>bold</strong> and <em>italic</em> text, which means that markdown is interpretating text

This is [a link](http://example.com){:target="_blank"} that opens in a new window.

{{ "example" | open_in_new_window: "http://example.com" }}


This following tag &#39; <strong><a href="https://www.soverin.net">SoverLink</a>{:target=&quot;_tab&quot;}</strong> &#39; should open https://www.soverin.net in tabname &quot;_tab2&quot;.
<br>If not, the MarkDown translation or attribute interpretation went wrong.


This following should display a Markdown header and single line for 3 columns:
| Left Syntax     | Center Description | Right comment |
|:--------------------|:------------------------:|-------------------:| 
| Line1      | Col2 | text3 |
<br> If not, the MarkDown translation or interpretation went wrong.