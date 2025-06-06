# Guia de Uso dos Prompts para Geração de Seções de Website

Este README explica como utilizar cada um dos prompts desenvolvidos para IA de UI/UX, indicando onde e como substituir as variáveis disponíveis. A estrutura é pensada para que você copie o prompt desejado, preencha apenas os campos entre colchetes e envie para a ferramenta de IA.

---

## Estrutura Geral

Todos os prompts seguem o mesmo padrão de variáveis a serem substituídas:

* **\[tipo de seção]**: descreve a funcionalidade ou propósito da seção (por exemplo: “Seção de Depoimentos”, “Seção de Hero”, “Seção de Lista de Serviços” etc.).
* **\[perfil do website]**: indica o ramo, público-alvo ou natureza do site (por exemplo: “e-commerce de moda feminina”, “blog corporativo de tecnologia”, “plataforma SaaS para gestão financeira” etc.).
* **\[identidade visual]**: refere-se ao conjunto de elementos visuais já definidos para a marca (exemplos: “paleta de cores azul e branco com tipografia sans-serif”, “estilo minimalista em preto e dourado”, “tonalidades pastel e fontes serifadas” etc.).
* **\[elemento adicional]** (apenas em alguns prompts): descreve o recurso extra a ser incorporado (por exemplo: “mapa interativo”, “vídeo em background”, “gráfico dinâmico”, “slider de imagens 3D” etc.).

Basta substituir cada trecho entre colchetes pelo conteúdo adequado. Não inclua os colchetes na versão final do prompt.

---

## Como usar este README

1. **Escolha o prompt** que melhor se encaixa à sua necessidade, dentre os seis modelos disponíveis.
2. **Copie o texto completo do prompt**, incluindo o título e toda a descrição.
3. **Substitua** cada variável (trechos entre colchetes) pelo texto correspondente ao seu projeto:

   * `[tipo de seção]`
   * `[perfil do website]`
   * `[identidade visual]`
   * `[elemento adicional]` (quando aplicável)
4. **Envie** o prompt preenchido para a IA de sua escolha (ChatGPT, DALL·E, Midjourney, etc.).
5. **Receba** a descrição detalhada da IA para a seção desejada e utilize-a como base para implementar ou gerar código front-end.

---

## 1. Prompt: Criar Seção do Zero com Complexidade e Estilo

### Texto completo do prompt

```
Desenvolva uma seção [tipo de seção] alinhada ao perfil do website [perfil do website], considerando o nicho de atuação (por exemplo, e-commerce, blog corporativo, startup de tecnologia, empresa de serviços) e aplicando elementos visuais que reflitam a identidade visual [identidade visual] (paleta de cores, estilos de fonte e tom da marca). Estruture o layout para ser totalmente responsivo, definindo colunas e grades que se adaptem a diferentes larguras de tela. Inclua blocos de texto explicativo, como parágrafos de descrição ou listas de pontos-chave, usando tipografia hierarquizada—títulos, subtítulos e corpo de texto—sem detalhar o conteúdo específico, mas assegurando que haja espaço suficiente para inserir informações relevantes ao público-alvo do website. Aplique transições suaves em botões e links para que, ao passar o mouse, cores e sombras mudem dinamicamente de acordo com a identidade visual. Crie animações de entrada para cada bloco de texto, fazendo com que parágrafos ou legendas deslizem ou apareçam com efeito fade-in à medida que a página é rolada, respeitando o tom (formal, descontraído, minimalista) apropriado ao perfil do website. Utilize ícones vetoriais para ilustrar cada recurso ou característica, posicionando-os ao lado de trechos de texto para reforçar visualmente a mensagem, escolhendo ícones cujo estilo combine com a identidade visual. Adicione um efeito parallax leve no fundo, com camadas de texto e imagens se deslocando em velocidades diferentes, criando profundidade sem destoar da paleta de cores. Garanta acessibilidade ao definir contraste de cores adequado entre texto e fundo e inclua atributos ARIA para componentes interativos. Caso a seção exija ilustrações ou gráficos, proponha lazy loading para as imagens e especifique um fallback de texto alternativo. Descreva em linguagem clara onde cada bloco textual deve ser inserido: por exemplo, uma área de destaque logo abaixo do título principal, seguida por parágrafos de apoio e uma lista ou citação que reforce o ponto, sempre conectando cada escolha ao perfil do website e à identidade visual. Oriente como inserir indicadores visuais, como setas animadas ou barras de progresso, para guiar o usuário até a próxima seção, mantendo a coesão estética.
```

