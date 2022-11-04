# preproj bol22014

<span style="color:green"></span>

- 1. Introdução

Reconhecimento de emoção em fala é uma linha de pesquisa dentro da área de Inteligência Artificial (IA), dada por tarefas de reconhecimento e classificação da reação afetiva de um indivíduo [H]. Este estudo sobre emoções, sua interpretação e sua representação no contexto computacional formam uma área de estudos denominada por Computação Afetiva [I].

Sejam transmitidas pelo rosto, corpo ou voz, as expressões de emoção são onipresentes. O sentido inferido das expressões está, em geral, substancialmente alinhado com o conteúdo afetivo expresso, sendo intuitivo sugerir que quanto mais forte o estado afetivo expresso mais nítido o sentido emocional inferido [K].

Antes mesmo de conhecer as palavras, ou de conseguir pronunciá-las corretamente, já empregamos a fala como uma forma primária de comunicação e expressão de emoções [A]. Independente da idade, os indivíduos da espécie humana expressam emoções comuns (e.g.: alegria, raiva, medo). Entretanto, idiomas distintos podem produzir diferenças na forma como essas emoções são expressas em matéria de tom de fala e voz [B] [C].

Ao nos comunicarmos utilizando a voz [D], além de decodificar e interpretar o valor presente na mensagem, também decodificamos e interpretamos outros elementos (e.g.: Entonação e ritmo) para compreender a mensagem de maneira completa. Não é difícil perceber que um "Bom dia!" sorridente e efusivo seria interpretado de forma quase que diametralmente oposta de um "Bom dia..." dito de forma lenta e com pouca energia. Portanto, reconhecemos a emoção na fala, e essa emoção é uma variável para interpretar o que foi dito.

A fala é a maneira mais popular de se comunicar com os outros na vida diária e é amplamente usada para expressão emocional [E]. Pode transportar dois tipos de informação: Informação literal e informação relativa [F]. A informação literal destaca o significado direto e informação relativa significa as mensagens implícitas, como a emoção contida na fala [F]. A fala é sempre uma fonte potencial do estado emocional de uma pessoa. No domínio do Aprendizado de Máquina (Machine Learning, ML), o Reconhecimento da Emoção da Fala (Speech Emotion Recognition, SER) é conhecido como a tarefa de determinar e classificar as características emocionais da fala. SER tem enfrentado consistentemente problemas desafiadores de ML devido à complexidade dos sinais de fala [F].

Emoções têm papel importante na comunicação humana. No contexto natural, utilizamos várias informações do ambiente para conseguirmos detectar emoções em suas expressões. Assim, é seguro afirmar que a fala é um dos elementos relevantes ao se tentar observar quais emoções estão sendo expressadas por um interlocutor. Nesse contexto, existem trabalhos que afirmam que emoções são expressas diferentemente pela fala humana e que ouvintes são capazes de corretamente inferir o estado emocional de um interlocutor apenas com a informação da voz [J].

Modelos estatísticos e de ML, vêm sendo um dos possíveis caminhos para realizar tarefas de reconhecimento de emoção na fala desde o final do século XX [L] [M]. Embora, conseguir identificar o estado emocional de um sujeito não seja uma tarefa trivial, pois demanda uma capacidade de percepção apurada. Em seu contexto original, os interlocutores utilizam várias informações visuais, auditivas, semânticas e metalinguísticas [N] para determinar qual emoção a fala de uma pessoa invoca, o que torna a tarefa bastante complexa e propensa a erros para o contexto da IA.

Ademais, existem trabalhos que demonstram que é possível inferir a emoção expressada por uma representação digital de uma fala, com diferentes técnicas de inteligência artificial [O] [P] [Q], bem como a intensidade de uma emoção na voz [K]. Assim, são confirmadas as suposições importantes para este trabalho: i. É possível inferir o estado emocional de um interlocutor apenas com a informação da fala; ii. é possível solucionar a tarefa de reconhecimento de emoção na voz por técnicas de IA; iii. é possível inferir um valor para quantificar a intensidade de dada emoção na fala do interlocutor.

