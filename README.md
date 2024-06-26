# A-Smart-QnA-System-for-Chennai-Tourism-using-RoBERTa

To effectively answer Chennai tourism-related questions, we fine-tuned RoBERTa on a curated dataset specifically focused on Chennai. 
This dataset comprised 320 question-answer (Q&A) pairs meticulously divided into a training set of 270 examples and a testing set of 50 examples.
Data scraped is available in the data folder.
Then RoBERTa model was fine-tuned for 20 epochs using the datasets. 
The fine-tuned version is available at :

https://huggingface.co/aditi2212/roberta-finetuned-ChennaiQA-final


Fine-tuning code is available in the fine-tuning folder.


The model's performance was measured on both the training set (270 Q&A pairs) and the testing set (50 Q&A pairs) not seen during training
We employed two key metrics to evaluate answer accuracy: Jaccard similarity and Levenshtein distance. 
RoBERTa was able to answer 282 questions out of 320 questions. The code for testing the model performance , the results, and the final GUI built using tkinter is present in the Inference folder. The project presentation is available in the miscellaneous folder.

The video explanation and demo is available at 

https://youtu.be/rq2BoGUteBM
