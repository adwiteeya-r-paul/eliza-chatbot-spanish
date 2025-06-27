# Spanish Chatbot - "ELIZA"
This program is a chatbot inspired by the early natural language processing computer program "ELIZA" developed at MIT.
The chatbot takes inputs from the user in Spanish, uses Regex to categorize the user input into any of the categories mentioned below and returns a corresponding output, also in Spanish. 

### Categories of user input 

  1. Initial greeting, generalizing for any names. Format: Mi nombre es Arp, Me llamo Arp.
  2. State of mind and adverbs, generalizing for any adjectives. Format: Estoy feliz, Yo estoy feliz, Estoy muy feliz, No estoy feliz, No estoy muy feliz, Yo no estoy muy feliz, Estoy un poco triste, Estoy bastante triste, Estoy más o menos triste.
  3. Characteristics of a person. Format: Soy desordenado, Es que yo soy bastante desordenado, Yo soy una persona desordenada, Yo no soy una persona ordenada, Soy una estudiante de Dartmouth.
  4. Descriptions of family. Format: Any input containing words referring to family members.
  5. Handling modal verbs and clitics. Format: Any input containing modal verbs in first person form, clitics like me or te.
  6. Thoughts and hopes. Format: Any input containing pienso, espero etc.
  7. Handling insults. Format: Input containing specific insults.
  8. Controlling for the word "always" Format: Any input containing siempre.
  9. All other statements.


### Files in this repository:

1. Eliza.py contains the program code
2. test-sentences-io contains the sentences used to test the code.

### Relevant links: 

Learn more about ELIZA here: [https://en.wikipedia.org/wiki/ELIZA]

