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
 - Inverted index by BOW (bag of word) representation for docs
 - One word query responding (It's not a Ranked Retrieval system)
<br><br>
## Phase2-Efficient query responding by heap and champion list
In this phase, we improve IR system accuracy and speed with famous IR techniques.  
The most important steps implemented in this phase:
- tf-idf Vector representation for docs
- Similarity calculation (cosine-sim)
- Index elimination
- Champion list (tf base)
- K-top extraction by max-heap
- Pharase query responding (Ranked Retrieval system) 
<br><br>
## Phase3-Speed up query responding by K-means clustering and KNN
In this phase, we use a larger dataset to deal with time and memory limitations.
### K-means
To have a Ranked Retrieval System like the second phase for query responding  ittakes a long time, for decreasing online computing we have to use clustering techniques. we chose k-means and after several experiments, we choose k = 100 and repeat clustering and updating centroid for 5 iterations.
<br>
### KNN
In this section we implement a categorized search engine with 5 categories 
- "culture" 
- "economy"
- "sports"
- "politics"
- "health"
we use KNN for labeling docs and we check k = 3, 5, and 7 and get the best result by 5
for search in this search engine, you have to enter your query like this.
```
cat:<cat> <query>
ex: cat:sport قهرمانی پرسپولیس
```
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
