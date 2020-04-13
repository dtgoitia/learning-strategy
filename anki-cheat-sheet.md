# Anki cheat sheet

## Key concepts

Deck: group of cards; you can nest decks inside decks.
Card: 1 question + 1 response.
Card type: blueprints for _cards_.
Field:
Note: instance of a _note type_; it contains 1 or more _cards_. Example:
  - Note: English-French
    - Card 1: Q in Frech, A in English.
    - Card 2: Q in English, A in French.
Note type: blueprint for _notes_.
Sibilings: _cards_ under the same _note_ are sibilings.
Collection: your ‘collection’ is all the material stored in Anki – your cards, notes, decks, note types, deck options, and so on.

- Anki considers same _card types_ to be related concepts, and ensures them not to appear too close to each other.
- Use _decks_ if you always want to study some content separately. Use _tag_, _fields_ and _filtered decks_ for content which occasionally needs to be separately.
- Each _note type_ have 1 or more _card types_; when you add a _note_, Anki will create one _card_ for each card type.
- Should: create a separate note type for each broad topic you’re studying.
- When Anki checks for duplicates, it only compares other notes of the same type.

Delete card/note: remove it completely.
Suspend card/note: do now review until manually unsuspended.
Bury card/note: suspend until tomorrow.

- Anki can show new cards from one deck while seeing reviews from another deck, or vice versa; can be disabled.
- When you answer a _card_, Anki _buries_ its _siblings_; can be disabled.


## Doubts

- [x] How to do reviews of specific cards within a deck? can I do that?
  - [Custom study and filtered decks](https://docs.ankiweb.net/#/filtered-decksj)
- [x] Can I freeze a deck? I don't want to study that deck today.
  - _Suspend_ all the cards in a deck.
- [x] Does Anki stop adding new cards if I keep forgetting existing ones?
  - `Deck options` > `New cards/day` tells Anki how many new cards you’d like introduced on each day you open the program. Missed days will not cause the cards to pile up. The limit applies to the current deck and sub-decks.

## External resources

- [Anki. Key Concepts](https://docs.ankiweb.net/#/getting-started?id=key-concepts)
- [Anki. Learning workflow](https://docs.ankiweb.net/#/studying?id=learning)
- [Anki. Using decks appropriately](https://docs.ankiweb.net/#/editing?id=using-decks-appropriately)
- [Anki. I haven’t studied for a while, and now the next due times are too big!](https://docs.ankiweb.net/#/faqs?id=i-havent-studied-for-a-while-and-now-the-next-due-times-are-too-big)
- [Anki. When are new cards added?](https://docs.ankiweb.net/#/deck-options?id=new-cards)
- [Anki. Algorithm](https://docs.ankiweb.net/#/faqs?id=what-spaced-repetition-algorithm-does-anki-use)