- 1.1 Justificativa: Argumentação sobre a relevância teórica e prática da pesquisa.

Pesquisando trabalhos científicos relacionados conseguimos encontrar diversas publicações. Artigos propondo modelos [T] e arquiteturas para SER já no ano de 2005, _reviews_ [R] e _surveys_ [S] comparando e detalhando tanto modelos de classificação quanto as bases de dados (_datasets_) utilizadas para treinar e validar os modelos das publicações.

Tornando a pesquisa mais específica, buscando por trabalhos que envolvam SER para a língua portuguesa (_PT-BR_), vamos perceber que o primeiro dataset em português brasileiro foi publicado em 2018: VERBO [V] [U].

Para a proposta deste trabalho, que é de tentar lidar não só com a emoção, mas tentar quantificar a intensidade da emoção do interlocutor falante de português, não foram encontrados nenhum trabalho relacionado e nenhuma base de dados - com anotações relativas a intensidade - no idioma desejado.

Assim, este trabalho se propõe a inovar, pesquisando técnicas para encontrar uma forma de inferir a intensidade da emoção em uma sentença falada. Entretanto, não partirá do zero, uma vez que já existem abordagens consolidadas para lidar com dados de forma semi-supervisionada e não supervisionada [W] que podem ser utilizadas com ponto de partida ou para estudo comparativo.

O resultado potencial deste trabalho poderia ser aplicado das seguintes formas, dentre outras: i. Melhora na interpretação na entrada de dados (input) e da fidelidade das respostas (output) de assistentes virtuais; ii. Encaixar a solução numa arquitetura para canais de atendimento, vindo a fornecer uma melhor experiência do usuário (User Experience, UX); iii. Combinar a inferência da intensidade da emoção com outros tipos de solução de classificação de IA para obter resultados mais completos, complexos e fidedignos [X]; iv. Criar um produto comercial white label para conversação mediada por IA [Y]; v. Tentar criar perfis comportamentais para funcionários e clientes, criando um emparelhamento otimizado das partes para melhorar a experiência, podendo ocasionar mais vendas de produtos financeiros; vi. Criando um novo dataset para futuras produções científicas.

- 1.2 Alinhamento do tema às Estratégias Corporativa do BB.

