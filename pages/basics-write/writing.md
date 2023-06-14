---
title: Writing
layout: content
# image: hand-paid-cans-36464-pxh2.jpg
---

Jacob:

I added every CSV file except for system_paths into source control.  words_to_replace and additional_words are super duper useful for dealing with work and other technical stuff; these are files that you want to start messing with immediately.  Some thoughts on words_to_replace and additional_words:

Stuff in additional_words will be top priority in recognition.  This can be great, but also you might not like it heavily preferring the added words over similar words that you say.
Stuff in additional_words considered a single word even it is multiple words.  An entry of "some new word, stuff to become new word" will let you do command "word stuff to become new word" to type "some new word".
You can terminate say/formatter commands without pausing by using the word "over".  "say string over space camel variable name over space say more words" types "string variableName more words".