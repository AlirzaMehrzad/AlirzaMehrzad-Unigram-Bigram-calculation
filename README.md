# Unigram-Bigram-calculation

The provided codes, implements Unigram and Bigram concepts. In Natural Language Processing (NLP), unigram and bigram probabilities are statistical measures used to determine the likelihood of a sequence of words in a language model.

---

Unigram Probability

A unigram considers each word in isolation and calculates its probability as if it were independent of any other word. Unigram models assume no dependence between words, which limits their accuracy for modeling language.

The probability of a word wiwi​ in the unigram model is:
P(wi)=Count(wi) / Total number of words in the corpus

---

Bigram Probability

A bigram considers the probability of a word given the previous word, capturing some context. The conditional probability is calculated as:
P(wi∣wi−1)=Count(wi−1,wi) / Count(wi−1)

Bigram models capture context by considering word pairs, making them more accurate than unigram models for many applications, though still limited by their lack of longer-range dependencies.
