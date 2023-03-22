Diretório para abrigar [notebooks](notebooks/): Arquivos de código, evidências e resultados e outros.

<br>

Dataset | URL
------- | ---
VERBO   | [VERBO: voice emotion recognition database in portuguese language](https://github.com/jrtorresneto/VERBO-emotional-speech-dataset)
VIVAE   | ["The Variably Intense Vocalizations of Affect and Emotion Corpus (VIVAE) consists of a set of human non-speech emotion vocalizations"](https://zenodo.org/record/4066235#.Y08sYiVv9hE)

<br>

Notebook                    | Descrição
--------------------------- | ---------
00_prep.ipynb               | Preparação
01_eda.ipynb                | Análise dos dados
02_features.ipynb           | Extração de características 
03_A_modelagem.ipynb        | Modelagem 1-dimensional
03_B_64_modelagem.ipynb     | Modelagem 2-dimensional com 64 mfccs
03_B_128_modelagem.ipynb    | Modelagem 2-dimensional com 128 mfccs
...                         | ...
03_Z_modelagem.ipynb        | Transfer Learning direto
04_optm.ipynb               | Técnicas para otimização
05_comparacao.ipynb         | Análise comparativa entre modelos
06_app.ipynb                | Empacotamento do modelo como software

<br>

# TODO & FIXME

- modelagem
    - - mais refs trabalhos de intensidade
- trabalhos futuros:
    - feature engeneering
    - data augumentation
    - data generation
    - outras arquiteturas
    - normalização
