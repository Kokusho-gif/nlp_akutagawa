# What this does
This application could generate sentences which seem to be made by Akutagawa(Great writer).

Relevant KEYWORD: RNN, LSTM, GRU


This repository consists of the structure shown below.

```mermaid
graph TD;
    nlp_akutagawa-->README.md;
    nlp_akutagawa-->akutagawa;
    akutagawa-->corpus;
    akutagawa-->akutagawa_nlp.ipynb;
    corpus-->__.txt;
```

## akutagawa_nlp.ipynb
Main component. All of prreprocessing, training code are here(No validation, Testing).

## corpus/__.txt
Raw data used for training and testing.
     
