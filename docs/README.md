# Assessment Component Library

With Assessment, the goal is to make it easier for you to include
opportunities for your users (or yourself) to perform checks of understanding.
These can also be helpful for you to create key takeaways from pieces
of work you write about or have video content on.

## Why Have An Assessment?

In pedagogy, or the study/practce of teaching, the space has seen time-and-time
again that in order to measure learning, there has to be an
opportunity for assessment. The purpose of this library is to make it
easier to implement some of the common tools that can support learners
and educators.

## Development Goals

Here is a list of particular components that come to mind that will be
useful to have right out of the gate:

1. Flashcards
  - Definition: A set of cards that have a front and back. Typically,
  should start with the front side shown and then the reader should
  determine the back's information. After finishing one card, it should
  be set aside and then move to the next card till through the entire deck.
2. Quiz
  - Definition: a test of knowledge. These can come in more than a single
  format, sometimes this would be a singular question or multiple. The
  question format can be a single choice option, mutliple choice, or
  fill-in-the-blank.

In any tool used, there must be a way to reset the assessment to the beginning.

Since this is a library we will need to make sure we organize the project
in a way that supports being added as a dependency and should prioritize
being a small footprint.

### Expected Tech Stack

At the start of this project, development will only include: React,
XState, and emotion. Periodic evaluations should include reassessing if
Preact would produce a similar usage as opposed to consuming React.