### Onde colocar cada variável

1. **\[tipo de seção]**:

   * Exemplo: “Seção de Depoimentos”, “Seção de Equipe”, “Herói com Chamada para Ação” etc.
   * Deve ficar logo após “Desenvolva uma seção”.

2. **\[perfil do website]**:

   * Exemplo: “plataforma SaaS de gestão escolar”, “site institucional de escritório de advocacia”, “e-commerce de produtos orgânicos”.
   * Deve ficar logo após “perfil do website”.

3. **\[identidade visual]**:

   * Exemplo: “tons de verde e branco com tipografia serifada”, “estilo corporativo em azul-marinho e cinza”, “linguagem visual moderna, minimalista, tons pastel”.
   * Deve ficar logo após “identidade visual”.

Nenhum outro trecho entre colchetes aparece neste prompt.

---

## 2. Prompt: Melhorar Design de Seção Existente para Otimização de UX

### Texto completo do prompt

```
Receba uma seção [tipo de seção] preexistente e reimagine sua estrutura visual, ajustando-a conforme o perfil do website [perfil do website] (por exemplo, setor de saúde, fintech, agência de marketing) e reforçando a identidade visual [identidade visual] com cores, fontes e elementos gráficos já estabelecidos. Insira conteúdos textuais mais substanciais: adicione parágrafos de explicação ou instruções, cabeçalhos secundários e chamadas para ação com botões textuais mais detalhados—sem especificar o tema do texto, apenas garantindo blocos amplos e hierarquizados para eventual preenchimento pelo conteúdo da marca. Sugira ajustes tipográficos, como tamanhos e pesos diferentes para criar hierarquia entre títulos, subtítulos e texto corrido, escolhendo estilos que reflitam a personalidade da marca (séria, jovem, luxuosa). Proponha uma paleta de cores que aumente o contraste entre texto e fundo, mas que permaneça compatível com os tons principais da identidade visual. Adicione microanimações em componentes-chave, por exemplo, faça campos de formulário revelarem placeholders animados ou textos de ajuda surgirem ao focar, usando transições suaves que remetam ao estilo do website. Indique onde incluir ícones que acompanhem trechos de texto, como ícones de informação ao lado de instruções ou de checklists próximos a listas de pontos, selecionando gráficos que se integrem à linguagem visual da marca. Oriente sobre espaçamento adequado (margens e preenchimento) para que cada bloco de texto tenha seu próprio “respiro”, evitando que o usuário se sinta sobrecarregado. Caso existam listas ou blocos de recursos, descreva como enfatizar cada item visualmente com marcadores estilizados e interativos: ao passar o mouse, o ícone ao lado de cada item muda de cor ou escala levemente, usando transições que se encaixem no moodboard do site. Aponte ainda para as partes da seção que podem ser otimizadas para performance, como substituir fontes pesadas por versões otimizadas e carregar trechos de texto de forma progressiva através de skeleton loaders.
```

### Onde colocar cada variável

1. **\[tipo de seção]**:

   * Coloque o nome da seção que já existe e precisa ser melhorada (por exemplo: “Seção de Serviços”, “Seção de Perguntas Frequentes”).
   * Local: logo após “Receba uma seção”.

