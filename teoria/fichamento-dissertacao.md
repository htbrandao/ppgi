# Fichamento @ dissertação

1. [Speech Emotion Recognition using Supervised Deep Recurrent System for Mental Health Monitoring](https://arxiv.org/abs/2208.12812) ++

"Mental health is one of the crucial health aspects that must be monitored and treated for better physical health and a safer community and social life [1]."

"According to the World Health Organization (WHO), during the first year of the COVID-19
pandemic, depression and anxiety disorders have increased by 25% globally, especially among young people and women. Due to late or unreceived mental care, the number of related
suicide has increased as well. The number of suicides has exceeded 700,000, meaning one person every 40 seconds dies by suicidal action related to a mental disorder [3]."

"Speech is the primary form of communication and emotional expression [5]. From childhood, even before being able to speak correct words, children express their emotions in their ununderstandable talks, such as their happiness and confusion. Juvenile, adults, and elderly individuals also express their emotions in their speech. All individuals express common emotions such as happy, sad, angry, happy, worry, fear, and neutral in their speech. However, different spoken languages produce differences in how these emotions are expressed in the speech tone and voice [6], [7]."

"There are several mental disorders that can be identified from individual’s emotion changes [9], [10] such as depression disorder [11], [12], stress disorder [13], [14], and anxiety
(worry/fear) disorders [15], [16]. Early diagnostic of mental disorders allows the individual to recieve the correct treatment and prevent sever illensses and even protect fom suicidal action [17], [18]."

"Intelligent Virtual Personal Assistants (IVA) [19], [20] is a software agent that can perform services for an individual based on processing users’ questions or commands via text
or voice, depending on the IVA design and purpose. Several studies address the effect of the IVA devices on individuals’ social life [24], marketing [25], and social communication [26]. However, there are few studies on  the user behavior while using intelligent virtual personal assistant devices to improve the user experience. Yang et al. [27] attempted to understand how to improve the IVA user experience by investigating the relationship between perceived enjoyment, perceived usefulness, and productrelated characteristics using a user survey. Coskun et al. also used questionnaire data to address the factors affecting IVA user experience [28]"

"Speech emotion recognition is one of the complex problems to solve as the emotional expression is tightly reliant on the spoken language, dialect, accent, and individuals’ cultural background. In addition, the audio signal itself preserves the spatial and temporal features of the speech. There have been several attempts to solve the speech emotion recognition problem. The main two scenario approaches: 
    - Scenario I: designing a model that used speech signal datasets after performing data preprocessing and feature extraction.
    - Scenario II: designing a model that converts the speech signal to images (spectrograms) and then performing data preprocessing and feature extraction to fit the data to image-based models.
Wani et al. [30] and Lotfidereshgi et al. [31] are examples of using the scenario II methodology to address the speech emotion recognition. The significant drawbacks of scenario
II are that the data is processed without any consideration of temporal features in the speech signal, which significantly limits the ability of such models to recognize different emotions from the speech correctly. In addition, the data transformation and feature extraction require additional implementation costs from both hardware and software aspects. For the scenario I, Zhang et al. [32], Bhargava et al. [33], Krishnan et al. [34], and Venkataramanan et al. [29] proposed different machine learning and deep learning approaches to solve the speech emotion recognition under the scenario I approach. This approach requires less data transformation and feature extractions compared to the scenario II approaches.  However, these models were not considering the temporal information within the audio signal within their approaches"

"This paper proposed a simple design hybrid model of the gated recurrent neural networks (GRU) with a 1D convolution neural network (1D-CNN) support."

"Toronto emotional speech set (TESS) [49]"

![](img/1.jpg)

"The model can be applied within an intelligent virtual personal assistant to improve the user experience while combining the user request and emotion to provide the appropriate service"

"Personal emotion is one of the most significant indicators of mental health normality and issues."

"The significance of the proposed model is that it does not require any additional data preprocessing due to the 1DCNN that behaves to extract the features from the speech signal."

___
2. [Depression Recognition using Remote Photoplethysmography from Facial Videos](https://arxiv.org/abs/2206.04399)

> n/a


___
3. [Accurate Emotion Strength Assessment for Seen and Unseen Speech Based on Data-Driven Deep Learning](https://arxiv.org/abs/2206.07229) -> [ISCA](https://www.isca-speech.org/archive/pdfs/interspeech_2022/liu22i_interspeech.pdf) ++


"Accurate emotion classification of speech and assessment of its strength are essential to profile human behaviors, which has many potential applications, such as human-robot interface,
human-machine dialogue, and social media. In recent years, there is an increasing interest in emotion control in expressive speech synthesis, such as emotional text-to-speech, emotional voice conversion, where accurate control of emotional strength in speech becomes critically important."

"The simplest emotion strength control method is to linearly scale the emotion representation vector [1]. The effect of such a linear scale is hardly interpretable. To obtain a meaningful
strength descriptor, some followed the idea of “relative attributes” [2–4] and quantify the emotion strength by learning from the <neutral, emotional> speech pairs. Support-VectorMachine (SVM) based attribute ranking [4] learns the difference between two samples that are significantly different in a particular attribute, that has been widely studied in computer vision [5, 6]."

"In speech processing, Zhu et al. [2] proposed to learn an emotion attribute ranking function R(·) from the <neutral, emotional> paired speech features. or of the emotion strength of one specific emotional speech. Lei et al. [3] further extended the utterance level emotion attribute ranking function to phoneme level and obtain a fine-grained ranking function. We note that a trained ranking function R(·) on specific data is not easily generalized to new domains. In other words, R(·) is not able to calculate an accurate or appropriate strength score for unseen or out-of-domain speech. To extend to a new data, we need to retrain a new ranking function on the <neutral, emotional> paired samples from the new data. Furthermore, the learning of ranking functions for new data requires parallel samples. All these limit the scope of applications. Recently, it was shown that deep learning has the ability to learn a mapping function effectively [7,8]. The neural solution learns complex non-linear mapping relationships, and exhibits good generalization ability with the support of a large number of model parameters [9]. Most importantly, the datadriven training strategy appears to be more powerful and have the potential to achieve good performance for out-of-domain data [10]."

"StrengthNet is a multi-task framework that includes a convolutional neural network (CNN) based acoustic encoder, a bidirectional long short-term memory (BiLSTM) based strength predictor and an auxiliary BiLSTM based emotion predictor.
    1) We propose a novel data-driven deep learning based speech emotion strength assessment model, i.e., StrengthNet;
    2) We show that the predicted emotion strength of seen and unseen speech is highly correlated with the ground truth; To our best knowledge, this is the first deep learning model for accurate emotion strength assessment for seen and unseen speech."

"The strategy of stacking more convolutional layers to expand the receptive field of a CNN
has been widely used to model time series data and yield satisfactory performance [7]. The strength predictor then reads the high-level feature representation to predict the emotion strength. Recent studies have confirmed the effectiveness of combining CNN and BiLSTM for classification [7], and recognition [11] tasks"

"As shown in Fig. 2, to improve the model generalization, we employ a domain fusion strategy [12, 13], which mix multiple emotional speech datasets from various domains to train our
StrengthNet."

"We use the ESD dataset [15] to validate the performance of StrengthNet in terms of strength prediction. The English corpus with a total of nearly 13 hours of speech is used in our
experiments. In addition, we use two additional English SER datasets: the Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) [16] and the Surrey AudioVisual Expressed Emotion (SAVEE) database [17]. The emotional speech databases can be divided into two types: acted and improvised [18]. All above three mentioned datasets belongs to acted family which widely used in emotional TTS [19]. We believe that it is appropriate
to employ acted emotional speech dataset for our experiments, due to the improvised speech is hard to induce strong and welldifferentiated emotions [20]."

