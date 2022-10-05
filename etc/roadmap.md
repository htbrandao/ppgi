# # Abordagens:

- semáforo while true
- unsupervised para agrupamento
  - modelo Circumplexo de Russel

# # Roadmap

- 1 - acessar os dados  <!-- resolver o #2 primeiro? -->
 
- 2 - pesquisar referências para escolher um framework de labeling
  - 2.1 - avaliar viabilidade do framework e fazer personalizações, caso seja necessário **e** possível
  - 2.2 - definir prazo e framework para labeling <!-- questionário para endossar escolha? -->
    - 2.2.1 - criar uma, duas ou mais frentes para labeling? (#2.1 e #4.4)
      - 2.2.1.1 - confrontar análise exploratória no futuro
    - 2.2.2 - definir valores. e.g.: (bom/ruim; arriscado/seguro; 1-9) (menor é pior? maior é pior -> mais risco?)
    - 2.2.3 - definir janela de tempo para labeling
  - 2.2.3 - realizar o labeling

- 3 - índice de concordância na curadoria
  - 3.1 - compreender as anotações
    - 3.1.1 - viabilidade para seguir adiante?
    - 3.1.2 - desempenho do time de anotação
      - 3.1.2.1 - questionário sobre a experiência da curadoria: opinião, pontos fracos, pontos fortes, sugestões e propostas de melhoria

- 4 - análise exploratória
  - 4.1 - compreensão dos dados
  - 4.2 - há correlações evidentes? e.g.: amplitude alta -> maior risco?
    - 4.2.1 - há falsas correlações?
    - 4.2.2 - correlações de segundo nível? e.g.: amplitude alta & tempo prolongado -> maior risco?
    - 4.2.3 - confrontar inferências com experiência real dos voluntários
      - 4.2.3.1 - consequências?
  - 4.3 - o que diz a área de saúde?
  - 4.4 - confrontar resultados com dataset dos times
    - 4.4.1 - há viés na análise exploratória causado pela curadoria?
      - 4.4.1.1 - consequências?
        - 4.4.1.1.1 - como evitar?
  - 4.5 - trabalhos relacionados

- 5 - testar modelos de _estado da arte_
  - 5.1 - para cada modelo:
    - 5.1.1 - avaliar desempenho e métricas
  - 5.2 - estudo comparativo

- 6 - implementar modelo próprio
  - 6.1 - avaliar desempenho e métricas
  - 6.2 - avaliar possibilidde de melhoria

- 7 - estudo comparativo

- 8 - trabalhos futuros