2. **\[perfil do website]**:

   * Informe o segmento ou o público-alvo (por exemplo: “e-commerce de tecnologia”, “consultoria de RH”, “empresa de telecomunicações”).
   * Local: logo após “perfil do website”.

3. **\[identidade visual]**:

   * Descreva brevemente o estilo visual já utilizado pela marca (por exemplo: “logotipo vermelho e preto, fontes sans-serif arrojadas”).
   * Local: logo após “identidade visual”.

---

## 3. Prompt: Transformar Design de Seção para Atualização Visual e Funcional

### Texto completo do prompt

```
Apresente um redesign completo de uma seção [tipo de seção] que esteja ultrapassada ou pouco atraente, respeitando o perfil do website [perfil do website] (por exemplo, loja de moda, escritório de advocacia, startup de educação) e atualize os elementos para refletir a identidade visual [identidade visual]: reavalie paleta de cores, estilos de fonte e atmosfera geral. Mantenha o conteúdo original, mas insira blocos maiores de texto: uma introdução em parágrafo, subtópicos explicativos e uma citação ou depoimento em destaque—sem especificar o conteúdo exato, apenas indicando a necessidade de espaços textuais mais generosos. Sugira substituir blocos estáticos por componentes interativos: crie um carrossel de cards onde cada card contenha um título, um parágrafo curto de descrição e um botão de ação, estilizados em conformidade com a marca. Explique como os parágrafos devem aparecer com animações—como deslize lateral ou fade-in logo após o título principal—sem definir o texto, apenas indicando que cada bloco textual deve ser animado em harmonia com o estilo visual. Insira ilustrações vetoriais ou SVGs animados próximos aos trechos de texto, por exemplo, setas que giram levemente para indicar continuidade ou ícones que mudam de cor quando o texto relacionado estiver no viewport, seguindo o guia de estilo da identidade visual. Estruture a seção para que em telas menores os parágrafos sejam reorganizados em colunas únicas, com títulos maiores e texto repartido em blocos de leitura mais curtos, de acordo com os padrões de responsividade do site. Inclua orientações sobre otimizar as animações definindo durações e curvas de easing apropriadas para não comprometer a experiência, assegurando que toda animação esteja em sintonia com o tom da marca. Explique como agrupar elementos textuais em painéis ou cartões com sombras sutis, criando camadas visuais que se sobrepõem ligeiramente, reforçando a identidade visual.
```

### Onde colocar cada variável

1. **\[tipo de seção]**:

   * Informe qual seção será redesenhada (por exemplo: “Seção de Características”, “Seção de Depoimentos”).
   * Local: logo após “seção”.

2. **\[perfil do website]**:

   * Descreva o nicho ou ramo do site (por exemplo: “e-commerce de eletrônicos”, “blog sobre decoração”, “agência de publicidade”).
   * Local: imediatamente após “perfil do website”.

3. **\[identidade visual]**:

   * Informe o estilo visual principal (por exemplo: “paleta monocromática em cinza e preto”, “cores vivas com tipografia manuscrita”).
   * Local: após “identidade visual”.

---

## 4. Prompt: Adicionar Elemento Interativo ao Design de Seção

### Texto completo do prompt

