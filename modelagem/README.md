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
03_A_64_modelagem.ipynb     | Modelagem 1-dim 64 mfccs
03_A2_64_modelagem.ipynb    | Modelagem 1-dim 64 mfccs com duas classes
03_A_128_modelagem.ipynb    | Modelagem 1-dim 128 mfccs
03_A2_128_modelagem.ipynb   | Modelagem 1-dim 128 mfccs com duas classes
03_B_64_modelagem.ipynb     | Modelagem 2-dim com 64 mfccs
03_B_128_modelagem.ipynb    | Modelagem 2-dim com 128 mfccs
...                         | ...
03_R_64_modelagem.ipynb     | Modelagem 2-dim RNN len variável
03_R_128_modelagem.ipynb    | Modelagem 2-dim RNN len variável
...                         | ...
03_Y_modelagem.ipynb        | Sugestão de modelos especialistas
03_Z_modelagem.ipynb        | Transfer Learning direto
04_optm.ipynb               | Técnicas para otimização
05_comparacao.ipynb         | Análise comparativa entre modelos
06_app.ipynb                | Empacotamento do modelo como software

<br>

# FIXME

# TODO

- modelagem
    - mais refs trabalhos de intensidade
    - mais plots ao longo dos notebooks

# FUTURO
    - https://scikit-learn.org/stable/modules/generated/sklearn.manifold.TSNE.html
    - feature engeneering
    - data augumentation
    - data generation
    - outras arquiteturas
        - rnn direto no sinal
            - batch por grupo com len próxima
    - normalização
