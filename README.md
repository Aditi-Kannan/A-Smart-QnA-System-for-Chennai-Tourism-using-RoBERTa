# A-Smart-QnA-System-for-Chennai-Tourism-using-RoBERTa

To effectively answer Chennai tourism-related questions, we fine-tuned RoBERTa on a curated dataset specifically focused on Chennai. 
This dataset comprised 320 question-answer (Q&A) pairs meticulously divided into a training set of 270 examples and a testing set of 50 examples.
Data scraped is available in the data folder.
Then RoBERTa model was fine-tuned for 20 epochs using the datasets. Fine-tuning code is available in the fine-tuning folder
The model's performance was measured on both the training set (270 Q&A pairs) and the testing set (50 Q&A pairs) not seen during training
We employed two key metrics to evaluate answer accuracy: Jaccard similarity and Levenshtein distance. 
RoBERTa was able to answer 282 questions out of 320 questions. The testing code and csv file is present in the testing folder.
The project report and presentations are available in the miscellaneous folder.