```
Pegue uma seção [tipo de seção] existente e incorpore um elemento interativo adicional—por exemplo, um mapa estilizado, um vídeo em background ou um gráfico dinâmico—garantindo que sua aparência e comportamento estejam alinhados ao perfil do website [perfil do website] (como plataforma de aprendizado online, consultoria, ou marketplace) e à identidade visual [identidade visual]. Instrua a IA a criar um bloco de texto explicativo com vários parágrafos, posicionando-o ao lado ou acima do elemento interativo, sem especificar o texto, apenas orientando que seja descritivo e suficientemente extenso para explicar o contexto da marca. Descreva como carregar o elemento de forma assíncrona para não atrasar o carregamento do texto e como animar esse texto com um efeito fade-in ou slide ao exibir o elemento, usando transições que reforcem a paleta de cores e o estilo de animação da marca. Se for um mapa, oriente a inserir ícones animados para marcar pontos de interesse, e ao clicar ou passar o mouse sobre esses ícones, exibir um tooltip com texto explicativo—sem detalhar o texto, apenas mencionando que haja tooltips informativos com o estilo visual da marca. Caso seja um vídeo, peça que o overlay semitransparente contenha um título e dois ou três parágrafos de texto em camadas, com transições de opacidade sincronizadas ao rodar o vídeo, usando fontes e cores compatíveis com a identidade visual. Indique também a inclusão de um botão de ação textual, com hover state animado, ao lado do texto, reforçando a interatividade e mantendo o estilo de botões preexistentes da marca. Explique como posicionar o [elemento adicional] em relação ao texto: por exemplo, o mapa no fundo com texto sobreposto, ou o vídeo ocupando 100% da largura enquanto o texto surge em um painel flutuante fixo, sempre em conformidade com o layout geral do site e as diretrizes visuais.
```

### Onde colocar cada variável

1. **\[tipo de seção]**:

   * Identifique a seção a ser melhorada (por exemplo: “Seção de Contato”, “Seção de Localização”).
   * Local: após “seção”.

2. **\[perfil do website]**:

   * Exemplo: “site de imobiliária”, “portal de notícias esportivas”, “serviço de streaming de música”.
   * Local: após “perfil do website”.

3. **\[identidade visual]**:

   * Exemplo: “cores vibrantes e tipografia descontraída”, “tons neutros e fonte serifada elegante”.
   * Local: após “identidade visual”.

4. **\[elemento adicional]**:

   * Exemplos: “mapa interativo”, “vídeo em background”, “gráfico animado em tempo real”.
   * Local: logo depois de “elemento interativo adicional”.

---

## 5. Prompt: Revisar e Analisar Design de Seção para Relatório de UX

### Texto completo do prompt

```
Avalie uma seção [tipo de seção] já implementada, considerando o perfil do website [perfil do website] (loja física, plataforma SaaS, site institucional) e a identidade visual [identidade visual] existente (tipografia, cores, estilo de ícones). Aponte oportunidades para aumentar a quantidade de conteúdo textual inserido: sugira adicionar títulos secundários, subtópicos com parágrafos explicativos e chamadas para ação com descrições mais detalhadas—sem indicar o texto exato, apenas destacando que cada novo parágrafo deve esclarecer objetivos, benefícios ou instruções de acordo com o tom da marca. Aponte inconsistências visuais, como hierarquia de fonte inadequada, e recomende tamanhos e pesos diferentes para títulos, subtítulos e corpo de texto, respeitando a família de fontes aprovada pela identidade visual. Indique oportunidades para inserir animações leves em blocos de texto, como parágrafos que surgem com efeito slide a partir das laterais ou títulos que pulsam levemente ao entrar no viewport, escolhendo estilos de movimento que combinem com o perfil do site. Mostre onde ícones podem substituir palavras em listas de recursos ou etapas do processo, explicando que cada ícone deve estar alinhado ao texto correspondente e ao estilo de sombreamento e cor da marca. Explique como medir a performance da seção, indicando que a IA deve gerar relatórios sobre métricas de carregamento de texto e renderização de animações, mas sem citar números específicos, apenas destacando que a velocidade de carregamento e fluidez de animação devem respeitar padrões do setor do website. Por fim, ofereça recomendações de acessibilidade, como garantir que cada bloco de texto tenha contraste de cor adequado e marcações semânticas (headings, lists), considerando o público-alvo do site.
```

### Onde colocar cada variável

1. **\[tipo de seção]**:

   * Pode ser “Seção de Sobre Nós”, “Seção de Blog”, “Seção de Preços”.
   * Local: após “seção”.

2. **\[perfil do website]**:

   * Exemplo: “e-commerce de calçados esportivos”, “startup de saúde digital”, “instituição educacional online”.
   * Local: após “perfil do website”.