Com o apoio de outras tecnologias, como Internet das Coisas, Big Data, Machine Learning, Business Intelligence, a IA tornou informações acessíveis e automatizou processos que hoje são aplicados a diferentes áreas do cotidiano, como carros autônomos e drones que transportam pessoas, sem precisar da interferência humana. [https://intra.bb.com.br/artemis/noticia/detalhar/f7f48e4edd1c3432a60745f30f42d44588922df0d74f803882a74ca46fd23c03]

Metaverso: O Gartner define um Metaverso como um espaço coletivo virtual 3D compartilhado, criado pela convergência da realidade física e digital virtualmente aprimorada. Um Metaverso é persistente, proporcionando experiências imersivas aprimoradas. O Gartner espera que um Metaverso completo seja independente de dispositivo e não seja de propriedade de um único fornecedor. Terá uma economia virtual própria, habilitada por moedas digitais e tokens não fungíveis (NFTs). Até 2027, o Gartner prevê que mais de 40% das grandes organizações em todo o mundo usarão uma combinação de Web3, Nuvem, Realidade Aumentada e gêmeos digitais em projetos baseados em Metaversos destinados a aumentar a receita.

Superaplicativos: Um superaplicativo combina os recursos de um aplicativo, uma plataforma e um ecossistema em um único aplicativo. Ele não apenas possui seu próprio conjunto de funcionalidades, mas também fornece uma plataforma para terceiros desenvolverem e publicarem seus próprios miniaplicativos. Até 2027, o Gartner prevê que mais de 50% da população global serão usuários ativos diários de vários superaplicativos.

“Embora a maioria dos exemplos de superaplicativos sejam aplicativos móveis, o conceito também pode ser aplicado a aplicativos clientes de desktop, como Microsoft Teams e Slack, com a chave sendo que um superaplicativo pode consolidar e substituir vários aplicativos para uso de clientes ou funcionários”, disse Karamouzis. .

Adaptive AI: Os sistemas de IA adaptável visam treinar continuamente os modelos e aprender em ambientes de tempo de execução e desenvolvimento com base em novos dados para se adaptar rapidamente às mudanças nas circunstâncias do mundo real que não estavam previstas ou disponíveis durante o desenvolvimento inicial. Eles usam feedback em tempo real para mudar seu aprendizado dinamicamente e ajustar as metas. Isso os torna adequados para operações em que mudanças rápidas no ambiente externo ou metas corporativas em constante mudança exigem uma resposta otimizada.

Digital Immune System: 76% das equipes responsáveis ​​por produtos digitais agora também são responsáveis ​​pela geração de receita. Os CIOs estão procurando novas práticas e abordagens que suas equipes possam adotar para fornecer esse alto valor comercial, além de mitigar riscos e aumentar a satisfação do cliente. Um sistema imunológico digital fornece esse roteiro. Digital Immune System combina insights baseados em dados sobre operações, testes automatizados e extremos, resolução automatizada de incidentes, engenharia de software nas operações de TI e segurança na cadeia de suprimentos de aplicativos para aumentar a resiliência e a estabilidade dos sistemas. O Gartner prevê que, até 2025, as organizações que investirem na criação de Digital Immune System reduzirão o tempo de inatividade do sistema em até 80% – e isso se traduz diretamente em maior receita.

[https://intra.bb.com.br/artemis/noticia/detalhar/8674ba8ec7d432ad62dc81f966ad740de5ae1612804a027bc85d600d40b81f5a]

O Banco do Brasil está entre os nove finalistas de mais um reconhecimento internacional de mercado: o Qorus-Accenture Banking Innovation Awards. Na edição deste ano, fomos selecionados nas categorias Reimaginando a experiência do cliente com a solução Open Finance: Consentimento no WhatsApp e Marketing Digital & Vendas com a solução Brablox: Banco do Brasil no Metaverso do Roblox.

[https://intra.bb.com.br/artemis/noticia/detalhar/136dddc16fa47042a4d534dcf9dfeeb2a13011955f6cea3a992eb3eb873e1bbf]

Sabe aquele momento tenso durante um atendimento, com o cliente na sua frente, em que chega num determinado assunto ou situação que você não sabe a resposta ou não consegue localizar na IN?

Isso acontece no dia a dia de quem está na linha de frente do atendimento nas nossas agências. E o que você faz nessas horas?#Keepcalm ou no nosso bom português: mantenha a calma.

Atento ao fato de que a preferência por atendimento de texto está se tornando um hábito devido a sua facilidade e agilidade, o BB desenvolveu uma ferramenta que permite que os funcionários tirem suas dúvidas sobre cartões e demandas de suporte técnico via chat.

Agora você pode contar com suporte especializado no assunto de forma ágil e prática através de chat na plataforma BB. Esse tipo de atendimento já era disponível antes, porém restrito a assuntos relacionados a cartão e por telefone no número 4004 3780.

Basta acessar a Plataforma BB (Negócios), clicar no ícone do chat e na opção “Atendimento ao Funcionário” e aguardar seu atendimento.

[https://intra.bb.com.br/artemis/noticia/detalhar/01f2d1216052716a128af2cae1c07edc090315a27e08549982d2a0037d2947f5]

Já percebeu como algumas plataformas de streaming e apps de música parecem saber exatamente o que você quer ver/ouvir? Parece mágica, mas na verdade são estudos e ferramentas que fundamentam tais indicações. E se houvesse uma recomendação de produtos para oferecer ao nosso cliente? Pois agora a rede Setor Público tem essa ferramenta à disposição. Em uma construção que une análise de dados e aprendizado de máquina, o Banco do Brasil apresenta nesta quinta-feira, 25, o NBO (Next Best Offer), ferramenta que indica a Melhor Oferta ao cliente.

A solução traz inúmeras vantagens, desde a personalização das ofertas indicando os clientes com maior chance de contratação até a identificação de produtos que têm baixa adesão na carteira de clientes.

Inicialmente as informações estão disponíveis no relatório “Indução Melhor Oferta”, no Portal da Rede. Conhecido como “O Pulo do Gato”, o relatório ajuda a direcionar os esforços da equipe e é importante ferramenta de apoio no atingimento de indicadores do Conexão e demais desafios.

“O modelo analítico captura dados comportamentais de consumo de produtos no BB, analisa e compara com outros clientes de perfil semelhante, para identificar os padrões. Se no mesmo grupo de análise, a maioria do público contratou um tipo de serviço, o modelo calcula a propensão e indica esse mesmo produto para os demais”, explica Anna Carolina Santos, assessora de TI da UAN.

[https://intra.bb.com.br/artemis/noticia/detalhar/2020297934cce418a5dccf875394bbe4a538a0777877d9f0946c81c4a6c63dba]

A Política de Relacionamento com os Clientes é uma declaração do compromisso do BB com o cliente para a construção de um relacionamento pautado por valores como ética, responsabilidade, transparência e diligência, propiciando a convergência de interesses e a consolidação de uma imagem institucional de credibilidade, segurança e competência. “A Política é uma forte aliada na busca do objetivo de ser o banco mais relevante para o cliente, proporcionando a melhor experiência e para a realização de negócios e resultados sustentáveis e rentáveis”, reforça Charlene Fiusa, gerente de soluções da Dicoi.

[https://intra.bb.com.br/artemis/noticia/detalhar/13d8ca4645360ad5650ae7c97ee271cef0c25dd089ffb8b5514116dbb83c02f0]

Durante a visita, quando ele começou a reclamar que o BB é complicado, seu irmão, Adalberto, logo interveio dizendo o quanto o BB é bom, e que o nosso atendimento está voltado a atender as necessidades do cliente. Isso foi a abertura para falarmos dos negócios. As operações que seriam renovadas com o concorrente foram fechadas com o BB, ali mesmo no encontro. Eu estava que não cabia em mim de contentamento.
Eles queriam construir um armazém e uma fábrica de ração na Fazenda Segredo, onde trabalham com lavouras irrigadas, gado de corte e confinamento, plantam o milho safrinha exclusivamente para ração, e também engorda dos animais lá criados. Até o esterco é aproveitado e utilizado para geração de energia elétrica.

[https://intra.bb.com.br/artemis/noticia/detalhar/aaa8ad27865b27c08209ca34425a0fc185e7f8c6bbad091453d81f04b5cbea10]


Realidade virtual.

O assistente de voz (Alexa) já permite conversas sobre conta digital, cashback e open finance. ALém de consultas sobre saldo e cartão de crédito. Para ser atendito, basta dizer:  "Alexa, abrir o Banco do Brasil"..

O espaço de inovação, que faz parte do programa Lentes, foi inaugurado na última sexta, em um evento que contou com a presença do presidente do BB, Fausto Ribeiro e outros membros do Conselho Diretor.

LENTES: Laboratório Experimentação Novas TEcnologiaS
    - Ativação: Experientar alternativas de aplicação em casos de negócio
    - Conexão: Conectar parceiros internos e externos para viabiliar novos negócios

[https://intra.bb.com.br/artemis/noticia/detalhar/a97ded6bd1cab9deae72c4fd529d7d79c138d55ffff72947748bc1f7e6911fa5]


Entendendo o dado como um ativo estratégico torna-se fundamental promover a cultura data driven no Banco e é um dos pilares da atuação da Unidade. O acompanhamento da evolução da maturidade analítica nas diversas unidades se sobressai num momento em que o uso de dados é  notadamente reconhecido como essencial para uma gestão sustentável, tanto  no apoio ao processo de tomada de decisão quanto no entendimento e melhoria da experiência do cliente, promovendo a geração de valor com o uso de inteligência analítica.

A liderança, como conectora entre os negócios e os times técnicos, tem um papel crucial para o sucesso de qualquer estratégia de analytics, pois o líder analítico deve desenvolver habilidades (soft skills) e ser capaz de compreender e disseminar os conceitos, métodos e melhores práticas para orientação de estratégias de dados e aceleração da cultura analítica.

Neste movimento de sensibilização o Banco do Brasil, em parceria com o Instituto Cappra, iniciou em 2020 um programa de aculturamento em analytics nas unidades estratégicas, voltado para a formação de líderes analíticos, onde todas as unidades estratégicas foram contempladas com vagas de treinamento personalizado para o BB, cujo público-alvo são os gerentes executivos e de soluções.

[https://intra.bb.com.br/artemis/noticia/detalhar/44bb23e6bc99e17e4fcce3aae6a5af17d17a44524e0a072a3d80ff9be7228cc0]


Vantagens de um atendimento de qualidade
- Retenção do Cliente;
- Melhoria da experiência do cliente;
- Diferencial competitivo;
- Melhoria do NPS;
- Conversão em negócios.

[https://intra.bb.com.br/artemis/noticia/detalhar/bd9691f630e477e91be1a17982a56068363d65dd8fe43ef7bd85651f91df634f]


Ressaltou que “cuidar do que é valioso para as pessoas” já foi incorporado à nossa cultura e que o nosso novo propósito propõe a sua evolução. Afirmou que “Ser próximo e relevante na vida das pessoas em todos os momentos” passa a ser nossa referência para os próximos anos e que, assim como o anterior, tem todo o potencial para ser igualmente integrado ao nosso jeito de ser.

A presidente do Conselho de Administração, Iêda Cagni, lembrou que “é a dedicação de todos nós que coloca o Banco do Brasil como protagonista na construção do futuro, e cada um de nós é essencial para os objetivos que estamos traçando. Não tenho dúvidas de que a equipe do Banco do Brasil, que é sabidamente capacitada, que faz parte de uma empresa com um nível extraordinário de governança, que desconheço em qualquer outra no Brasil, sabe onde precisa chegar. Isso garante o sucesso de qualquer estratégia”.

[https://intra.bb.com.br/artemis/noticia/detalhar/1cc86f15b2846d22d76815d7e4e5c4fc340ea39bcb9fa52b8ed4a73014673b2e]

Ser próximo e relevante na vida das pessoas em todos os momentos

Assim como em qualquer relacionamento, é preciso haver conversa, convivência e respeito de ambas as partes. O mesmo deve acontecer quando o assunto é relacionamento ao cliente que deve acontecer de forma genuína. 

Com a mudança de propósito, buscamos expandir o cuidado com aquilo que é valioso para as pessoas, manifestado no propósito anterior e que já está consolidado e incorporado à nossa cultura e ao nosso cotidiano.

[https://intra.bb.com.br/artemis/noticia/detalhar/f0936e03e5bd6e18e03d02bf524555b6c3837206c58fb2ea61bb6ad6afa38c61]

BB é destaque no evento "Tecnologia Bancária"

Estamos começando um movimento em que uma área serve a outra. Com essa integração, aceleramos a velocidade com a qual desenvolvemos nossas soluções. Também temos solução em lowcode que ajuda todas as áreas do Banco a desenvolver sem precisar de tecnologia, o que desonera o setor de TI. Além disso, temos um movimento grande direcionado a cloud, com mais de 4 mil aplicações rodando até o fim do ano, e o Lentes, programa de inovação com vários laboratórios vinculados tratando de novas tecnologias, como 5G e Realidade Aumentada, para os funcionários entenderem como aquela tecnologia pode potencializar seu produto e serviço.

“Estamos trabalhando governança de dados, o que garante segurança e qualidade de dados para ser assertivo com o cliente. Não existe nenhuma área do Banco que não tome decisãso orientada a dados. Quando o banco de varejo entende que pode utilizar inteligência analítica, fazemos entregas melhores e ajudamos o cliente a ter mais rentabilidade”,

"O BB tem investido em soluções de biometria e aquisições de ferramentas de proteção e identificação do usuário o dispositivo para evitar fraudes, mas o mais dificil é evitar a engenharia social, porque é o próprio cliente que cai no golpe. Estamos fazendo campanhas de comunicação mais fortes para educar a sociedade dos riscos do mundo virtual. Também lançamos um game de segurança digital com situações de golpe corriqueiras para que usuários possam ver se estão preparados para responder a tentativas de ataques, além mostrar em nossas redes sociais como o criminoso virtual age”


[https://intra.bb.com.br/artemis/noticia/detalhar/75f6f0e7ea8248ce54bc6eafd058a32e43beeea59839c9c2bb10ced90d5d386c]



Sustentabilidade está no nosso DNA. Metaverso somos atuantes. Nosso app tende a ser cada vez mais um superaplicativo. IA, observabilidade, nuvem e wi-fi são tecnologias que estão cada vez mais disponíveis. E através de engenharia de plataforma.

Objetivo agora é não apenas aplicarmos, mas sermos protagonistas

Sabendo que uma das estratégias corporativas é ser o Banco com a plataforma de negócios e serviços mais relevantes para o cliente, proporcionando a melhor experiência, a proposta deste trabalho vai diretamente de encontro à essa ideia.

> https://behavioralsignals.com/

> Pesquisar o alinhamento na intranet e com Esio.






- 1.3 Apresentação geral das principais questões a serem investigadas (pergunta da pesquisa)
- 1.4 Objetivos Específicos
- 1.5 Objetivo Geral

___
- 2. Referencial teórico
- 2.1 Fundamentação teórica do tema (incluir uma revisão dos principais conceitos que fundamentam o tema e priorizar a literatura atualizada – últimos 5 anos 

___
- 3. Procedimentos metodológicos
- 3.1 Delineamento do estudo.
- 3.2 Participantes
- 3.3 Procedimentos de coleta de dados com definição de onde será realizada a pesquisa no Banco do Brasil. 
- 3.4 Instrumentos utilizados
- 3.5 Procedimentos de análise de dados.
- 3.6 Procedimentos éticos
- 3.7 Resultados esperados
- 3.8 Descrição dos resultados e das contribuições práticas da pesquisa, tanto para o funcionário, quanto para o Banco do Brasil.

___
- 5. Cronograma e orçamento
- 5.1 Identificação das principais etapas e atividades a serem realizadas durante a pesquisa, bem como de suas datas de conclusão

___
6. Referências bibliográficas
```
[A] P. Lieberman, “The evolution of human speech: Its anatomical and neural bases” Current anthropology, vol. 48, no. 1, pp. 39–66, 2007.
[B] C. Kramsch, “Language and culture,” AILA review, vol. 27, no. 1, pp. 30–55, 2014.
[C] E. Sapir, Language: An introduction to the study of speech. Harcourt, Brace, 1921
[D] CASTRO, Sara de. "Elementos da comunicação"; Brasil Escola. Disponível em: https://brasilescola.uol.com.br/redacao/elementos-presentes-no-ato-comunicacao.htm. Acesso em 04 de novembro de 2022.
[E] Sahidullah, M.; Saha, G. Design, analysis and experimental evaluation of block based transformation in MFCC computation for
speaker recognition. Speech Commun. 2012, 54, 543–565.
[F] Garrido, M. The Feedforward Short-Time Fourier Transform. IEEE Trans. Circuits Syst. II Express Briefs 2016, 63, 868–872.
[G] Angadi, S.; Reddy, V.S. Hybrid deep network scheme for emotion recognition in speech. Int. J. Intell. Eng. Syst. 2019, 12, 59–67.
[H] Moataz El Ayadi, Mohamed S Kamel e Fakhri Karray. “Survey on speech emotion recognition: Features, classification schemes, and databases”. Em: Pattern Recognition 44.3 (2011), pp. 572–587
[I] Stuart Russell e Peter Norvig. “Artificial intelligence: a modern approach”.
[J] Klaus R Scherer. “Expression of emotion in voice and music”. Em: Journal of voice
9.3 (1995), pp. 235–248.
[K] Holz, N., Larrouy-Maestri, P. & Poeppel, D. The paradoxical role of emotional intensity in the perception of vocal affect. Sci Rep 11, 9663 (2021). https://doi.org/10.1038/s41598-021-88431-0
[L] Frank Dellaert, Thomas Polzin e Alex Waibel. “Recognizing emotion in speech”.
Em: Proceeding of Fourth International Conference on Spoken Language Processing.
ICSLP’96. Vol. 3. IEEE. 1996, pp. 1970–1973.
[M] Oh-Wook Kwon et al. “Emotion recognition by speech signals”. Em: Eighth European Conference on Speech Communication and Technology. 2003.
[N] Klaus R Scherer. “Expression of emotion in voice and music”. Em: Journal of voice
9.3 (1995), pp. 235–248.
[O] Yixiong Pan, Peipei Shen e Liping Shen. “Speech emotion recognition using support
vector machine”. Em: International Journal of Smart Home 6.2 (2012), pp. 101–
108.
[P] Kun Han, Dong Yu e Ivan Tashev. “Speech emotion recognition using deep neural
network and extreme learning machine”. Em: Fifteenth annual conference of the
international speech communication association. 2014.
[Q] Kun-Yi Huang et al. “Speech emotion recognition using deep neural network considering verbal and nonverbal speech sounds”. Em: ICASSP 2019-2019 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE.
2019, pp. 5866–5870.
[R] R. A. Khalil, E. Jones, M. I. Babar, T. Jan, M. H. Zafar and T. Alhussain, "Speech Emotion Recognition Using Deep Learning Techniques: A Review," in IEEE Access, vol. 7, pp. 117327-117345, 2019, doi: 10.1109/ACCESS.2019.2936124.
[S] Abbaschian, B.J.; Sierra-Sosa, D.; Elmaghraby, A. Deep Learning Techniques for Speech Emotion Recognition, from Databases to Models. Sensors 2021, 21, 1249. https://doi.org/10.3390/s21041249
[T] Lin, Y.L.; Wei, G. Speech emotion recognition based on HMM and SVM. In Proceedings of the 2005 International Conference on Machine Learning and Cybernetics, Guangzhou, China, 18–21 August 2005; Volume 8, pp. 4898–4901
[U] TORRES NETO, José R. et al. VERBO: voice emotion recognition database in portuguese language. Journal of Computer Science, v. 14, n. 11, p. 1420-1430, 2018Tradução. Disponível em: http://dx.doi.org/10.3844/jcssp.2018.1420.1430. Acesso em: 04 nov. 2022.
[V] Neelakshi Joshi. "Brazilian Portuguese emotional speech corpus analysis". X Seminário em TI do PCI/CTI. 2021. Disponível em: https://www.gov.br/cti/pt-br/publicacoes/producao-cientifica/seminario-pci/xi_seminario_pci-2021/pdf/seminario-2021_paper_29.pdf. Acesso em 04 de novembro de 2022.
[W] S. E. Eskimez, Z. Duan and W. Heinzelman, "Unsupervised Learning Approach to Feature Analysis for Automatic Speech Emotion Recognition," 2018 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), 2018, pp. 5099-5103, doi: 10.1109/ICASSP.2018.8462685.
[X] Liu, Rui, et al. "Accurate Emotion Strength Assessment for Seen and Unseen Speech Based on Data-Driven Deep Learning." arXiv preprint arXiv:2206.07229 (2022).
[Y] Behavioral Signals. Disponível em: https://behavioralsignals.com/ai-mediated-conversations-case-study/. Acesso em 04 de novembro de 2022.
[Z]
[A1]
[B1]
[C1]
[D1]
[E1]
[F1]
[G1]
[H1]
[I1]
[J1]
[K1]
[L1]
[M1]
[N1]
[O1]
[P1]
[Q1]
[R1]
[S1]
[T1]
[U1]
[V1]
[W1]
[X1]
[Y1]
[Z1]
```
___
7. Sugestão de livro para ajudar na elaboração do projeto
- i. Goodfellow et al. Deep Learning. An MIT Press book. 2016. Disponível em: https://www.deeplearningbook.org/
