# Hate Speech Detection 
![alt text](https://th.bing.com/th/id/OIP.xIV8sscrJ6ZFr6WTm1dRawHaEK?pid=ImgDet&rs=1) <br/>
### Conducted By Zachary Biernat and Rahul Kumar under the supervision of Dr. Kamruzzaman Sarker at the University of Hartford

## WARNING

Our code is undergoing a transformation from TensorFlow to PyTorch Lightning in order to support further development and research into the transformer architecture and adding knowledge graph data. Additionally, we will not proceed with using the ERNIE model. We are working our best to re-organize our files and advance our results so stay tuned for the final result, thanks!

## What is Hate Speech Detection?

Hate Speech is speech used to threaten or defame a character on the basis of ethnicity, religion, sexual orientation, or similar grounds. In this project, we aim to recreate the results of a previous paper and advance the performance of classifying hate speech from tweets by comparing various embeddings and architecture results as well as fine-tuning the transformer models. Future work for this project includes creating a pipeline to classify hate speech from social media tweets. 

## Data

The data is from the 2019hateval dataset which can be found using this link: https://datacloud.di.unito.it/index.php/s/eMZdFYq6yRP3zeL
The dataset composed of 13k individual sentences with a hate speech label that were split into a train/val/test split of 70/5/25. 

## Models
We used the following architectures and embeddings:
<br/>GLoVe<br/>FastText<br/>BERT<br/>

Each model has an adjacent model that has also been trained on the original dataset as well as the knowledge graph extractions from DBPedia. These models are distinguished from the other models with the "graph" extension in the title. 

## Papers
**Dataset Paper:** https://www.aclweb.org/anthology/S19-2007/ <br/>
**Original Overview Paper:** https://dl.acm.org/doi/pdf/10.1145/3430984.3431072 <br/>
**BERT paper:** https://aclanthology.org/N19-1423/ <br/>
**GLoVe paper:** https://aclanthology.org/D14-1162.pdf <br/>
**FastText paper:** https://aclanthology.org/Q17-1010/ <br/>
**Hateval Paper:** https://www.aclweb.org/anthology/S19-2007/ <br/>