3. **\[identidade visual]**:

   * Exemplo: “logo azul com degradê, fontes sem serifa modernas”, “padronização em tons terrosos e serifas clássicas”.
   * Local: após “identidade visual”.

---

## 6. Prompt: Criar Design System para Seções de Website

### Texto completo do prompt

```
Desenvolva um guia de estilo (design system) completo, capaz de gerar seções [tipo de seção] para diferentes perfis de website [perfil do website] (agência de marketing, portal de notícias, fintech, e-commerce), sempre respeitando a identidade visual [identidade visual] de cada marca. Inclua definições de tipografia detalhadas: hierarquia de títulos, subtítulos, corpo de texto e legendas, parametrizando tamanhos, pesos e espaçamentos que se adequem ao tom e personalidade de cada empresa. Solicite que a IA produza exemplos genéricos de blocos de texto em cada componente—como parágrafos de introdução, listas de características com descrições e chamadas para ação textuais—sem dizer o conteúdo, apenas definindo que devem existir e ser suficientemente longos para preencher o layout. Estabeleça uma paleta de cores base e variações para efeitos de hover e foco em botões e links textuais, permitindo ajustes conforme a paleta principal de cada identidade visual. Crie tokens de design para espaçamentos (por exemplo, margin e padding) e defina diretrizes de layout: grids com colunas fluidas, breakpoints para reorganização de textos e componentes em telas menores, de acordo com as diretrizes gerais de cada marca. Instrua a IA a incluir ilustrações ou ícones vetoriais associados a cada bloco de texto, explicando como devem ser animados (por exemplo, ícones que aparecem com fade-in quando o texto relacionado for exibido), garantindo que esses ícones pertençam ao mesmo conjunto visual de cada identidade. Descreva como documentar cada componente: definir onde inserir cada bloco de texto, quais estilos aplicar ao título versus subtítulo versus corpo e como padronizar animações para blocos textuais e visuais (parágrafos que surgem deslizando de baixo para cima ou cards de texto que giram levemente em 3D). Conclua recomendando uma estrutura de versionamento de tokens e componentes que permita evoluir o design system sem quebrar seções previamente criadas, considerando diferentes variações para empresas com identidade visual mais conservadora ou mais vanguardista.
```

### Onde colocar cada variável

1. **\[tipo de seção]**:

   * Pode ser genérico (ex.: “Seção de Conteúdo Genérica”) ou algo mais específico conforme a empresa (ex.: “Seção de Landing Page”, “Seção de FAQ”).
   * Local: logo após “seções”.

2. **\[perfil do website]**:

   * Liste vários exemplos de segmentos ou público-alvo (ex.: “site institucional de escritório de contabilidade”, “app de finanças pessoais”, “blog de design gráfico”).
   * Local: após “perfil do website”.

3. **\[identidade visual]**:

   * Especifique que cada marca terá seu próprio “guideline” inicial (ex.: “sem fontes serifadas, cores vibrantes”, “visual dark mode, tipografia monospace”).
   * Local: após “identidade visual”.

---

## Dicas Gerais

* **Mantenha a coerência**: Certifique-se de que o estilo (formal, descontraído, minimalista etc.) refletido nos prompts corresponda ao tom de voz da marca.
* **Não inclua colchetes** nas versões finais. Apenas utilize o texto das variáveis.
* **Verifique duplicações**: Evite repetir exatamente a mesma identidade visual em múltiplos prompts; procure adaptar descrições que façam sentido ao site real.
* **Teste incrementalmente**: Se a IA gerar uma seção muito enxuta, tente incluir instruções curtinhas como “inclua descrições de X parágrafos” ou “insira listas de Y itens com ícones”, até alcançar o nível de detalhamento desejado.

---

Pronto! Agora você tem um guia completo para preencher e utilizar cada prompt, gerando seções de website ricas em conteúdo visual e alinhadas ao perfil e identidade visual de qualquer marca ou segmento.
