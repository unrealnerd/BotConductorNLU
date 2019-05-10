<!--- Make sure to update this training data file with more training examples from https://forum.rasa.com/t/rasa-starter-pack/704 --> 

## intent:phrase
- Can you tell me a phrase?
- I would like to hear a phrase
- Tell me a phrase
- A phrase please
- Tell me a phrase please
- I would like to hear a phrase
- I would loke to hear a phrase, please
- Can you tell phrases?
- Please tell me a phrase
- I need to hear a phrase
- Share a random phrase
- Share random [2](phrasecount) phrase
- [3](phrasecount) phrase
- [5](phrasecount) random phrase
  

## regex:phrasecount
- [0-9]{1}