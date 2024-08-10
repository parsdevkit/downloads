---
title: Downloads
hide:
  - navigation
  - toc
---


<!-- --8<-- "contents/en/pars/index.md:8" -->


First let's declare a text variable {% set my_variable = "String printed by the template" %}. 
And then print it in bold and red:  **{{my_variable}}**{style="color: red"} .  

we can also create variables of other types, for example:

- lists {% set my_list = [1, 2, 3, 4, 5] %}
- dictionaries {% set my_dict = {"one": 1, "two": 2, "three": 3} %}

Now we print my_list = {{my_list}} and dict = {{my_dict}}

We can get separate elements of the dicts and lists. For example first element of the list is **{{ my_list[0] }}**, 
and element "two" from the dict is **{{ my_dict["two"] }}**