# LLMs & grammar
This is the repository for bachelor thesis 'Studying Large Language Models' Capabilities of Judging Linguistic Acceptability on Russian Sentences'.

The folder 'annotation' contains two files with annotated examples of explanations and corrections generated by YandexGPT and GigaChat. 

In the folder 'code' files with the code which was used to prompt three models can be found ('saiga.ipynb', 'yagpt.ipynb' and 'gigachat.ipynb'). To  run the notebooks with GigaChat and YandexGpt, one needs to first get API-keys. In addition to it, there are notebooks with the code which was used for measuring the labels and categories predicted ('evaluation.ipynb') and for extracting samples of explanations and corrections to annotate ('sample.ipynb'). To run 'evaluation.ipynb' both output file and file with dataset in the tsv format are needed. For the 'sample.ipynb' input files should be in tsv, too.

Finally, 'thesis.pdf' is the thesis text itself.

All the models' outputs can be found on the Google drive [here](https://drive.google.com/drive/folders/1Ug07nGQvPDVezqsag4MvM3fCX_E-FdZJ)
