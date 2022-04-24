# BERT Examples
http://docs.deeppavlov.ai/en/master/index.html
- paraphraser  
This library model solves the tasks of ranking and paraphrase identification based on semantic similarity which is trained with siamese neural networks. The trained network can retrieve the response closest semantically to a given context from some database or answer whether two sentences are paraphrases or not.  
- text qa  
The Question Answering component answers a question based on a given context (e.g, a paragraph of text), where the answer to the question is a segment of the context. This component allows you to answer questions based on your documentation.   
### installation
```
conda create -n bert python=3.7 ipython
conda activate bert
pip install -r requirements.txt
# python -m deeppavlov install squad_bert
# python -m deeppavlov install squad_torch_bert
source activate bert
conda install pip
conda install ipykernel
source activate bert
python -m ipykernel install --user --name bert --display-name "Python: BERT"
jupyter notebook
```
### paraphrase detection
```
# python -m deeppavlov install paraphrase_ident_paraphraser
```
