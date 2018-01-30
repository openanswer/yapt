# Introduction to Operators

> A biologist, a physicist, and a mathematician are all eating on the patio of a restaurant. Across the street, they see two people walk into a building, and a few moments later three people walk out.
>
> The biologist says, "Oh, they must have reproduced."
>
> The physicist remarks, "There must have been some type of statistical error."
>
> All are quiet for a long while before the mathematician says, "You know, if one more person walks into that building it will be empty."

We have already come across the assignment operator (` = `) in the [previous section](variables.md), where we used it to assign values to a meaningful name that represents that value:
```python
 > password = 'dolph!ns'              # this is not my password and you should never store passwords in code
 > a_single_space = ' '
 > my_favorite_number = '111'         # again, note the quotes, this is different from 111 (without quotes), more on this in the next section
 > a_slightly_more_secure_password = password + a_single_space + my_favorite_number
 > a_slightly_more_secure_password    # What do you think the output will be?
```
<details>
  <summary>Expand to reveal the output</summary>
  <pre><code class='highlighter-rouge'> # Well, it would be the same as:
 > 'dolph!ns' + ' ' + '111'
=> 'dolp!ns 111'</code></pre>
</details>


| [Previous (Variables)](variables.md) | [Home](index.md) | [Next (Types)](types_intro.md) |
|:-------------------------------------|:----------------:|-------------------------------:|
|                                      |                  |                                |
