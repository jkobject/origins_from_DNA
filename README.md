# PCA for Infering Genetic Ancestry:

Coded by Jérémie KALFON in Python2 + vcftools for the BroadInstitute

## Instalation

you should have python2 installed and Anaconda

you can import the repo with git and the git command

```bash
git clone [url] 
cd PCA-Ancestry
pip install -r requirements.txt
```

now you can launch a jupyter notebook or python
and execute the commands

#### other requirements :
python 2.7
conda
jupyter notebook
mawk
cut
cat
vcftools


## TODO

- try KPCA <<<
- do CV <
- do other accuracy tests <<
- do the simple visualisation <
- add tsne visualisation <
- add requirements <
- add a cmd line function <
- add another clustering method (maybe using autosklearn, without PCA.) <<<<<
- make the code compatible python3 with `future`
- use specifically the SNPs of Zhou et al

## Problems and ideas

We could try to look for other feature selection method as PCA is often not recommended for classification problems
- ACO 
- Dictionnary learning with GAs
- Conv Neural Nets if enough training data

We could use Naive Bayes to guess missing values



Jérémie KALFON for BroadInstitute

jkobject@gmail.com

jkobject.com
