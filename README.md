# Spellchecker / Autocorrect

A python implementation of [Peter Norvig's basic spellcheck program](https://norvig.com/spell-correct.html).

Used a plain text file of War and Peace from [Project Gutenberg](https://www.gutenberg.org/help/new_website.html) as the 'training' set. Should probably use a larger corpus, as 'hello' doesn't appear even once in the entire book(!?), and hence, is not able to predict a mispelling of it.

Corrects the given mispelled word and gives suggestions upto a Minimum Edit Distance of 2 letters away.

