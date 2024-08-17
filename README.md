# text-summarizer

Text summarization refers to the technique of shortening long pieces of text. The intention is to create a coherent and fluent summary having only the main points outlined in the document. Automatic text summarization is a common problem in machine learning and natural language processing (NLP).

There are two main approaches to summarize text in NLP:

Extractive summarization This approach selects passages from the source text and then arranges it to form a summary. One way of thinking about this is like a highlighter underlining the important sections. The main idea is that the summarized text is a sub portion of the source text.

Abstractive summarization The abstraction technique entails paraphrasing and shortening parts of the source document. When abstraction is applied for text summarization in deep learning problems, it can overcome the grammar inconsistencies of the extractive method. The abstractive text summarization algorithms create new phrases and sentences that relay the most useful information from the original text — just like humans do. Therefore, abstraction performs better than extraction. However, the text summarization algorithms required to do abstraction are more difficult to develop.

In this project, I have made the use of abstractive summarization with the help of BART model, which inherits from pretrained model on Hugging Face.
