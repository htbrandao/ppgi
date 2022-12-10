# Fichamento @ bbolsa

1. [Speech Emotion Recognition using Supervised Deep Recurrent System for Mental Health Monitoring](https://arxiv.org/abs/2208.12812)

`#intro`

"Understanding human behavior and monitoring mental health are essential to maintaining the community and society’s safety"

"According to the Institute for Health Metrics and Evaluation (IHME), the number of diagnosed individuals with one of the mental disorders globally has exceeded 1.1 billion individuals in 2016 [2]"

"Due to late or unreceived mental care, the number of relatedsuicide has increased as well. The number of suicides has exceeded 700,000, meaning one person every 40 seconds dies by suicidal action related to a mental disorder [3]"

<span style="color:green">
"Speech is the primary form of communication and emotional expression [5]. From childhood, even before being able to speak correct words, children express their emotions in their ununderstandable talks, such as their happiness and confusion. Juvenile, adults, and elderly individuals also express their emotions in their speech. All individuals express common emotions such as happy, sad, angry, happy, worry, fear, and neutral in their speech. However, different spoken languages produce differences in how these emotions are expressed in the speech tone and voice [6], [7]"
</span>

"There are several mental disorders that can be identified from individual’s emotion changes [9], [10] such as depression disorder [11], [12], stress disorder [13], [14], and anxiety (worry/fear) disorders [15], [16]. Early diagnostic of mental disorders allows the individual to recieve the correct treatment and prevent sever illensses and even protect fom suisidal action [17], [18]."

"Several studies address the effect of the IVA devices on individuals’ social life [24], markating [25], and social communication [26]. However, there are few studies on understanding the user behavior while using intelligent virtual personal assistant devices to improve the user experience. Yang et al. [27] attempted to understand how to improve the IVA user experience by investigating the relationship between perceived enjoyment, perceived usefulness, and product-related characteristics using a user survey"

`#fundteo`

"Zhang et al. [32], Bhargava et al. [33], Krishnan et al. [34], and Venkataramanan et al. [29] proposed different machine learning and deep learning approaches to solve the speech emotion recognition."

"The GRU has successfully achieved significant results in various applications, especially in signal data such as emotion recognition from EEG signal [37], sleep stage classification from EEG and EoG [38], arrhythmia supraventricular premature beat detection from ECG signal [39], music source separation [40], and sound event detection [41]. GRU can learn the spatial features of the speech signal and the temporal information due to the recurrent behavior. In this paper, we selected the GRU as a competitive recurrent neural network that requires less budget and can achieve comparable results to the LSTM. The 1D-CNN acts as the feature extractor for the 1D speech signal [42] [43] [44]."

`#motiv`

"Personal emotion is one of the most significant indicators of mental health normality and issues."

"The model can be applied within an intelligent virtual personal assistant to improve the user experience while combining the user request and emotion to provide the appropriate service"

___
2. [Depression Recognition using Remote Photoplethysmography from Facial Videos](https://arxiv.org/abs/2206.04399)

`#intro`

"Currently, depression screening is usually based on medical interviews described in the Diagnostic and Statistical Manual of Mental Disorders (DSM-V), but depends on the subjectivity and experience of the psychiatrist and the subjective memory of the patient, a fact that can lead to misdiagnosis with its consequential social, physiological, or psychological side effects due to undertreatment or overtreatment of the illness."

"Other objective biomarkers have been shown to be useful for physicians to evaluate and assess the level of depression of the patient in a more confident and precise manner. Recent studies have demonstrated the impact of depression on physiological biomarkers, such as heart rate variability (HRV) calculated from the electrocardiogram (ECG) [3] [4], HRV using PPG signals [5] or electrodermal activity (EDA) [6]."

___
3. [Accurate Emotion Strength Assessment for Seen and Unseen Speech Based on Data-Driven Deep Learning](https://arxiv.org/abs/2206.07229) -> [ISCA](https://www.isca-speech.org/archive/pdfs/interspeech_2022/liu22i_interspeech.pdf)   


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

___
4. [Emotional Speaker Identification using a Novel Capsule Nets Model](https://arxiv.org/abs/2201.02994) -> [sciencedirect](https://www.sciencedirect.com/science/article/abs/pii/S0957417421017498)


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

___
5. [MEL Spectrogram](https://medium.com/analytics-vidhya/understanding-the-mel-spectrogram-fca2afa2ce53)


`#fundteo`

"A signal is a variation in a certain quantity over time. For audio, the quantity that varies is air pressure. How do we capture this information digitally? We can take samples of the air pressure over time. The rate at which we sample the data can vary, but is most commonly 44.1kHz, or 44,100 samples per second. What we have captured is a waveform for the signal, and this can be interpreted, modified, and analyzed with computer software."

"An audio signal is comprised of several single-frequency sound waves. When taking samples of the signal over time, we only capture the resulting amplitudes. The Fourier transform is a mathematical formula that allows us to decompose a signal into it’s individual frequencies and the frequency’s amplitude. In other words, it converts the signal from the time domain into the frequency domain. The result is called a spectrum."

"The fast Fourier transform (FFT) is an algorithm that can efficiently compute the Fourier transform. It is widely used in signal processing. I will use this algorithm on a windowed segment of our example audio."

"Short-time Fourier transform. The FFT is computed on overlapping windowed segments of the signal, and we get what is called the spectrogram."

"You can think of a spectrogram as a bunch of FFTs stacked on top of each other. It is a way to visually represent a signal’s loudness, or amplitude, as it varies over time at different frequencies. There are some additional details going on behind the scenes when computing the spectrogram. The y-axis is converted to a log scale, and the color dimension is converted to decibels (you can think of this as the log scale of the amplitude). This is because humans can only perceive a very small and concentrated range of frequencies and amplitudes."

"Studies have shown that humans do not perceive frequencies on a linear scale. We are better at detecting differences in lower frequencies than higher frequencies. For example, we can easily tell the difference between 500 and 1000 Hz, but we will hardly be able to tell a difference between 10,000 and 10,500 Hz, even though the distance between the two pairs are the same. In 1937, Stevens, Volkmann, and Newmann proposed a unit of pitch such that equal distances in pitch sounded equally distant to the listener. This is called the mel scale. We perform a mathematical operation on frequencies to convert them to the mel scale."

"A mel spectrogram is a spectrogram where the frequencies are converted to the mel scale. I know, right? Who would’ve thought? What’s amazing is that after going through all those mental gymnastics to try to understand the mel spectrogram, it can be implemented in only a couple lines of code."

"1. We took samples of air pressure over time to digitally represent an audio signal; 2. We mapped the audio signal from the time domain to the frequency domain using the fast Fourier transform, and we performed this on overlapping windowed segments of the audio signal; 3. We converted the y-axis (frequency) to a log scale and the color dimension (amplitude) to decibels to form the spectrogram; 4.We mapped the y-axis (frequency) onto the mel scale to form the mel spectrogram."

___
6. [Automatic Detection of Depression from Stratified Samples of Audio Data](https://arxiv.org/abs/2111.10783) -> [???]()


`#intro`

"Depression diagnosis and treatment has been inaccessible in many parts of the world due to financial costs, privacy concerns and a severe shortage of psychiatrists. This scarcity is worsened in low-income countries which have a psychiatrist to population ratio 210 times lower than that of countries with better economies [2]. As a result, up to two-thirds of all depression cases are left undiagnosed and thus
untreated [3]. Untreated depression can ruin quality of life by causing loss of sleep, concentration, and happiness."

`#fundteo`

"We applied mel-spectrogram to extract relevant features from the audio. Three types of encoders were tested i.e. 1D CNN, 1D CNN-LSTM, and 1D CNN-GRU. After tuning hyperparameters systematically, we found that 1D CNN-GRU encoder with a kernel size of 5 and 15 seconds of recording data appeared to have the best performance with F1 score of 0.75, precision of 0.64, and recall of 0.92"

"Depression is defined by the American Psychiatric Association as a common mental disorder that causes sadness and loss of interest in activities which were once enjoyed by the individual [4][62]."

"Conventionally, mental disorders including depression are diagnosed manually by psychiatrists. Current methods consist of interviews and questionnaires (such as PHQ-2 [8], PHQ-8 [9] and PHQ-9 [10]) designed to diagnose this type of disorder. Results from these surveys will be analyzed by psychiatrists who subsequently conduct an one-on-one interview with the patient. During the interview, psychiatrists search for markers related to depression in patients’ speech e.g. emotional display, reasonings, and inconsistencies [25]."

"Currently, there has been an integration of Artificial Intelligence (AI) in various fields of medical analysis [26][27][28][29][30], but not many were practically used in psychological disorders detection. Skills developed by psychiatrists for instance speech pattern analysis can be 3 learned and mastered by AI. Therefore, AI has become a promising alternative to manual depression detection."

"Speech is an act of expressing ideas and emotion by vocalization [31]. It is also an indispensable component for communication between individuals inside human society. As for communication, another element called “language” has been used along with speech. Language is the way to express thought through a distinct set of symbols, dialects, or sounds (speech). Language understanding can be acquired by a comprehensive study of vocal patterns and alphabets. Humans are capable of identifying as well as expressing speech and languages; meanwhile, machines do not have the ability to do so."

"For automatic speech recognition (ASR), the system will process vocal data (speech) into digital signals suitable for AI training and analysis [32]. Speakers have unique voice patterns due to the variation of personalities and body structure. Accordingly, ASR uses criteria such as speech size and speaking styles to classify voice samples into groups. Spectrograms and chroma feature techniques may potentially enhance the system in organizing voices [33]. Both techniques extract and present relevant features to the system, enabling the system to conduct more complex classification and evaluation [34][38][42][52]. The methods provided above allow AI to effectively perform speech and emotions recognition"

"A range of research has been conducted in the field of speech classification and recognition. In 2013, Li Deng and colleagues [35] presented an overview of ‘‘New Types of Deep Neural Network Learning for Speech Recognition and Related Applications,’’ which is a collection of studies related to sound technologies."

"Research conducted in 2018 [41] demonstrated deep learning networks’ ability to detect mood disorders (unipolar depression and bipolar disorder)."

"Another approach to use DNNs in psychological disorders analysis was made in 2018. Tuka Alhanai et al. [42] utilized Long-Short Term Memory (LSTM) neural networks to differentiate depression patients from ordinary people during an emotional talking environment."

"Techniques for feature extraction such as Mel-Spectrograms have been used extensively in the field of speech recognition systems [44][45][46][47]"

"In many speech recognition projects, the analysis focuses on the distribution of acoustic patterns over time [43][48][51][58]"

`#motiv`

"Furthermore, depression is also the leading cause of disability worldwide [5]. From a socioeconomic standpoint, depressed individuals lose up to 4 more hours of productive work per week compared to their healthy counterparts [6]. This can have devastating impacts on both the individual’s livelihood and the overall economic output which is estimated to cost $210.5 billion per year globally [7]. Therefore, it is crucial to make depression diagnosis more accessible to mitigate these consequences on society as well as individuals."

___
7. [Automated Sex Classification of Children's Voices and Changes in Differentiating Factors with Age](https://arxiv.org/abs/2209.13112)


`#fundteo`

"It is known that children’s voice attributes are age dependent28. Therefore, any successful models of sex classification in children are likely to be sensitive to the speaker’s age. The most important factor that influences children’s voice attributes is puberty29,30, which usually starts between ages 8 and 13 years in girls and between ages 9 and 15 years in boys31,32."

___
8. [Language Independent Emotion Quantification using Non linear Modelling of Speech](https://arxiv.org/abs/2102.06003)


`#intro`

"Emotion is a psychological state related with the sensory system brought on by hormonal changes differently connected with contemplations, sentiments, social reactions, and a level of joy or disappointment. This hormonal changes cause audibly distinguishable features in speech and visibly distinct features in facial expressions. This audio-visual communication helps people to perceive each other’s emotion. Audio signal, including both speech and music, in general are inherently complex and few non-linear studies have been conducted to understand the underlying complexity and non-linearity of these signals and their manifestation in the human brain [1-12]. This underlying complex nature of audio signals makes emotion recognition a troublesome task for a machine. The motivation behind emotion recognition framework is to utilize feeling related learning so that human machine correspondence will be improved [13]"

___
9. [Voice Conversion Based on Cross-Domain Features Using Variational Auto Encoders](https://arxiv.org/abs/1808.09634)

> n/a

___
10. [A Fine-tuned Wav2vec 2.0/HuBERT Benchmark For Speech Emotion Recognition, Speaker Verification and Spoken Language Understanding](https://arxiv.org/abs/2111.02735)


`#fundteo`

"In speech domain, excellent self-supervised models are emerging [1, 2, 3, 4, 5, 6, 7, 8, 9]"

"In the field of Speech Emotion Recognition (SER), Speaker Verification (SV) and Spoken Language Understanding (SLU), it is still vague whether self-supervised models can produce better performance compared with traditional supervised models (spectral features + CNN-based feature extraction + RNN/Transformer based time series modeling) [12, 13, 14, 15, 16]. However, meaningful attempts have been made in some previous works, which we will introduce below"

___
11. [Improving Automatic Emotion Recognition from speech using Rhythm and Temporal feature](https://arxiv.org/abs/1303.1761)


`#fundteo`

"The most commonly used acoustic features in literature are related to MFCC’s and prosody features like pitch, intensity and speaking rate"

"Extracting valuable features is another challenging task in the emotion recognition system. Mel frequency cepstral coefficients (MFCC) are one of the important features used in speech signal processing. Initially designed for speech recognition tasks they often give excellent performance in emotion detection tasks as well [13]."

"An artificial neural network (ANN), usually called "neural network" (NN), is a mathematical model or computational model that tries to simulate the structure and/or functional aspects of biological neural networks. It consists of an interconnected group of artificial neurons and processes information using a connectionist approach to computation [14]."

___
12. [DEEP: Uma arquitetura para reconhecer emoção com base no espectro sonoro da voz de falantes da língua portuguesa](https://bdm.unb.br/bitstream/10483/27583/1/2020_GabrielCampos_LucasMoutinho_tcc.pdf)


`#intro`

<span style="color:green">
"O reconhecimento de emoção em fala é uma linha de pesquisa dentro da Inteligência Artificial (IA), que consiste nas tarefas de reconhecimento e classificação da reação afetiva de um indivíduo [1]. O estudo das emoções e a maneira pelas quais as entendemos e as representamos no contexto computacional formam a área de conhecimento denominada Computação Afetiva [2]. "
</span>

<span style="color:green">
"A aplicação de modelos estatísticos e de algoritmos de aprendizagem de máquina, do inglês machine learning (ML), vem sendo um dos possíveis caminhos para realizar tarefas de reconhecimento de emoção na fala desde o final do século XX [6] [7]. Entretanto, conseguir identificar o estado emocional de um sujeito não é uma tarefa trivial, visto que demanda uma apurada capacidade de percepção. Em seu contexto original, os interlocutores utilizam várias informações visuais, auditivas, semânticas e metalinguísticas [8] para determinar qual emoção a fala de uma pessoa invoca, o que torna a tarefa bastante complexa e propensa a erros para o contexto da IA"
</span>

<span style="color:green">
"As emoções também têm papel importante na comunicação humana. No contexto natural, utilizamos várias informações do ambiente para conseguirmos detectar emoções em suas expressões. Assim, é seguro afirmar que a fala é um dos elementos relevantes ao se tentar observar quais emoções estão sendo expressadas por um interlocutor. Nesse contexto, existem trabalhos que afirmam que emoções são expressas diferentemente pela fala humana e que ouvintes são capazes de corretamente inferir o estado emocional de um interlocutor apenas com a informação da voz [8]."
</span>

`#fundteo`

"Diversos estudos foram realizados para o entendimento de quais fatores são relevantes para o reconhecimento de emoção [8] [9]. Dentre essas pesquisas, cabe citar o trabalho de Scherer (1995) [8], que apresenta evidências de que emoções são expressas diferentemente pela fala humana e que ouvintes são capazes de corretamente inferir o estado emocional de um interlocutor apenas com a informação da voz."

"Uma das principais consiste na inexistência de um consenso sobre a definição teórica das emoções [10], de modo que as características mais importantes para a distinção entre emoções ainda não são claras. Além disso, aspectos como a variabilidade das frases faladas por pessoas diferentes adiciona outro nível de dificuldade na distinção de emoções, pois características específicas da voz de um indivíduo, como sotaque e ritmo da fala, alteram os resultados das features comumente extraídas da voz [9], tais como as prosódicas e MFCC (Mel-Frequency Cepstral Coefficients), utilizadas em trabalhos da literatura relacionada [6] [11] [12]. Adicionalmente, existem trabalhos [13] que apontam que a linguagem falada é um dos aspectos que influenciam diretamente no processo de reconhecimento de emoção."

"A literatura relacionada apresenta diversas propostas de modelos para a realização da tarefa de reconhecimento de emoção na fala. Trabalhos como Dellaert et al. (1996) [6], Kwon et al. (2003) [7] e Pan, Shen (2012) [11], utilizam modelos mais tradicionais de IA, tais como K-nearest Neighbors (KNN), Support Vector Machines (SVM) e Hidden Markov Models (HMM). Em Dellaert et al. (1996) [6], são utilizadas apenas features prosódicas para o modelo, com o intuito de reconhecer emoções somente pelas características fonéticas e linguísticas do som. Já em Kwon et al. (2003) [7] e Pan, Shen (2012) [11], são incorporadas as features MFCC aos modelos, que, a partir deste momento, tornou-se a feature predominante em trabalhos da área. Contudo, Dellaert et al. (1996) [6], Kwon et al. (2003) [7] e Pan, Shen (2012) [11] utilizam, ainda, modelos de ML mais simplórios, como o HMM, o KNN e o SVM. O próximo avanço das pesquisas analisadas é apresentado nos trabalhos de Han, Yu, Tanshev (2014) [12] e Abdel-Hamid et al. (2014) [16], no qual é introduzida a utilização de modelos de DL. A partir deste ponto, os trabalhos divergem entre si quanto à exploração de modelos com arquiteturas cada vez mais robustas, como no caso de [17] e [18], que utilizam modelos híbridos 1 para a classificação de emoções na voz"

"Adicionalmente, ressalta-se que nenhum dos trabalhos relacionados treina modelos com base em dados de voz na língua portuguesa do Brasil, e, tendo em vista as evidências [13] dos impactos da linguagem no
processo de expressão de emoção em voz, em função, por exemplo, da presença de aspectos congruentes aos regionalismos e ritmos de fala, evidencia-se a importância de trabalhos que explorem reconhecimento de emoção em voz com enfoque na língua portuguesa."

"A base de dados de voz VERBO [21] utiliza o formato .wav, que não realiza compressão do som digital, sendo, dessa forma, o formato digital mais próximo da expressão natural do som."

<span style="color:green">
"Existem trabalhos que demonstram que é possível inferir a emoção expressada por uma representação digital de uma fala, com diferentes técnicas de inteligência artificial [11] [12] [17]. Assim, são confirmadas duas suposições importantes para este trabalho: (i) É possível inferir o estado emocional de um interlocutor apenas com a informação da fala; e (ii) é possível solucionar a tarefa de reconhecimento de emoção na voz por técnicas de IA."
</span>

"Uma das formas de se organizar o conjunto de emoções é observada no Modelo Circumplexo, introduzido por Russel em [22]"

"A aplicação de modelos estatísticos e de algoritmos de aprendizagem de máquina para o reconhecimento da fala vem sendo discutida em trabalhos acadêmicos desde o final do século XX [27] [28]. A utilização destes para o reconhecimento de emoção na fala também tem trabalhos datados do mesmo período [6] [7], porém ganharam mais espaço apenas nos últimos anos, em especial de 2012 a 2020 [11] [12] [17] [18] [19] [20]. Apesar da popularização recente do tema, pouco foi publicado acerca do assunto em âmbito nacional, de forma que a pesquisa de Neto et al.(2018) [21] é tomada como a única referência brasileira, sendo esta utilizada para adquirir a base de dados de voz em português."

"Para superar o estado-da-arte de algoritmos tradicionais de DL nesta base, como um único modelo LSTM (Long-Short Term Memory) ou CNN, os pesquisadores sugerem a extração de ambos os aspectos verbais e não verbais da fala para classificação, o que seria possível utilizando uma arquitetura híbrida: uma CNN para extração das features e uma LSTM (Long-Short Term Memory) para classificação. O modelo híbrido superou o resultado dos modelos tradicionais de DL. Outra pesquisa neste viés é a de Zhao, Mao e Chen (2019) [18]."

"Diferentemente de [17] e [18], que sugerem a aplicação de modelos híbridos CNN-LSTM, o DEEP propõe uma arquitetura composta por classificadores CNN especialistas para cada emoção, com o intuito de não
propagar os erros, como pode ocorrer ao se colocar modelos sequencialmente. Na busca de novas metodologias, o DEEP também converge com [19] e [20] na exploração de entradas diferentes das tradicionais, que contém somente features prosódicas e MFCC. Ao contrário de [19], que incorpora entradas de texto, e [20], que incorpora entradas de imagem dos espectogramas, o DEEP acrescenta uma nova feature de áudio,
as cromáticas, estas que carregam consigo características tonais do som, visando otimizar o processo que exigiria a adição de modelos para a conversão de voz em áudio e imagem. Além dos fatores mencionados, o DEEP também se diferencia de [17], [18] [19] e [20], por ser o único modelo treinado para o reconhecimento de emoção na fala em língua portuguesa."

"Adicionalmente, adotamos como objetivo realizar a tarefa de reconhecimento de emoção na fala com o conjunto de dados na língua portuguesa, por não terem sido encontrados trabalhos na literatura que tenham realizado esta tarefa. Tal objetivo só é possível devido à recente publicação do trabalho de Neto, José e Filho (2018) [21] que contempla a construção de uma base de dados de emoção na voz em língua portuguesa, o VERBO. Por se tratar de uma base de dados nova, o estudo dos ganhos de performance da arquitetura proposta exige, também, a comparação dos resultados com o de arquiteturas tradicionais de um único modelo treinados na mesma base, no caso, utilizando-se de apenas um classificador CNN."

"MFCC : Além de ser uma das formas de representação espectral do som, é uma das features mais aplicada para tarefas de reconhecimento de fala [30] [31] e de emoção na fala [11] [7];. Os MFCCs são compostos por um conjunto de coeficientes, que coletivamente formam um MFC, Mel-Frequency Cepstrum, que é uma representação da densidade espectral a curto prazo de um som. Para obter estes coeficientes, é realizado o processo chamado de Mel-Frequency Wrapping. Sua ideia é de transformar a saída da FFT em uma instância de uma escala Mel [32], que é uma escala construída baseada em tons que são perceptivelmente  equidistantes ao ouvido humano. Após o processo de Mel-Frequency Wrapping, aplicamos a Transformada Discreta de Cosseno nos resultados obtidos do passo anterior. O objetivo desse passo é obter o Cepstrum [33], que é utilizado para investigar estruturas e obter informação sobre fala em um espectro."

"Cromáticas: A feature cromática é composta por doze classes tonais. A combinação das informações relacionadas ao tom de um som é chamada de HPCP (Harmonic Pitch Class Profiles), que descreve as características tonais do som. Tal feature utilizada para análise musical, por exemplo, um método computacional para improvisação musical por meio da detecção automática da escala de acordes [34]. A
decisão de aplicá-la para a tarefa de reconhecimento de voz foi pautada na tonalidade da voz que auxiliou a distinguir as emoções, principalmente considerando a diferença tonal da expressão de uma emoção por cada ator e atriz, diferente dos trabalhos da literatura que não a utilizam."

"Prosódicas: A feature prosódica relaciona-se às características fonéticas e linguísticas do som, as quais se associam com elementos interligados da fala, ao contrário de segmentos fonéticos individuais. Tal feature utilizada em sistemas de reconhecimento de voz [6] [11] para informar sobre aspectos tais como entonação, tremulação, estresse e ritmo. Com essa feature é possível compreender a sonoridade, a tremulação e a afinação do discurso humano, padrões presentes no espectro sonoro que auxiliaram no treinamento do modelo."

___
13. [A Knowledge-Based Recommendation System That Includes Sentiment Analysis and Deep Learning](https://ieeexplore.ieee.org/document/8445585)

> citar como trabalho relacionado

___
14. [Emotion intensity detection for social media data](https://www.semanticscholar.org/paper/Emotion-intensity-detection-for-social-media-data-Mashal-Asnani/b28f0916e14c65af4d5f6ec0a3584251b78dc513)

> pulei

___
15. [Emotion Detection and Analysis on Social Media](https://arxiv.org/abs/1901.08458)


`#fundteo`

"Emotions have also been studied, but in a limited extent, such as by asking specific questions and judging on the basis of replies, or an analysis done only on short one-lined headlines or a few others [1], [2], [3], all of which depended on the manual annotation of the training dataset of a small size and limited scope."

___
16. [The paradoxical role of emotional intensity in the perception of vocal affect](https://www.nature.com/articles/s41598-021-88431-0) -> [VIVAE](https://zenodo.org/record/4066235#.Y2FyG99v-Ul)


`#motiv`

"Vocalizations including laughter, cries, moans, or screams constitute a potent source of information about the affective states of others. It is typically conjectured that the higher the intensity of the expressed emotion, the better the classification of affective information"

<span style="color:green">
"Whether conveyed by the face, body, or voice, expressions of emotion are ubiquitous. The inferred meaning of the expressions is, generally speaking, substantially aligned with the affective content expressed, and it is intuitive to suggest that the stronger the expressed affective state the more clear-cut the inferred emotional meaning. Indeed, a body of research suggests that high-intensity emotion expressions are better ‘recognized’ [1–5]"
</span>

"This generalization has been challenged by the discovery of perceptual ambiguity for facial [10,11] and vocal [12] expressions of peak emotional intensity. In the latter study, vocalizations of extreme positive valence could not be disambiguated from extreme negative valence. Moreover, these authors demonstrated a trend opposite the predicted relation for peak intense positive situations: the reactions of real-life lottery winners were rated more negatively as hedonic intensity (in this case cued by the prize sum) increased. They argue that peak emotion expression is inherently ambiguous and reliant on contextual information [12–14]."

"The research on the ambiguity of intense expressions is intriguing, but key issues lack sufficient evidence to refine our theoretical understanding. The studies on peak emotion elegantly contrast positive and negative affect. As such, one aspect of affective experience (i.e., valence) is hard to differentiate. Valence along with arousal are thought to constitute essential building blocks of coreaffect15,16. Hence, its compromised perceptual representation invites the speculation that peak intense vocalizations do not convey any affective meaning. But it is not known whether arousal, an equally fundamental property of affect, is similarly indistinctive. Moreover, the data raise the question whether individual emotions of the same or opposing valence can be differentiated, or if only peak positive affect is unidentifiable."

"Though valence and arousal are equally fundamental in emotion theoretical frameworks, it is implausible to assume that the human voice does not signal physical activation or arousal in the most extreme instances of emotion. In fact, from an ethological perspective, a perceptual representation of arousal as well as the specific intensity of the emotional state seem essential, even when overall valence and the specific type of emotion cannot be identified. To address specifically the influence of emotional intensity on emotion perception, we use nonverbal vocalizations from a newly developed database, the Variably Intense Vocalizations of Affect and Emotion Corpus (VIVAE)."

___
17. [Human Emotion Recognition: Review of Sensors and Methods ](https://www.mdpi.com/1424-8220/20/3/592) -> [???]()


`#fundteo`

"In the scientific literature are presented numerous attempts to classify the emotions and set boundaries between emotions, affect, and mood [18–21]. From the prospective of automated emotion
recognition and evaluation, the most convenient classification is presented in [3,22]. According to the latter classification, main terms defined as follows: (i) “emotion” is a response of the organism to a particular stimulus (person, situation or event); Usually it is an intense, short duration experience and the person is typically well aware of it; (ii) “affect” is a result of the effect caused by emotion and includes their dynamic interaction; (iii) “feeling” is always experienced in relation to a particular object of which the person is aware; its duration depends on the length of time that the representation of the object remains active in the person’s mind; (iv) “mood” tends to be subtler, longer lasting, less intensive, more in the background, but it can affect affective state of a person to positive or negative direction"

"According to the research performed by Feidakis, Daradoumis and Cabella [21] where the classification of emotions based on fundamental models is presented, exist 66 emotions which can be divided into two groups: ten basic emotions (anger, anticipation, distrust, fear, happiness, joy, love, sadness, surprise, trust) and 56 secondary emotions. To evaluate such a huge amount of emotions, it is extremely difficult, especially if automated recognition and evaluation is required. Moreover, similar emotions can have overlapping parameters, which are measured. To handle this issue, the majority of studies of emotion evaluation focuse s on other classification s [3,21], which include dimensions of emotions, in most cases valence (activation—negative/positive) and arousal (high/low) [23,24], and analyses only basic emotions which can be defined more easily. A majority of researches use variations of Russel’s circumplex model of emotions (Figure 1) which provides a distribution of basic emotions in two-dimensional space in respect of valence and and arousal"

"According to [36,37], each emotion can be evaluated by analyzing five main components of emotion (Behavioral tendencies, physiological reactions, motor expressions cognitive appraisals and subjective feelings) but only the first four can be evaluated automatically and can give indications about the emotional state of an user during an interaction, without interrupting it. Subjective feelings usually evaluated only using self-assessment techniques."

___
18. [Emotion Intensity and its Control for Emotional Voice Conversion](https://arxiv.org/abs/2201.03967)


`#fundteo`

"Previous emotional voice conversion studies mainly focus on learning a feature mapping between different emotion types. Most of them, model the mappings of spectral and prosody parameters with a Gaussian mixture model (GMM) [21], [22], sparse representation [23], or hidden Markov model (HMM) [24]. Recent deep learning methods such as deep neural networks (DNN) [25], [26] and deep bi-directional long-short-term memory network (DBLSTM) [27] have advanced the state-of-the-art. New techniques using generative adversarial network (GAN)-based [28], [29], [30] or auto-encoder-based models [31], [32], [33] make it possible for non-parallel training."

"Emotion intensity can affect our perception of emotions [46]. For example, happy can be perceived as happy or elation, which are similar in voice quality but different in intensity [9]. Thus, correlating the emotion intensity to the loudness of the voice is a rather oversimplification. Emotion intensity can be observed in various acoustic cues, not only in speech energy but also in speech rate and  fundamental frequency [12]. The differences in these cue levels could be larger between different intensities of the same emotion than between different emotions [46]."

`#motiv`

"Below, we summarise the gaps in the literature of emotional voice conversion that we aim to address in this paper. 1) There are very few studies on emotion intensity control, which is crucial to achieving emotional intelligence; 2) Despite the tremendous potential, emotion intensity control is still not a well-explored research direction for emotional voice conversion; 3) There is a lack of focus on modelling prosody style to achieve improved emotion intensity control; 4) Feasibility of using a pre-trained speech emotion recognizer as an emotion supervisor for EVC training poses tremendous potential but is not well understood."

"To model emotion intensity, one of the difficulties is the lack of annotated intensity labels. Inspired by the idea of attribute [93] in computer vision, we regard emotion intensity as an attribute of the emotional speech. Combining the emotion representations with the intensity information allows the framework to jointly learn abundant emotion styles and intensity levels from any emotional speech database."

___
19. [Emotional Intensity Level Analysis of Speech Emotional Intensity Estimation](https://www.esann.org/sites/default/files/proceedings/2021/ES2021-118.pdf)


`#motiv`

"Intensity estimation has a lot of potential applications for human-robot interaction, patient monitoring, security surveillance and entertainment. If it is not possible to read the intensity of emotions during speech input, the possibility that responses given when humans and machines communicate are greatly misunderstood cannot be eliminated. In order to avoid such situations, research on how to better estimate emotional intensity has been conducted."

___
20. [Recognition of Emotion with Intensity from Speech Signal Using 3D Transformed Feature and Deep Learning](https://www.mdpi.com/2079-9292/11/15/2362) -> [???]()


`#intro`

<span style="color:green">
"Speech is the most popular way to communicate with others in daily life and is largely used for emotional expression [1]. Speech can carry two types of information, literal information and relative information [2]. The literal information highlights direct meaning, and relative information means the implicit messages such as emotion contained in the speech [3]. Speech is always a potential source of the emotional state of a person. In the computational intelligence or machine learning (ML) domain, Speech Emotion Recognition (SER) is known as the task of determining and classifying the emotional features of speech. SER has consistently faced challenging ML issues due to the complexity of speech signals [2]."
</span>

`#fundteo`

"The efficiency of emotional features obtained from speech significantly impacts SER performance [3]. Various DL models based on neural networks have been investigated for SER [4], which include Deep Belief Networks (DBN) [3], Convolutional Neural Network (CNN) [1,4], Recurrent Neural Network (RNN) [5] and Long Short-Term Memory (LSTM) network [5]. Prominent existing methods employ different feature ex-
traction and signal transformation methods on speech signals, and then DL methods are applied to the transformed signal for emotion classification."

"A remarkable observation from the existing SER studies is those only considered emotion categorization from speech signals regardless of the intensity that belongs to it [6]. Emotion intensity (e.g., Normal, Strong) for a particular emotional expression (e.g., sad, angry) has a crucial impact. In case of being very sad/angry, a person may fall into serious disruptive activity."

___
21. [Brazilian Portuguese emotional speech corpus analysis](https://www.gov.br/cti/pt-br/publicacoes/producao-cientifica/seminario-pci/xi_seminario_pci-2021/pdf/seminario-2021_paper_29.pdf)


`#fundteo`

"The voice emotion recognition database (VERBO, NETO 2018) is the first speech emotion corpus in Brazilian Portuguese language. This acted database is recorded with 12 professional
Brazilian actors (6 females and 6 males) and contains 5 long sentences, 2 short sentences, 2 questions, and 5 nonsense phrases, summing to 14 phrases, in a way to include all the Portuguese linguistic phonemes. It follows a discrete emotional model containing six basic emotions: anger (167), disgust (167), fear (166), happy (166), sad (167), surprise (167) and seventh one is neutral (167) comprising total 1167 utterances."

> https://thescipub.com/pdf/jcssp.2018.1420.1430.pdf

    "The database was validated by a panel of expert judges and we achieved an agreement rate of 76% using the content validity index and substantial agreement rate of 65% using Fleiss’ Kappa. In addition, an accuracy of 0.76 was achieved and it was possible to observe that the emotions anger and happiness were more easy to recognize showing 0.85 and 0.83 of f1-score, respectively, whereas the disgust and surprise emotions were the most difficult showing 0.67 and 0.68, respectively."

___
22. [END-TO-END SPEECH RECOGNITION APPLIED TO BRAZILIAN PORTUGUESE USING DEEP LEARNING](http://www.pee.ufrj.br/mwg-internal/de5fs23hu73ds/progress?id=ynpPt7kh6WfQgOdd36Ib7avR6tKN6V-l8iTIWXdw74o,&dl)()

> pulei

___
23. [StrengthNet: Deep Learning-based Emotion Strength Assessment for Emotional Speech Synthesis](https://arxiv.org/abs/2110.03156) -> [???]()


`#motiv`

"The emotion strength of synthesized speech can be controlled flexibly using a strength descriptor, which is obtained by an emotion attribute ranking function. However, a trained ranking function on specific data has poor generalization, which limits its applicability for more realistic cases. Emotional speech synthesis (ESS), such as emotional text-to-speech, emotional voice conversion, etc., seeks to generate expressive speech with a desired emotion category. Note that the control of emotion strength in an utterance is the key to emotion rendering. Specifically, the emotion strength of synthesized speech can be controlled flexibly using a predefined strength descriptor."

___
24. [Musical Genre Classification with Convolutional Neural Networks](https://towardsdatascience.com/musical-genre-classification-with-convolutional-neural-networks-ff04f9601a74)

> pulei

___
25. [The circumplex model of affect: An integrative approach to affective neuroscience, cognitive development, and psychopathology](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2367156/)

> leitura particular

___
26. [Russell’s (1980) Circumplex Models](https://psu.pb.unizin.org/psych425/chapter/circumplex-models/) -> [???]()

> leitura particular

___
27. [O afeto sob a perspectiva do circumplexo: evidências de validade de construto](http://pepsic.bvsalud.org/scielo.php?script=sci_arttext&pid=S1677-04712017000200005)


`#fundteo`

"O afeto, para Russell (1980), é compreendido por meio do circumplexo (Figura 1). Suas dimensões são bipolares e ortogonais, sendo nomeadas de valência (prazer ou desprazer) e ativação percebida (alta ou baixa). O circumplexo é uma estrutura ordenada em que todos os testes apresentam um mesmo nível de complexidade e diferem em termos do tipo de habilidade que eles medem. Quando um construto pode ser representado por um circumplexo, sua matriz de correlações apresenta um padrão de correlações fortes perto da diagonal e, conforme as correlações se afastam da diagonal, elas ficam mais fracas, até que voltam a ficar fortes. Esse padrão de correlações repete-se em toda a matriz, e, por isso, pontos próximos no circumplexo são correlacionados fortemente (Guttman, 1954). A dimensão valência está relacionada à codificação do ambiente como prazeroso ou desprazeroso. Para o estímulo em um determinado momento, o sujeito pode atribuir um significado: bom ou ruim; útil ou prejudicial; recompensador ou ameaçador (Barrett, 2006). A ativação, por sua vez, é a dimensão da experiência que corresponde à mobilização ou energia dispensada; ou seja, é representada por um continuum, desde a baixa ativação, representada por sono, até a ativação alta, representada pela excitação (Russell & Barrett, 1999). Estados afetivos que são próximos no circumplexo representam uma combinação similar de valência e ativação percebida; já estados afetivos posicionados diametricamente longe um do outro diferem em termos de valência e ativação (Russell, 1980). Assim, as quatro variáveis alocadas diagonalmente não são dimensões, mas ajudam a definir os quadrantes no espaço do circumplexo (Russell, 1980)."

"Com base nos modelos teóricos analisados, as combinações das dimensões geraram seis categorias: afeto positivo com ativação alta (eufórico, entusiasmado); afeto positivo com ativação moderada (gratificante, satisfeito); afeto positivo com ativação baixa (sereno, calmo); afeto negativo com ativação alta (chateado, em sofrimento); afeto negativo com ativação moderada (miserável, descontente); e afeto negativo com ativação baixa (letárgico, depressivo) (Carroll et al., 1999). Essas dimensões foram posteriormente adaptadas por Yik et al. (2011) em um novo modelo, o 12-PAC (12-Point Affect Circumplex). Nesse modelo, o afeto pode ser mensurado por meio de 12 pontos concernentes às combinações entre valência e ativação."

___
28. [All-in-One: Emotion, Sentiment and Intensity Prediction using a Multi-task Ensemble Framework](https://www.cse.iitb.ac.in/~pb/papers/ieee-toac-sa.pdf)


`#fundteo`

"ny organization does not wish to lose their valuable customers. They can keep track of the emotions and sentiments of their customers over a period of time. If the unpleasant emotions or sentiments are being expressed by a customer on a regular basis, the organization can act in a timely manner to address his/her concerns. On the other hand, if the emotions and sentiments are pleasant, the organization 
can ride on the positive feedback of their customers to analyze and forecast their economic situation with more confidence. The classification of emotions and sentiments into coarse-grained classes does not always reflect exact state of opinion of a user, hence, do not serve the purpose completely. Recently, the attention has been shifted towards fine-grained analysis on the dimensional scale [10], [11], [12], [13], [14]. Arousal or intensity defines the degree of emotion and sentiment felt by the user and often differs on a case-to-case basis. Within a single class (e.g., Sadness) some emotions are gentle (e.g.,  ‘I lost my favorite pen today.’) while others can be severe (e.g., ‘my uncle died from cancer today...RIP’). Similarly, some sentiments are gentler than others within the same polarity, e.g., ‘happy to see you again’ v/s ‘can’t wait to see you again’."

"Following the trends of emotion intensity prediction, researchers have also focused on predicting the intensity score for sentiment [35], [36], [37], [38]. Balahur et al [35] studied the behavior of sentiment intensity for text summarization. Authors in [37] proposed semi-supervised technique that used sentiment bearing word embeddings to produce a continuous ranking among adjectives that share common semantics. In another work [38], authors proposed a stacked ensemble technique for sentiment intensity prediction in financial do main. Traditional techniques, e.g., boosting [39], bagging [40], voting (weighted, majority) [41] etc. are some of the common choices for constructing ensemble [42], [43], [44]. Akhtar et al. [45] proposed an ensemble technique based on Particle Swarm Optimization (PSO) to solve the problem of aspect based sentiment analysis."

___
29. [A Multi-task Ensemble Framework for Emotion, Sentiment and Intensity Prediction](https://arxiv.org/abs/1808.01216)

> pré-print do #28

___
30. [Music emotion recognition based on segment-level two-stage learning](https://link.springer.com/content/pdf/10.1007/s13735-022-00230-z.pdf) -> [???]()

> pulei

___
31. [Emotion Recognition from Speech: An Unsupervised Learning Approach](https://www.atlantis-press.com/journals/ijcis/125945494/view)


`#fundteo`

"Clustering techniques can be inventoried following several criteria, whether they are hierarchical, partition-based, density/neighborhood-based or model-based [8]. Obviously clustering was less used than classification for emotion recognition, since most works deal with labeled databases. However, in a big data context, unsupervised recognition methods can prove more useful, since labeling a huge quantity of expressive speech data would be a tedious and expensive task. For instance, self-organizing maps (SOMs) were used by Szekely et al. to detect emotions in audiobooks [40], based on articulatory features. Also, hierarchical K-means were used by Eyben et al. to detect emotions in a corpus dedicated for expressive speech synthesis, using prosodic and acoustic features [31]. It should be noted that, since clusters do not necessarily correspond to classes, a “vector quantization” approach is usually used, whereby the number of clusters is overestimated, and subsequently the detected clusters are grouped into classes; methods based on this type of approach can even be competitive with entirely supervised approaches, with theoretical guarantees [41], and can be easily used in a semi-supervised context (partially labeled data). Experiments have shown that in clustering the choice of features is more important for the final accuracy than in classification, where the generalization power of the classifier and the direct minimization of a loss function could mask the irrelevance or the aberrance of some features"

___
32. [Deep Learning Techniques for Speech Emotion Recognition, from Databases to Models](https://www.mdpi.com/1424-8220/21/4/1249)


`#fundteo`

"Due to the importance of SER in human–computer interaction and the development of artificial intelligence systems, there are multiple other recent publications and surveys on SER. In this section, we review the most recent studies related to the current work. In 2018, Swain et al. [49] reviewed studies between 2000 and 2017 on SER systems based on three perspectives: database, feature extraction, and classifiers. The research has an extensive section on databases and feature extraction; however, only traditional machine learning methods have been considered as classifying tool, and the authors are regretting neural networks and deep learning approaches. A year after, Khalil et al. [50] reviewed discrete approaches in SER using deep learning. Several deep learning approaches, including deep neural networks (DNNs), convolutional neural networks (CNNs), recurrent neural networks (RNNs), and autoencoder, have been mentioned along with some of their limitations and strengths in the study. However,
the research is not addressing the accessible approaches to overcome weaknesses. Very recently, Anjali et al. [51] published a review as a summary of speech emotion detection methods. A brief discussion of various features used in speech emotion recognition and review of methods used for this purpose from 2009 to 2018 has been provided in the re-search. The drawback of the paper is the depth of analysis. Yet, it can be considered a start point. In 2020, Basu et al. [52] published a brief review on the importance of speech emotion datasets and features, noise reduction; ultimately, they analyze the significance  of different classification approaches, including SVM and HMM. The strength of the research is the identification of several features related to speech emotion recognition; however, its weakness is the leak of more modern methods’ investigation and briefly mentions convolutional and recurrent neural networks as a deep learning method. In contributions to the other published surveys, this research provides a thorough study of significant databases and deep learning discrete approaches in SER. The reason for not focusing on the other older techniques is recent progress in neural networks and, more specifically, deep learning. Based on the best of our knowledge, this study is the first survey in SER focusing on deep learning along with unified experimental results that proposes approaches to enhance the available methods’ results."

> Emotional Speech Databases comparison

> Emotion Recognition Methods evolution/history

"Transfer learning can overcome the cross-domain’ challenge of SER, i.e., test corpora does not match train corpora. Song et al. [90] utilize transfer learning in cross-corpus speech emotion recognition task practicing dimension reduction and Maximum Mean discrepancy embedding optimization to get two adjacent latent feature spaces for the source and target corpora and SVM as classifier method. The experiment has been done utilizing EMO-DB with five emotion categories as source corpus and a Chinese emotion dataset with the same emotion categories as the test corpus"

"In older studies, most of the methods were based on signal processing and traditional machine learning methods such as SVM. However, more recently, researchers are focusing on deep learning and neural networks improvement, which is directly related to the progress and advancement of hardware and software that allows researchers to employ and tune sophisticated networks such as LSTM, GAN, and VAE."

> A brief comparison of all the algorithms reviewed, containing features and methods

"The surge of new research on convolutional neural networks shows that they are capable of better solving the problem of emotion recognition by having higher low-level and short-term discriminative capabilities. The incorporation of LSTM networks and the introduction of deep convolutional LSTM structures has helped to take the solution to a new level and to give the network long-term memory to be able to identify long-term paralinguistic patterns. They have also shown higher capabilities of speaker-independent emotion recognition"

`#motiv`

"Automatic SER helps smart speakers and virtual assistants to understand their users better, especially when they recognize dubious meaning words. For example, the term “really” can be used to question a fact or emphasize and stress out a statement in both positive and negative ways. Read the following sentences in different ways: “I really liked having that tool.” The same application can help translate  from one language to another, especially as other languages have different ways of projecting emotions through speech [7]. SER is also beneficial in online interactive tutorials and courses. Understanding the student’s emotional state will help the machine decide how to present the rest of the course contents [8]. Speech emotion recognition can also be very instrumental in vehicles safety features. It can recognize the driver’s state of mind and help prevent accidents and disasters [8]. Another related application is in therapy sessions; by employing SER, therapists will understand their patients’ state and possibly underlying hidden emotions as well [9]. It has been proven that in stressful and noisy environments like aircraft cockpits, the application of SER can significantly help to increase the performance of automatic speech recognition systems [10]. The service industry and e-commerce can utilize speech emotion recognition in call centers to give early alerts to customer service and supervisors of the caller’s state of mind [11]."

___
33. [A voice-based real-time emotion detection technique using recurrent neural network empowered feature modelling](https://link.springer.com/content/pdf/10.1007/s11042-022-13363-4.pdf) -> [???]()

> pulei

___
34. [UNSUPERVISED LEARNING APPROACH TO FEATURE ANALYSIS FOR AUTOMATIC SPEECH EMOTION RECOGNITION](http://labsites.rochester.edu/air/publications/eskimez2018unsupervised.pdf) -> [???]()


`#intro`

"Emotions are a vital part of social interactions. Designing computational models to recognize emotions is key to an automatic understanding of social interactions. In recent years, researchers have developed automatic emotion recognition systems using different data modalities, including physiological signals [1], facial expressions and body gestures [2], and speech [3]."

`#fundteo`

"The scarcity of emotional speech data is a bottleneck of developing automatic speech emotion recognition (ASER) systems. One way to alleviate this issue is to use unsupervised feature learning techniques
to learn features from the widely available general speech and use these features to train emotion classifiers."

"One way to alleviate the data lacking issue is to transfer knowledge learned from unlabeled data or data in other related tasks (source tasks) to the task at hand (target task) [5]. One technique is unsupervised feature learning, which does not utilize the label information but aims to learn robust features that can capture the intrinsic structures of the data. These features are also often discriminative to train better classification models for the target task [6,7]. For ASER, the most natural and available data sources are general speech."

___
35. [Unsupervised Feature Learning for Speech Emotion Recognition Based on Autoencoder](https://www.mdpi.com/2079-9292/10/17/2086)


`#fundteo`

"Applying the unsupervised learning method into speech features and implemented speech emotion recognition. We proposed to adapt multiple autoencoders for feature extraction and utilize a convolutional  neutral network for classification, which were combined to analyze the influence on speech emotion recognition result. "

___
36. [Speech Emotion Recognition Using Unsupervised Feature Selection Algorithms](https://www.semanticscholar.org/paper/Speech-Emotion-Recognition-using-Unsupervised-Bandela-Kumar/e8d637f9f02a8c4849e5af09e6b9f9edf5e76eb9)


`#fundteo`

"Feature selection techniques can be categorized based on labelling of the data as supervised, unsupervised and semi-supervised. In supervised feature selection, the data is labelled feature evaluation process. If the data is huge, labelling of the data is costly and a tedious task. Unsupervised feature selection can overcom e these drawbacks of supervised approaches. But this is more difficult than supervised ones since it does not have labelled data and still its result can be good even without any prior knowledge. The evaluation of feature selection meth ods can be further classified into four types, i.e., filter, wrapper, embedded, hybrid and ensemble feature selection"

___
37. [Survey of Deep Representation Learning for Speech Emotion Recognition](https://www.semanticscholar.org/paper/Survey-of-Deep-Representation-Learning-for-Speech-Latif-Rana/368e0844bbd3feb5ab17a271ad1663ca5a6fb7e7)


`#fundteo`

> citar como trabalho relacionado

Model | Characteristics
----- | ---------------
DNNs    | Good for learning a hierarchy of representations. They can learn  invariant and discriminative representations. Features learntby DNNs are more generalised compared to traditional methods.
CNNs    | Good for learning both low-level as well as high-level representation from emotional speech. RNNs Good for sequential modelling. They can learn temporal structures from speech suitable for emotion classification.
AEs     | Powerful unsupervised representation learning models that  encode the emotional speech data in sparse and compressed representations.
VAEs    |Stochastic variational inference and learning model. Popular in learning disentangled emotional representations from speech.
GANs    | A Game-theoretical framework that is useful for data generation and is robust to overfitting. They can learn disentangled representations that are very suitable for SER.
"LSTM/GRU-RNNs combined with CNNs are very popular and suitable for capturing emotional attributes in a supervised way."

"Emotions are context-dependent, and Transformers can better capture temporal contexts compared to RNNs. This encourages SER researchers to utilise Transformers in their studies."

> Review of different SER databases

> Comparing attributes of different deep representation learning techniques.

___
38. [Emotion classification from speech signal based on empirical mode decomposition and non-linear features](https://d-nb.info/1232071765/34)

> pulei

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
