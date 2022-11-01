# Fichamento PPGI

<br>

TAGS: `intro, just, alinhamento, motivação, obesp, obgeral, fundteo, analise, etica, result, contrib`.

<br>

1. [Speech Emotion Recognition using Supervised Deep Recurrent System for Mental Health Monitoring](https://arxiv.org/abs/2208.12812)

<details>
<summary>[...]</summary>

`#intro`

"Understanding human behavior and monitoringmental health are essential to maintaining the community and society’s safety"

"According to the Institute for Health Metrics and Evaluation (IHME), the number of diagnosed individuals with one of the mental disorders globally has exceeded 1.1 billion individuals in 2016 [2]"

"Due to late or unreceived mental care, the number of relatedsuicide has increased as well. The number of suicides has exceeded 700,000, meaning one person every 40 seconds dies by suicidal action related to a mental disorder [3]"

"Speech is the primary form of communication and emotional expression [5]. From childhood, even before being able to speak correct words, children express their emotions in their ununderstandable talks, such as their happiness and confusion. Juvenile, adults, and elderly individuals also express their emotions in their speech. All individuals express common emotions such as happy, sad, angry, happy, worry, fear, and neutral in their speech. However, different spoken languages produce differences in how these emotions are expressed in the speech tone and voice [6], [7]"

"There are several mental disorders that can be identified from individual’s emotion changes [9], [10] such as depression disorder [11], [12], stress disorder [13], [14], and anxiety (worry/fear) disorders [15], [16]. Early diagnostic of mental disorders allows the individual to recieve the correct treatment and prevent sever illensses and even protect fom suisidal action [17], [18]."

"Several studies address the effect of the IVA devices on individuals’ social life [24], markating [25], and social communication [26]. However, there are few studies on understanding the user behavior while using intelligent virtual personal assistant devices to improve the user experience. Yang et al. [27] attempted to understand how to improve the IVA user experience by investigating the relationship between perceived enjoyment, perceived usefulness, and product-related characteristics using a user survey"

`#fundteo`

"Zhang et al. [32], Bhargava et al. [33], Krishnan et al. [34], and Venkataramanan et al. [29] proposed different machine learning and deep learning approaches to solve the speech emotion recognition under the scenario I {{ designing a model that used speech signal datasets after performing data preprocessing and feature extraction }} approach"

"The GRU has successfully achieved significant results in various applications, especially in signal data such as emotion recognition from EEG signal [37], sleep stage classification from EEG and EoG [38], arrhythmia supraventricular premature beat detection from ECG signal [39], music source separation [40], and sound event detection [41]. GRU can learn the spatial features of the speech signal and the temporal information due to the recurrent behavior. In this paper, we selected the GRU as a competitive recurrent neural network that requires less budget and can achieve comparable results to the LSTM. The 1D-CNN acts as the feature extractor for the 1D speech signal [42]–[44]."

`#motiv`

"Personal emotion is one of the most significant indicators of mental health normality and issues."

"The model can be applied within an intelligent virtual personal assistant to improve the user experience while combining the user request and emotion to provide the appropriate service"

</details>

___
2. [Depression Recognition using Remote Photoplethysmography from Facial Videos](https://arxiv.org/abs/2206.04399)

<details><summary>[...]</summary>

`#intro`

"Currently, depression screening is usually based on medical interviews described in the Diagnostic and Statistical Manual of Mental Disorders (DSM-V), but depends on the subjectivity and experience of the psychiatrist and the subjective memory of the patient, a fact that can lead to misdiagnosis with its consequential social, physiological, or psychological side effects due to undertreatment or overtreatment of the illness."

"Other objective biomarkers have been shown to be useful for physicians to evaluate and assess the level of depression of the patient in a more confident and precise manner. Recent studies have demonstrated the impact of depression on physiological biomarkers, such as heart rate variability (HRV) calculated from the electrocardiogram (ECG) [3] [4], HRV using PPG signals [5] or electrodermal activity (EDA) [6]."


</details>

___
3. [Accurate Emotion Strength Assessment for Seen and Unseen Speech Based on Data-Driven Deep Learning](https://arxiv.org/abs/2206.07229) -> [ISCA](https://www.isca-speech.org/archive/pdfs/interspeech_2022/liu22i_interspeech.pdf)   

<details>
<summary>[...]</summary>

`#intro`

"Emotion classification of speech and assessment of the emotion strength are required in applications such as emotional text-to-speech and voice conversion."

"An acoustic encoder, a strength predictor, and an auxiliary emotion predictor."

"Accurate emotion classification of speech and assessment of its strength are essential to profile human behaviors, which has many potential applications, such as human-robot interface, human-machine dialogue, and social media."

"The simplest emotion strength control method is to linearly scale the emotion representation vector [1]. The effect of such a linear scale is hardly interpretable. To obtain a meaningful strength descriptor, some followed the idea of “relative attributes” [2–4] and quantify the emotion strength by learning from the <neutral, emotional> speech pairs. Support-Vector-Machine (SVM) based attribute ranking [4] learns the difference between two samples that are significantly different in a particular attribute, that has been widely studied in computer vision [5, 6]."

"Recently, it was shown that deep learning has the ability to learn a mapping function effectively [7,8]. The neural solution learns complex non-linear mapping relationships, and exhibits good generalization ability with the support of a large number of model parameters [9]. Most importantly, the data-driven training strategy appears to be more powerful and have the potential to achieve good performance for out-of-domain data [10]."

`#fundteo`

"The acoustic encoder extracts the high-level features from the input mel-spectrum. The strength predictor aims to predict the strength score for the input mel-spectrum. The emotion predictor is used to predict the emotion category, which serves as an auxiliary task."

"The strategy of stacking more convolutional layers to expand the receptive field of a CNN has been widely used to model time series data and yield satisfactory performance [7]. Given an input mel-spectrum
sequence X, the CNN based acoustic encoder aims to extract a high-level feature H. The high-level feature H is then fed to two predictors to predict the emotion strength score and emotion category,  respectively."

"The strength predictor then reads the high-level feature representation to predict the emotion strength. Recent studies have confirmed the effectiveness of combining CNN and BiLSTM for classification [7], and recognition [11] tasks"

"To improve the model generalization, we employ a domain fusion strategy [12, 13], which mix multiple emotional speech datasets from various domains to train our StrengthNet. The fused data mixed from various domains will represent a more comprehensive set, thus minimizing the distance between the training and validation set, as well as any future testing sets."

"Experimental results demonstrate that our StrengthNet can achieve accurate emotion strength prediction for both seen and unseen speech with the help of domain fusion strategy."

</details>

___
4. [Emotional Speaker Identification using a Novel Capsule Nets Model](https://arxiv.org/abs/2201.02994) -> [sciencedirect](https://www.sciencedirect.com/science/article/abs/pii/S0957417421017498)

<details>
<summary>[...]</summary>

`#intro`

"Speaker recognition models trained on neutral speech fail to correctly identify speakers under emotional stress. Although considerable advancements in speaker identification have been made using convolutional neural networks (CNN), CNNs cannot exploit the spatial association between low-level features."

"Noisy environments or the speaker’s emotional, can affect the performance of such techniques (Bashirpour & Geravanchizadeh, 2018). The performance of these approaches is reduced significantly when the speech samples are obtained under suboptimal conditions, e.g., an emotional environment (J. H. L. Hansen & Patil, 2007), where the speech samples are emotional or highly expressive (Ghiurcau et al., 2011; Parthasarathy et al., 2017). Speech samples obtained under circumstances where the speaker is not influenced by any kind of emotion is referred to as ‘neutral’ speech samples, while those under any kind of emotion (such as happy, sad, anger and so on) are referred to as emotional speech. Emotional speech varies the acoustic features extracted from the samples."

"Human speech is more frequently emotional or expressive, which alters the speech characteristics of a speaker."

`#fundteo`

"CNN uses a pooling operation, which makes them insensitive to the spatial information of the input features, i.e., the position information of features in the time-frequency axis. The pooling function makes the CNN invariant and results in losing certain features."

"The increasing popularity of deep learning based techniques (J. et al., 2015; Nassif et al., 2019; Variani et al., 2014) in speech processing has motivated researchers to use convolutional neural networks (CNN) for SI (Lukic et al., 2016). However, CNN use a pooling operation, which makes them insensitive to the spatial information of the input features, i.e., the position information of features in the time-frequency axis. The pooling function makes the CNN invariant and results in losing certain features, which leads to the need for an extensive amount of training data to compensate the loss. However, acquiring sufficient amounts of training data can be difficult in practical application (Kwabena Patrick et al., 2019)."

"Meftah et al. (Meftah et al., 2020) exploited linearly spaced spectrograms to distinguish emotional speakers in Arabic and English using a fusion of a convolutional neural network and the long short-term memory architecture, and they based their study on the KSU Emotions, EPST, WEST POINT, and TIMIT databases."

"Despite the popularity of using CNNs to extract high level features, it has been found that the kernel-based convolution operation in a CNN can fail to capture certain features or its spatial information (Kwabena Patrick et al., 2019). In addition, the pooling operation renders them incapable of recognizing the spatial hierarchies between features."

"CNNs are partially responsible for the increase of interest in deep learning models in recent years (Bunrit et al., 2019; Lukic et al., 2016). Convolutional layers, which form the first layers of a classical CNN, facilitate the extraction of features by applying variable-sized filters to the input to form feature maps using the convolution process. Multiple convolution kernels or filters are often applied and may be followed by the pooling operation, which helps to ensure that semantically similar features are merged to a single feature. Although this helps down-sampling, it also results in
making CNNs spatially invariant. Hinton et al. (Hinton et al., 2011) observed that multiple layers of such down-sampling can lead to loss of spatial information and suggested the idea of “capsules” to characterize an entity, where neurons comprising a capsule capture both the spatial information and existence probability of the features into a vector."

"MFCCs have been the go-to feature since their introduction in the 1980s and have been utilized extensively in many speech and speaker recognition studies (Tirumala et al., 2017). Computing MFCCs is a straightforward process, as shown in Fig. 2. This process begins by slicing audio samples into sliding frames of width 25 ms, resulting in statistically stationary signals. This is followed by discrete Fourier analysis of the frames to extract the frequency information"

`#motiv`

"Identifying an emotional speaker has numerous applications, e.g., identifying a person from emotional (anger or panic) speech samples during a crime investigation, identifying and assisting people in panic at emergency helpline centers and assessing the stress or frustration of callers at customer centers."


`#contrib`

"Previous studies have focused on analyzing speaker identification under different emotional and stressful environments to realize optimal performance in robust human–computer interactions (Alluri et al., 2017; Fragopanagos & Taylor, 2005; Senthil Raja & Dandapat, 2010; S. Wu et al., 2011). Some studies (Scherer et al., 2000; T. Wu et al., 2005) have used emotional speech samples from speakers to train the model to improve speaker identification performance; however, this is not a feasible solution for practical applications."

"Ghiurcau et al. (Ghiurcau et al., 2011) studied the negative impact of the emotional state of a speaker on the performance of SI systems using the GMM. In a later study, they compared the results to those obtained using an SVM classifier on the Berlin speech database and concluded that models trained on neutral speech produced poor results on speech samples collected in an emotional environment. The results obtained varied with emotion (with anger and happiness scoring the least). The results were found to improve vastly when emotional speech was included in training, although this is not practical solution. Wu et al. (Zhaohui et al., 2006) explored ways to enhance speaker identification by studying techniques to alter prosodic features and utilizing the same to adapt the features from emotional speech."

</details>


___
5. [MEL Spectrogram](https://medium.com/analytics-vidhya/understanding-the-mel-spectrogram-fca2afa2ce53) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
6. [Automatic Detection of Depression from Stratified Samples of Audio Data](https://arxiv.org/abs/2111.10783) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
7. [Automated Sex Classification of Children's Voices and Changes in Differentiating Factors with Age](https://arxiv.org/abs/2209.13112) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
8. [Language Independent Emotion Quantification using Non linear Modelling of Speech](https://arxiv.org/abs/2102.06003) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
9. [Voice Conversion Based on Cross-Domain Features Using Variational Auto Encoders](https://arxiv.org/abs/1808.09634) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
10. [A Fine-tuned Wav2vec 2.0/HuBERT Benchmark For Speech Emotion Recognition, Speaker Verification and Spoken Language Understanding](https://arxiv.org/abs/2111.02735) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
11. [Improving Automatic Emotion Recognition from speech using Rhythm and Temporal feature](https://arxiv.org/abs/1303.1761) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
12. [DEEP: Uma arquitetura para reconhecer emoção com base no espectro sonoro da voz de falantes da língua portuguesa](https://bdm.unb.br/bitstream/10483/27583/1/2020_GabrielCampos_LucasMoutinho_tcc.pdf) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
13. [A Knowledge-Based Recommendation System That Includes Sentiment Analysis and Deep Learning](https://ieeexplore.ieee.org/document/8445585) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
14. [Emotion intensity detection for social media data](https://www.semanticscholar.org/paper/Emotion-intensity-detection-for-social-media-data-Mashal-Asnani/b28f0916e14c65af4d5f6ec0a3584251b78dc513) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
15. [Emotion Detection and Analysis on Social Media](https://arxiv.org/abs/1901.08458) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
16. [The paradoxical role of emotional intensity in the perception of vocal affect](https://www.nature.com/articles/s41598-021-88431-0) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
17. [Human Emotion Recognition: Review of Sensors and Methods ](https://www.mdpi.com/1424-8220/20/3/592) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
18. [Emotion Intensity and its Control for Emotional Voice Conversion](https://arxiv.org/abs/2201.03967) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
19. [Emotional Intensity Level Analysis of Speech Emotional Intensity Estimation](https://www.esann.org/sites/default/files/proceedings/2021/ES2021-118.pdf) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
20. [Recognition of Emotion with Intensity from Speech Signal Using 3D Transformed Feature and Deep Learning](https://www.mdpi.com/2079-9292/11/15/2362) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
21. [Brazilian Portuguese emotional speech corpus analysis](https://www.gov.br/cti/pt-br/publicacoes/producao-cientifica/seminario-pci/xi_seminario_pci-2021/pdf/seminario-2021_paper_29.pdf) -> [???]() 

<details>
<summary>[...]</summary>



</details>

___
22. [END-TO-END SPEECH RECOGNITION APPLIED TO BRAZILIAN PORTUGUESE USING DEEP LEARNING](http://www.pee.ufrj.br/mwg-internal/de5fs23hu73ds/progress?id=ynpPt7kh6WfQgOdd36Ib7avR6tKN6V-l8iTIWXdw74o,&dl) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
23. [StrengthNet: Deep Learning-based Emotion Strength Assessment for Emotional Speech Synthesis](https://arxiv.org/abs/2110.03156) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
24. [Musical Genre Classification with Convolutional Neural Networks](https://towardsdatascience.com/musical-genre-classification-with-convolutional-neural-networks-ff04f9601a74) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
25. [The circumplex model of affect: An integrative approach to affective neuroscience, cognitive development, and psychopathology](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2367156/) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
26. [Russell’s (1980) Circumplex Models](https://psu.pb.unizin.org/psych425/chapter/circumplex-models/) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
27. [O afeto sob a perspectiva do circumplexo: evidências de validade de construto](http://pepsic.bvsalud.org/scielo.php?script=sci_arttext&pid=S1677-04712017000200005) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
28. [All-in-One: Emotion, Sentiment and Intensity Prediction using a Multi-task Ensemble Framework](https://www.cse.iitb.ac.in/~pb/papers/ieee-toac-sa.pdf) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
29. [A Multi-task Ensemble Framework for Emotion, Sentiment and Intensity Prediction](https://arxiv.org/abs/1808.01216) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
30. [Music emotion recognition based on segment-level two-stage learning](https://link.springer.com/content/pdf/10.1007/s13735-022-00230-z.pdf) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
31. [Emotion Recognition from Speech: An Unsupervised Learning Approach](https://www.atlantis-press.com/journals/ijcis/125945494/view) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
32. [Deep Learning Techniques for Speech Emotion Recognition, from Databases to Models](https://www.mdpi.com/1424-8220/21/4/1249) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
33. [A voice-based real-time emotion detection technique using recurrent neural network empowered feature modelling](https://link.springer.com/content/pdf/10.1007/s11042-022-13363-4.pdf) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
34. [UNSUPERVISED LEARNING APPROACH TO FEATURE ANALYSIS FOR AUTOMATIC SPEECH EMOTION RECOGNITION](http://labsites.rochester.edu/air/publications/eskimez2018unsupervised.pdf) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
35. [Unsupervised Feature Learning for Speech Emotion Recognition Based on Autoencoder](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjUpOOR54P7AhXOupUCHRf4BW4QFnoECAsQAQ&url=https%3A%2F%2Fwww.mdpi.com%2F2079-9292%2F10%2F17%2F2086%2Fpdf-vor&usg=AOvVaw2v1k9G3XnHqMWDkWOL8wdR) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
36. [Speech Emotion Recognition Using Unsupervised Feature Selection Algorithms](https://www.semanticscholar.org/paper/Speech-Emotion-Recognition-using-Unsupervised-Bandela-Kumar/e8d637f9f02a8c4849e5af09e6b9f9edf5e76eb9) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
37. [Survey of Deep Representation Learning for Speech Emotion Recognition](https://www.semanticscholar.org/paper/Survey-of-Deep-Representation-Learning-for-Speech-Latif-Rana/368e0844bbd3feb5ab17a271ad1663ca5a6fb7e7) -> [???]()

<details>
<summary>[...]</summary>



</details>

___
38. [Emotion classification from speech signal based on empirical mode decomposition and non-linear features](https://d-nb.info/1232071765/34) -> [???]()

<details>
<summary>[...]</summary>



</details>

___


<br><br>


Dataset | URL
------- | ---
VERBO   | https://github.com/jrtorresneto/VERBO-emotional-speech-dataset
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
