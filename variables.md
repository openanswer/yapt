# Variables

> _"Elementary, my dear Watson." -Sherlock Holmes_

Did you know that Holmes never said that particular phrase in any of the books?
Turns out the quote [was first used by P. G. Wodehouse, in Psmith Journalist, 1915](https://www.phrases.org.uk/meanings/elementary-my-dear-watson.html).
The **`author`** of the **`quote`** turned out to be _`P. G. Wodehouse`_, not _`Holmes`_ nor _`Sir Arthur Conan Doyle`_!

After reading the quote above you probably almost subconsciously created two variables.
A **`quote`** for _`"Elementary, my dear Watson."`_, and an **`author`** for _`Sherlock Holmes`_ or _`Sir Arthur Conan Doyle`_.
You may have then changed the **`author`** to _`Wodehouse`_.
In programming, variables are just that - some information that we give a name to in order to later recall it.

Variables are created by assigning values to a particular name using the assignment operator (`=`):
```python
 > variable = 'value'
 #            ^     ^ quotes define strings (a text data type, more on this later)
 > author = 'Sherlock Holmes'
 > quote = 'Elementary, my dear Watson.'
 > year = 1915
```
Variables can be reassigned:
```python
 > variable = 'a different value'
 > author = 'Wodehouse'
```
Can contain other variables:
```python
 > a = 1
 > b = a
```
And the information stored in the variables can be recalled:
```python
 > a
=> 1
 > b
=> 1
 > variable
=> 'a different value'
 > quote
=> 'Elementary, my dear Watson.'
 > author
=> 'Wodehouse'
 > year
=> 1915
```


| [Previous (Introduction)](intro.md) | [Home](index.md) | [Next (Introducing Types)](types_intro.md) |
|:------------------------------------|:----------------:|-------------------------------------------:|
|                                     |                  |                                            |
