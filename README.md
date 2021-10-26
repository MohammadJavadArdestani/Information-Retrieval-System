# Information Retrieval System  

## Phase1-Simple inverted index

The most important steps implemented in this phase:
-  Persian Tokenizer
-  Persian Normalization functions:
    - remove_punctuation_marks()  
    - remove_postfix()
    - remove_prefix()
    - verb_steaming()
    - char_digit_unification()
    - morakab_unification()
    - remove_arabic_notations()
 - Find and remove stop-words
 - Inverted index by BOW(bag of word) representation for docs
 - One word query responding (It's not a Ranked Retrieval system)
<br><br>
## Phase2-Efficient query responding by heap and champion list
In this phase we imporve IR system accuracy and speed by famous IR techniques 
The most important steps implemented in this phase:
- tf-idf Vector representation fro docs.
- Similarity calculation (cosin-sim)
- Index elimination
- Champion list (tf base)
- K-top extraction by max-heap  
<br><br>
## Phase3-Speed up query responding by K-means clustering and KNN
<br><br>
## License
Distributed under the MIT License. See LICENSE for more information.
<br><br>
## Contact
Mohammad Javad Ardestani: mjavad.ardestani00@gmail.com <br>
Project Link: https://github.com/MohammadJavadArdestani/Information-Retrieval-System
<br><br>
## Acknowledgments
- [NLP Stanford](https://nlp.stanford.edu/IR-book/html/htmledition/contents-1.html)
- [Pickle](https://docs.python.org/3/library/pickle.html)
