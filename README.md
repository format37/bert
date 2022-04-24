# DeepPavlov & BERT Examples
- paraphraser  
http://docs.deeppavlov.ai/en/master/index.html
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
