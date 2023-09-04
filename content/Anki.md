+++
title = Making anki cards for A Dictionary of Japanese Grammar
menu = "main"
+++

# Making anki cards for *A Dictionary of Japanese Grammar*

---

{{< toc >}}

In November 2022, I finished studying two anki decks that I made/modified based on the content in the [Dictionaries of Japanese Grammar book series](https://www.amazon.com/Dictionary-Japanese-Learning-Language-Intermediate/dp/B01M3T4NJP), and posted the details to reddit.

Since I originally posted the decks to a file host that reddit marks as spam, it was eventually removed. [Here's the original body]({{< ref "/redditpost.md" >}}) of the post, which I've reorganized a bit in the text below.


**You can download the decks here:** 
* [Grammar](https://ankiweb.net/shared/info/843402109)
* [Vocab](https://ankiweb.net/shared/info/261818505)

## Methodology

There are over 5,000 sentences across the three books in the *A Dictionary of Japanese Grammar* series. There is an anki deck on itazuraneko which provides a card for each grammar point and sticks all of the sentences for each grammar point into it. Later, I found an anki deck in r/Japanese (which seems to have since been deleted) that was a modified version of the one on itazuraneko. This deck made a card for each sentence individually

Taking this modified deck, I:
* used AwesomeTTS with a paid API subscription to add natural sounding Japanese voices to each sentence
* created a separate deck for all of the unknown vocabulary, with audio (some 4,000 words; this is useful for those who have a roughly JLPT3-level of understanding, so you may need to make your own cards if you starting with less Japanese knowledge)
* adjusted card stying by adding a dark mode and mobile friendly sizing
* added furigana to some words (and most names) in the sentence deck. This I did more for personal use because I hadn't originally planned to shared this deck so it is incomplete and not always reliable, but the functionality is there if you want it.

## Why

...Because, lol. Well, I really wanted a simple, low-effort way to study and remember grammar before I got to a place where I felt more comfortable reading (that ended up being not low effort at all in the end, but it will be for you). Things weren’t sticking with workbooks, and I wasn’t finding them helpful. Youtube videos for grammar points were helpful, but the repetition wasn’t there. So anki it was

## How to use

How I used these might not end up being what you do, and that's totally fine. But to give you some idea of what you might do:

Roughly, I focused on one book at a time, starting at the beginner level. I gave myself a certain limit of sentences to study each day, like ten, and just went through them. I would read the sentence, and if I understood it (even if I got some vocab readings wrong) I would pass it. If I struggled to understand, I would mark it as hard or even completely forgotten. Then I would add words I didn’t know from each sentence to the vocabulary deck and study those the next day. 

Sometimes the vocabulary deck making took quite awhile, because I wasn’t sure of the right reading, or I would later realize what I thought was a word was being used differently as part of a phrase.

For the voices, I mostly added them in batch, but went back and re-recorded those with incorrect readings, or where the grammar point emphasized something was male or female speech. I'm still fixing these, so you may find errors in readings here--**please let me know if you find an error** and I'll update the deck.

## Card specifics

Here are what the cards look like:

### Sentence Cards

**Sentence card front**

![Sentence Card Front](/ankiSentenceDeckFront.png 'Sentence Card Front')

**Sentence card back**

![Sentence Card Back](/ankiSentenceDeckBack.png 'Sentence Card Back')

**Sentence deck night mode**

![Sentence deck night mode](/ankiSentenceDeckNightMode.png 'Sentence deck night mode')

Includes a little footnote to tell you where in the book and in which book you can find the sentence. Some sentences I have added a little additional note in a card field called "extra notes" that you can put what you want in.

Some words in this deck (particularly names) have ruby-enabled furigana; just hover with a mouse or tap. You can add furigana, too. The deck is compatible with the [Japanese Furigana](https://ankiweb.net/shared/info/678316993) and the [Japanese Support](https://ankiweb.net/shared/info/3918629684) addons.

**Sentence deck fields**

![Sentence Deck Fields](/sentenceDeckFields.png 'Sentence Deck Fields')

The *Japanese* field was originally there to make the deck compatible with the Japanese add on, but it was unnecessary. Some, but not all, of the sentences I fixed typos for have the typos fixed only in the *Reading* field, which is the field that will display on your card. The *Japanese* field is not displayed.

### Vocabulary Cards

**Vocab Front**

![Vocab Deck Front](/ankiVocabularyDeckFront.png 'Vocab Deck Front')

**Vocab Back**

![Vocab Back Expanded](/ankiVocabularyDeckExpanded.png 'Vocab Back Expanded')

The plus and minus buttons, and the magnifying glass at the bottom are tapable/clickable to show or hide collapsible fields. Also, some kanji have alternative writings or multiple readings. I tried to add this in where I can.

Warning in advance, not all of the cards are so well formatted on the back with the point of speech (sorry) due to laziness. But you can do this if you'd like. The first bullet point in an unordered list will make anything in it styled the way the *noun* text is in the example

**Vocab with image**

![Vocab with image](/ankiVocabularyDeckWithImageDisplay.png 'Vocab with image')

**Vocab night mode**

![Vocab Night Mode](/ankiVocabularyDeckNightMode.png 'Vocab Night Mode')

The notes and image fields will only display if you put something inside.

**Vocab deck fields**

![Vocab Deck Fields](/vocabularyDeckFields.png 'Vocab Deck Fields')

If you use a sentence not from the grammar deck, you can put a link to where you find it in the sentence source link field (which otherwise will not show up on your card)

In this example, in the notes field I put a translation of the first sentence. I found this sentence and its translation in a dictionary, so there's no link.


## Caveats

* I wasn't planning on sharing this, so the vocabulary deck has about ten or fifteen words that aren't in the books; I didn't mark them, so I don't know which ones they are.
* Sometimes the ADoJG's English translations are needlessly over localized. There are about ten sentences I edited the translation of to be more literal, but they are unmarked. I don't remember which these were
* The original itazuraneko grammar deck must have been ocr'd, since there were quite a few typos. I fixed as many as I could, but I don't think I found them all, so if you find a mistake, let me know. 
* Not all grammar points are covered in the book series, which is annoying, but not a bad thing. It definitely has the bulk of what you need to know, and it does cover quite a bit. But if you want something insanely comprehensive down to the smallest detail, you would need to make an anki deck out of everything on [imabi](https://imabi.org), or the [日本語文型辞典](https://www.amazon.com/Handbook-Japanese-Patterns-Teachers-Learners/dp/4874246788/ref=sr_1_4?crid=7YFREHY6CVAJ&keywords=japanese+learners+grammar&qid=1693689852&sprefix=japanese+learners+grammar%2Caps%2C117&sr=8-4).
* If you make any edits to the code, I'm sorry in advance. I am not a developer by any means, and the code is a huge mess. I've been meaning to clean it up and I just haven't. Learning html and css is another hobby I pursued in the creation of these cards, and it is probably very apparent when looking at the code.


## Credits

- [/u/TrainOfPotatoes](https://www.reddit.com/u/TrainOfPotatoes/), who seems to be the original author of the theme for the grammar deck I found. My version has been changed quite a bit, though
- [ninja33 on Github](https://github.com/ninja33/anki-templates), who made the base version of the theme for the vocabulary deck I ended up changing
- [abdo](https://forums.ankiweb.net/u/abdo/summary) on the anki forums who helped me with my Javascript
- The [Migaku Dictionary](https://ankiweb.net/shared/info/1655992655) developers
- The redditor who uploaded the edited itazuraneko grammar deck. I can't find your post anywhere, so if you are out there, thank you!
- The developers of [AwesomeTTS](https://ankiweb.net/shared/info/1436550454) 
- The authors of the *[A Dictionary of Japanese Grammar](https://www.amazon.com/Dictionary-Japanese-Learning-Language-Intermediate/dp/B01M3T4NJP)* series

---
