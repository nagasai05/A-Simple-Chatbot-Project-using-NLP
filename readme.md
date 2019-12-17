## A SIMPLE CHATBOT PROJECT

This project is made on the excel sheet of context and response . This project is done by the Natural Language Processing Concept.

The whole process of this model is given below

> Reading the excel file
>
> Then Context is normalized, first text will be converted to lower case, then regular expressions is applied to remove all other special characters other than a-z, 0-9.
>
> After regex application, Lemmatization is applied on the tokenized words considering the Parts of speech tags
>
> After Lemmatization, text is normalized
>
> Context should be converted into vector format by using TF_IDF vectorization
>
> After vectorization, If we input an text to get response the given text is normalized like above process and converted to vector .
>
> After all the above process cross validation is done for the output to get response
>
> This process is done by
>
> 1. Pairwise distances of tfidf values of input taken and context is measured, cosine similarity of both is found
> 2. For the values which meet requirements of threshold values, the response is given.
>
> 