"We further verify the effectiveness of the proposed domain fusion for model generalization in terms of emotion strength prediction."

"We further evaluate how close the results of StrengthNet for unseen speech can get to the emotional strength as perceived by humans. Since the RAVDESS dataset includes the manual emotion intensity label.  The experiments confirm the superiority of the proposed domain fusion based StrengthNet for unseen speech in terms of human perception."

"In future work, we intend to integrate our StrengthNet as a front-end or back-end for emotional speech synthesis models to enhance the emotion expressiveness
of output emotional speech."

___
4. [Emotional Speaker Identification using a Novel Capsule Nets Model](https://arxiv.org/abs/2201.02994) -> [sciencedirect](https://www.sciencedirect.com/science/article/abs/pii/S0957417421017498)






















































___
5. [MEL Spectrogram](https://medium.com/analytics-vidhya/understanding-the-mel-spectrogram-fca2afa2ce53)




___
6. [Automatic Detection of Depression from Stratified Samples of Audio Data](https://arxiv.org/abs/2111.10783) -> [???]()




___
7. [Automated Sex Classification of Children's Voices and Changes in Differentiating Factors with Age](https://arxiv.org/abs/2209.13112)




___
8. [Language Independent Emotion Quantification using Non linear Modelling of Speech](https://arxiv.org/abs/2102.06003)




___
9. [Voice Conversion Based on Cross-Domain Features Using Variational Auto Encoders](https://arxiv.org/abs/1808.09634)




___
10. [A Fine-tuned Wav2vec 2.0/HuBERT Benchmark For Speech Emotion Recognition, Speaker Verification and Spoken Language Understanding](https://arxiv.org/abs/2111.02735)




___
11. [Improving Automatic Emotion Recognition from speech using Rhythm and Temporal feature](https://arxiv.org/abs/1303.1761)




___
12. [DEEP: Uma arquitetura para reconhecer emoção com base no espectro sonoro da voz de falantes da língua portuguesa](https://bdm.unb.br/bitstream/10483/27583/1/2020_GabrielCampos_LucasMoutinho_tcc.pdf)




___
13. [A Knowledge-Based Recommendation System That Includes Sentiment Analysis and Deep Learning](https://ieeexplore.ieee.org/document/8445585)




___
14. [Emotion intensity detection for social media data](https://www.semanticscholar.org/paper/Emotion-intensity-detection-for-social-media-data-Mashal-Asnani/b28f0916e14c65af4d5f6ec0a3584251b78dc513)




___
15. [Emotion Detection and Analysis on Social Media](https://arxiv.org/abs/1901.08458)




___
16. [The paradoxical role of emotional intensity in the perception of vocal affect](https://www.nature.com/articles/s41598-021-88431-0) -> [VIVAE](https://zenodo.org/record/4066235#.Y2FyG99v-Ul)




___
17. [Human Emotion Recognition: Review of Sensors and Methods ](https://www.mdpi.com/1424-8220/20/3/592) -> [???]()




___
18. [Emotion Intensity and its Control for Emotional Voice Conversion](https://arxiv.org/abs/2201.03967)




___
19. [Emotional Intensity Level Analysis of Speech Emotional Intensity Estimation](https://www.esann.org/sites/default/files/proceedings/2021/ES2021-118.pdf)




___
20. [Recognition of Emotion with Intensity from Speech Signal Using 3D Transformed Feature and Deep Learning](https://www.mdpi.com/2079-9292/11/15/2362) -> [???]()




___
21. [Brazilian Portuguese emotional speech corpus analysis](https://www.gov.br/cti/pt-br/publicacoes/producao-cientifica/seminario-pci/xi_seminario_pci-2021/pdf/seminario-2021_paper_29.pdf)




___
22. [END-TO-END SPEECH RECOGNITION APPLIED TO BRAZILIAN PORTUGUESE USING DEEP LEARNING](http://www.pee.ufrj.br/mwg-internal/de5fs23hu73ds/progress?id=ynpPt7kh6WfQgOdd36Ib7avR6tKN6V-l8iTIWXdw74o,&dl)()




___
23. [StrengthNet: Deep Learning-based Emotion Strength Assessment for Emotional Speech Synthesis](https://arxiv.org/abs/2110.03156) -> [???]()




___
24. [Musical Genre Classification with Convolutional Neural Networks](https://towardsdatascience.com/musical-genre-classification-with-convolutional-neural-networks-ff04f9601a74)




___
25. [The circumplex model of affect: An integrative approach to affective neuroscience, cognitive development, and psychopathology](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2367156/)




___
26. [Russell’s (1980) Circumplex Models](https://psu.pb.unizin.org/psych425/chapter/circumplex-models/) -> [???]()




___
27. [O afeto sob a perspectiva do circumplexo: evidências de validade de construto](http://pepsic.bvsalud.org/scielo.php?script=sci_arttext&pid=S1677-04712017000200005)




___
28. [All-in-One: Emotion, Sentiment and Intensity Prediction using a Multi-task Ensemble Framework](https://www.cse.iitb.ac.in/~pb/papers/ieee-toac-sa.pdf)




___
29. [A Multi-task Ensemble Framework for Emotion, Sentiment and Intensity Prediction](https://arxiv.org/abs/1808.01216)




___
30. [Music emotion recognition based on segment-level two-stage learning](https://link.springer.com/content/pdf/10.1007/s13735-022-00230-z.pdf) -> [???]()




___
31. [Emotion Recognition from Speech: An Unsupervised Learning Approach](https://www.atlantis-press.com/journals/ijcis/125945494/view)




___
32. [Deep Learning Techniques for Speech Emotion Recognition, from Databases to Models](https://www.mdpi.com/1424-8220/21/4/1249)




___
33. [A voice-based real-time emotion detection technique using recurrent neural network empowered feature modelling](https://link.springer.com/content/pdf/10.1007/s11042-022-13363-4.pdf) -> [???]()




___
34. [UNSUPERVISED LEARNING APPROACH TO FEATURE ANALYSIS FOR AUTOMATIC SPEECH EMOTION RECOGNITION](http://labsites.rochester.edu/air/publications/eskimez2018unsupervised.pdf) -> [???]()




___
35. [Unsupervised Feature Learning for Speech Emotion Recognition Based on Autoencoder](https://www.mdpi.com/2079-9292/10/17/2086)




___
36. [Speech Emotion Recognition Using Unsupervised Feature Selection Algorithms](https://www.semanticscholar.org/paper/Speech-Emotion-Recognition-using-Unsupervised-Bandela-Kumar/e8d637f9f02a8c4849e5af09e6b9f9edf5e76eb9)




___
37. [Survey of Deep Representation Learning for Speech Emotion Recognition](https://www.semanticscholar.org/paper/Survey-of-Deep-Representation-Learning-for-Speech-Latif-Rana/368e0844bbd3feb5ab17a271ad1663ca5a6fb7e7)




___
38. [Emotion classification from speech signal based on empirical mode decomposition and non-linear features](https://d-nb.info/1232071765/34)




___
39. [Emotion recognition from speech: a review](https://www.sci.brooklyn.cuny.edu/~levitan/nlp-psych/papers/koolagudi12.pdf)




___
40. [Speech Emotion Recognition Using Deep Learning Techniques: A Review](https://ieeexplore.ieee.org/abstract/document/8805181)




___
41. [Emotion Recognition and Detection Methods: A Comprehensive Survey](https://iecscience.org/uploads/jpapers/202003/dnQToaqdF8IRjhE62pfIovCkDJ2jXAcZdK6KHRzM.pdf)




___
42. [New approach in quantification of emotional intensity from the speech signal: emotional temperature](https://flab.k.hosei.ac.jp/pukiwiki/index.php?plugin=attach&pcmd=open&file=1-s2.0-S0957417415005229-main.pdf&refer=Hirano)




___

<br><br>

Dataset | URL
------- | ---
VERBO   | https://github.com/jrtorresneto/VERBO-emotional-speech-dataset; https://thescipub.com/pdf/jcssp.2018.1420.1430.pdf
VIVAE   | https://zenodo.org/record/4066235#.Y2FyG99v-Ul

<br><br>

Emoção              | VERBO | VIVAE | [x]
------------------- | ----- | ----- | ----
alegria / pleasure  | [x]   | [x]   | alegria
nojo / --           | [x]   | [ ]   |
medo / fear         | [x]   | [x]   | medo
neutro / --         | [x]   | [ ]   |
raiva / anger       | [x]   | [x]   | raiva
surpresa / surprise | [x]   | [x]   | surpresa
tristeza / --       | [x]   | [ ]   |
-- / pain           | [ ]   | [x]   |
-- / achievement    | [ ]   | [x]   |




___

<br><br>

- REFS adicionais:
    - https://ieeexplore.ieee.org/abstract/document/9892110; 
    - https://link.springer.com/content/pdf/10.3758/BRM.42.1.74.pdf
    - https://www.isca-speech.org/archive_v0/sp2008/papers/sp08_717.pdf
    - https://clf.unige.ch/files/3314/4102/7366/14_Peres_153-169.pdf
    - https://link.springer.com/article/10.1007/s13278-018-0505-2
    - https://aclanthology.org/W14-6905.pdf
