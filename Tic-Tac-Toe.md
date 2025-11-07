# Descrição Detalhada da Tarefa: Implementação do Jogo da Velha
> Criador: Prof. Dr. Eduardo Cambruzzi, IFBA campus Valença

## Contexto

No componente curricular de **Lógica de Programação**, do **Curso Técnico Integrado em Informática (1º ano, IFBA)**, os estudantes foram desafiados a implementar o jogo da velha (*tic-tac-toe*) de forma colaborativa, aplicando conceitos fundamentais de programação estruturada.

## Enunciado da Tarefa

Desenvolver um programa que implemente o **jogo da velha (3x3)**, obedecendo às regras tradicionais: dois jogadores alternam jogadas marcando “X” e “O” em uma matriz 3x3 até que um deles vença (linha, coluna ou diagonal) ou o jogo empate.

## Requisitos Técnicos

* Representar o tabuleiro utilizando **listas** (listas simples ou listas de listas) ou **matrizes**.
* Utilizar **estruturas condicionais** para determinar jogadas válidas e condições de vitória/empate.
* Empregar **laços de repetição** para controle do fluxo do jogo.
* Organizar o código em **funções** que recebam argumentos e retornem valores.
* Utilizar **acumuladores e contadores** quando necessário (ex.: contagem de jogadas).
* Implementar **verificações de entrada** e mensagens de **feedback** para o jogador.

## Modalidade de Avaliação

A avaliação é **oral e individual**, mesmo com a tarefa feita em grupo. Cada estudante explica o funcionamento do código do grupo, demonstrando **domínio conceitual e procedimental** sobre a solução desenvolvida.

## Critérios de Avaliação

* Funcionamento correto do programa (**critério técnico**).
* Clareza na explicação e domínio dos conceitos (**critério cognitivo**).
* Colaboração e equidade no trabalho (**critério atitudinal**).



# Competências Especificadas (OntoKSD + BNCC Computação)

## Competência Geral (BNCC – Computação na Educação Básica)

* **Compreender, analisar, projetar e implementar soluções computacionais** para problemas do cotidiano, mobilizando conceitos de algoritmos, representação de dados e estruturas de controle, de forma ética, colaborativa e reflexiva.



## Competências Específicas da Tarefa



### C1 - Definir os requisitos da solução analisando criticamente situações do mundo real.

**Descrição detalhada:**
> Esta competência envolve a capacidade de **analisar um problema computacional concreto** — neste caso, o jogo da velha — para identificar, compreender e especificar seus **requisitos funcionais e não funcionais** antes da implementação. O estudante deve observar o funcionamento lógico do jogo, reconhecer suas regras e restrições, e traduzi-las em requisitos claros que orientem o desenvolvimento do programa.
O processo inclui a **colaboração** entre os integrantes da dupla, o **raciocínio analítico** para decompor o problema e a **documentação organizada** das observações, de forma a garantir uma base sólida para o código a ser produzido.

**(KS): Pensamento Analítico / Aplicar**
> O estudante aplica o **pensamento analítico** para decompor o funcionamento do jogo em componentes lógicos observáveis, como jogadas, condições de vitória e controle de fluxo. Esse raciocínio permite compreender as relações de causa e efeito no comportamento do jogo e antecipar as decisões de projeto que deverão ser implementadas.

**(KS): Colaboração / Aplicar**
> O estudante aplica **estratégias colaborativas** para discutir, comparar e validar interpretações sobre o problema com o colega de dupla. Essa cooperação contribui para a construção coletiva dos requisitos e para a resolução de ambiguidades, simulando práticas profissionais de coautoria em engenharia de software.

**(KS): Especificação de Requisitos / Aplicar**
> O estudante aplica conhecimentos sobre **especificação de requisitos** para expressar, de forma organizada e compreensível, as funcionalidades esperadas (ex.: entrada de jogadas, detecção de vitória, mensagem de empate) e restrições (ex.: jogadas válidas, limite de turnos).
O foco é transformar observações empíricas do jogo em **descrições estruturadas** que servirão de guia para a codificação.

**(D): Meticuloso e Colaborativo**

* **Meticuloso** — demonstra atenção à organização e clareza ao representar dados, requisitos e observações, cuidando para que nenhum aspecto essencial do problema seja negligenciado.
* **Colaborativo** — contribui ativamente nas discussões, respeitando e integrando as ideias do parceiro, buscando um entendimento comum sobre os requisitos e a forma de expressá-los.

#### BNCC associada

**Competência geral 1 – Computação (Ensino Médio)**

> “Compreender as possibilidades e os limites da Computação para resolver problemas (...), propondo e analisando soluções computacionais para diversos domínios do conhecimento” – C1 envolve exatamente analisar o problema (jogo da velha), levantar requisitos e pensar a solução computacional adequada.

**Competência geral 5 – Computação (Ensino Médio)**

> “Desenvolver projetos para investigar desafios do mundo contemporâneo, construir soluções (...), preferencialmente de maneira colaborativa” – a definição de requisitos é a etapa inicial do projeto de software em dupla, articulando análise, discussão e documentação.

**Competências específicas:**

* **EM13CO01** – “Explorar e construir a solução de problemas por meio da reutilização de partes de soluções existentes” – ao analisar o jogo, os estudantes podem se apoiar em padrões de solução já conhecidos (ex.: exemplos de pseudocódigo para jogos de tabuleiro) e adaptá-los.
* **EM13CO02** – “Explorar e construir a solução de problemas por meio de refinamentos, utilizando diversos níveis de abstração desde a especificação até a implementação” – C1 está no nível de especificação de requisitos, que depois será refinado em algoritmos e código.



### C2 – Identificar formas de organizar e representar a informação de maneira estruturada, incluindo matrizes, registros e listas.

**Descrição detalhada:**
> Esta competência envolve a capacidade de **traduzir elementos conceituais do jogo da velha em estruturas de dados apropriadas**, representando o tabuleiro, as posições jogadas e os estados intermediários da partida. O estudante deve aplicar raciocínio analítico para **modelar informações** do domínio do problema (jogadores, jogadas, condições de vitória) em formatos computacionais adequados, utilizando **listas simples ou listas de listas (matrizes)**.

> A precisão na representação dos dados é essencial para garantir que as regras do jogo sejam corretamente implementadas e compreendidas, além de favorecer a **manutenção e clareza do código**. O trabalho colaborativo contribui para validar o modelo de dados, discutir alternativas de implementação e verificar sua coerência com os requisitos previamente definidos.

**(KS): Estruturas de dados / Aplicar**
> O estudante aplica conhecimentos de **estruturas de dados** para escolher e utilizar representações adequadas (listas ou matrizes) que armazenem o estado atual do jogo. Isso inclui compreender como **acessar, modificar e exibir** os dados da estrutura de maneira eficiente e legível, garantindo consistência durante o ciclo de jogadas.

**(KS): Pensamento Analítico / Aplicar**
> O estudante aplica o **pensamento analítico** para identificar quais informações do jogo precisam ser representadas, como relacioná-las entre si (ex.: posição da jogada, valor “X” ou “O”, condição de vitória) e como essas relações influenciam as operações sobre os dados. Essa análise orienta a escolha de estruturas adequadas e previne redundâncias ou inconsistências lógicas.

**(D): Meticuloso e Colaborativo**

* **Meticuloso** — demonstra atenção ao detalhe na organização e clareza da representação dos dados, evitando erros de indexação, inconsistência de valores ou confusão entre estados do jogo.
* **Colaborativo** — trabalha de forma cooperativa com o parceiro de dupla para validar a estrutura de dados e integrar diferentes ideias de implementação, respeitando contribuições e buscando consenso técnico.

#### BNCC associada

**Competência geral 1 – Computação (Ensino Médio)**
A representação do tabuleiro (listas, matrizes) é parte do processo de **propor e analisar soluções computacionais viáveis**, em termos de estrutura de dados adequada ao problema.

**Competência geral 4 – Computação (Ensino Médio)**

> “Construir conhecimento usando técnicas e tecnologias computacionais, produzindo conteúdos e artefatos de forma criativa, com respeito às questões éticas e legais” – aqui o artefato é, justamente, o **modelo de dados do jogo** (tabuleiro, jogadas, estados).

**Competências Específicas:**

* **(EF15CO01)** – Identificar formas de organizar e representar a informação de maneira estruturada, incluindo matrizes, registros, listas e grafos. É a base explícita para escolher listas ou matrizes na representação do tabuleiro.
* **(EF04CO01)** – Reconhecer objetos reais ou digitais que podem ser representados por matrizes, com cada componente em uma posição coordenada.
* **(EF07CO03)** – Construir soluções computacionais selecionando estruturas de dados adequadas, de forma individual ou colaborativa. C2 concretiza isso quando a dupla discute qual estrutura (lista de listas, matriz, etc.) é mais adequada ao jogo.
* **(EF09CO02)** – (no 9º ano) Construir soluções computacionais selecionando tipos de dados e estruturas apropriadas às situações propostas; o texto da BNCC destaca especificamente vetores e matrizes como instrumentos centrais de representação.
* **(EM13CO02)** – Ao escolher e refinar estruturas (ex.: trocar uma representação mais confusa por outra mais clara), o aluno pratica o refinamento por abstração em diferentes níveis, desde o modelo conceitual do tabuleiro até a implementação em código.



### C3 – Aplicar estruturas condicionais e laços de repetição, de forma criativa e inventiva, para controle de fluxo.

**Descrição detalhada:**
> Esta competência refere-se à capacidade de **controlar o comportamento dinâmico do jogo da velha** por meio do uso combinado de estruturas condicionais e de repetição. O estudante deve compreender e aplicar comandos de **decisão e iteração** para gerenciar turnos, validar jogadas e determinar as condições de vitória ou empate, garantindo que o jogo se mantenha consistente do início ao fim.
> Além de aplicar corretamente esses conceitos, espera-se que o estudante **explore soluções criativas e inventivas**, buscando simplificar o código, reduzir redundâncias e antecipar possíveis exceções lógicas.
> A **meticulosidade** é essencial para evitar erros de lógica e garantir o fluxo correto das jogadas, enquanto a **colaboração** possibilita o refinamento coletivo das estratégias de controle e depuração.

**(KS): Estruturas condicionais (if, elif, else) / Aplicar**
> O estudante aplica **estruturas condicionais** para controlar decisões no jogo, como verificar se uma jogada é válida, identificar o vencedor ou detectar um empate. Esse uso envolve traduzir regras do jogo em condições lógicas bem definidas, garantindo que cada cenário seja corretamente tratado no fluxo do programa.

**(KS): Estruturas de repetição (while, for) / Aplicar**
> O estudante aplica **laços de repetição** para criar o ciclo contínuo do jogo, permitindo que as jogadas se repitam até que seja atingida uma condição de término (vitória ou empate). Isso inclui controlar o número de turnos, alternar jogadores e assegurar que o loop de execução respeite as regras definidas.

**(KS): Operadores relacionais e lógicos / Aplicar**
> O estudante aplica **operadores relacionais e lógicos** para expressar as condições de decisão e repetição, compondo expressões booleanas que permitem avaliar estados do jogo (ex.: “as três posições são iguais” ou “há espaços disponíveis”). Esses operadores garantem **precisão na tomada de decisão** e eficiência no controle do fluxo.

**(D): Criativo (inovador), Inventivo (exploratório), Meticuloso, Colaborativo**

* **Criativo (inovador)** — demonstra iniciativa para buscar diferentes formas de estruturar o código, criando soluções alternativas para o mesmo problema e propondo melhorias no fluxo do jogo.
* **Inventivo (exploratório)** — explora novas abordagens e testa hipóteses de implementação, aprendendo por tentativa e erro e ajustando o código com base em observações e resultados.
* **Meticuloso** — mantém atenção constante aos detalhes lógicos, evitando contradições, repetições desnecessárias ou falhas de controle que possam comprometer a execução do jogo.
* **Colaborativo** — interage ativamente com o colega de dupla, discutindo estratégias de fluxo e verificando em conjunto o funcionamento das estruturas condicionais e iterativas.

#### BNCC associada

* **Competência geral 1 (EM)** – O uso de condicionais e laços na implementação do jogo concretiza a capacidade de **utilizar algoritmos e estruturas de controle** em um problema real.
* **Competência geral 5 (EM)** – Desenvolver projetos para investigar desafios do mundo real, aqui materializado no projeto de jogo que precisa **controlar o fluxo de interação** de forma robusta.

**Competências específicas:**

* **(EF15CO02)** – Elaborar e simular algoritmos que já envolvem **sequências, seleções e repetições**; aqui surgem explicitamente as estruturas de controle que depois aparecerão como `if`, `while`, `for` etc.
* **(EF03CO02)** – Trabalhar com **repetições condicionais simples** em algoritmos, que é o “projeto” natural para o loop de jogo da velha (repetir enquanto não houver vitória ou empate).
* **(EF04CO03)** – Elaborar algoritmos que envolvam **repetições simples e aninhadas**, reforçando a ideia de ciclos que se repetem sob certas condições (ex.: percorrer o tabuleiro, verificar linhas/colunas/diagonais).
* **(EF69CO02)** – Criar algoritmos com **estruturas de seleção e repetição** em diferentes linguagens de programação, consolidando o uso de condicionais e laços no código.



### C4 – Modularizar o código, de forma meticulosa, para dividir responsabilidades, organizando-o em funções independentes.

**Descrição detalhada:**
> Esta competência envolve a capacidade de **estruturar programas de forma modular**, decompondo o problema em funções específicas e reutilizáveis, cada uma responsável por uma parte claramente definida do jogo. O estudante deve ser capaz de **criar funções** com parâmetros e retorno de valores, compreender o **escopo das variáveis utilizadas** e organizar o fluxo do programa de modo que cada componente possa ser entendido, testado e modificado de forma isolada.
> A modularização reflete **maturidade no raciocínio computacional**, pois permite clareza, reuso e manutenção facilitada do código. O comportamento meticuloso assegura que as funções sejam implementadas com precisão e coerência, enquanto a colaboração possibilita a integração harmoniosa das partes produzidas pela dupla.

**(KS): Função, parâmetros e retorno / Criar**
> O estudante **cria funções específicas** para encapsular responsabilidades distintas dentro do programa, como inicializar o tabuleiro, checar condições de vitória ou imprimir o estado atual do jogo. Esse processo exige definir **parâmetros adequados**, compreender o fluxo de dados entre as funções e planejar retornos consistentes que alimentem outras partes do programa.

**(KS): Escopo de variáveis / Aplicar**
> O estudante aplica corretamente o conceito de **escopo**, diferenciando variáveis locais e globais, de modo a evitar conflitos de nomes e comportamentos inesperados. Essa aplicação prática demonstra domínio sobre a **visibilidade e duração das variáveis** no contexto de funções, garantindo integridade e previsibilidade no código.

**(D): Meticuloso, Colaborativo**

* **Meticuloso** — demonstra atenção ao detalhe na definição de funções, parâmetros e retornos, assegurando consistência semântica e minimizando erros de referência ou redundância.
* **Colaborativo** — participa ativamente na divisão de responsabilidades e integração das funções do programa, comunicando-se com o parceiro de forma clara e construtiva para garantir coerência no código final.

#### BNCC associada

* **Competência geral 4 (EM)** – Construir conhecimento em Computação aplicando técnicas e tecnologias para produzir artefatos; a **modularização** é uma técnica essencial para projetos maiores e mais organizados.
* **Competência geral 5 (EM)** – Desenvolver projetos computacionais investigando desafios do mundo real. Projetos maiores exigem modularização para facilitar trabalho em dupla e manutenção do código.

**Competências específicas:**

* **(EM13CO02)** – Refinar soluções computacionais em diferentes níveis de abstração, desde a arquitetura até a implementação, o que inclui decidir **como decompor o programa em funções** e como elas se comunicam.



### C5 - Justificar de forma ética, clara e fundamentada a autoria de soluções computacionais.

**Descrição detalhada:**
> Esta competência envolve a capacidade de **explicar e defender a própria solução computacional**, demonstrando domínio conceitual, clareza comunicativa e responsabilidade ética.
Durante a avaliação oral, o estudante deve ser capaz de **compreender o vocabulário técnico** da programação, **aplicar o raciocínio lógico** para justificar decisões de implementação e **comunicar-se oralmente** de forma estruturada e fundamentada.
> A competência reflete não apenas a apropriação cognitiva do conhecimento, mas também o **compromisso ético com a autoria do trabalho** e com a comunicação respeitosa e colaborativa no ambiente acadêmico.

**(KS): Vocabulário técnico da programação (função, laço, variável, condição, etc.) / Compreender**
> O estudante compreende o significado e o uso do **vocabulário técnico da programação**, reconhecendo termos e conceitos fundamentais como função, estrutura de repetição, condição lógica e variável. Essa compreensão permite interpretar e explicar, com precisão, as partes do código e as decisões tomadas durante o desenvolvimento.

**(KS): Raciocínio lógico / Aplicar**
> O estudante aplica o **raciocínio lógico** para justificar a sequência de operações do código, demonstrando coerência entre os requisitos do problema e a estrutura da solução. Essa habilidade envolve **argumentar de forma fundamentada**, conectando causa e efeito entre decisões algorítmicas e resultados obtidos.

**(KS): Comunicação Oral / Aplicar**
> O estudante aplica habilidades de **comunicação oral** para descrever a solução de maneira clara, organizada e acessível. Isso inclui o uso adequado da terminologia técnica, o encadeamento lógico das ideias e a capacidade de responder a questionamentos do avaliador de forma segura e fundamentada.

**(D): Ético, Comunicativo, Responsável**

* **Ético** — reconhece a própria autoria da solução, evita o plágio e demonstra honestidade intelectual ao expor suas contribuições e limites de conhecimento.
* **Comunicativo** — expressa ideias de maneira clara, objetiva e coerente, favorecendo a compreensão mútua e o diálogo construtivo com o avaliador e o colega.
* **Responsável** — assume compromisso com a qualidade da explicação e com a veracidade das informações apresentadas, demonstrando maturidade e profissionalismo na defesa da solução.

#### BNCC associada

* **Competência geral 4 (EM)** – Enfatiza a produção de artefatos computacionais considerando **critérios de qualidade, comunicação e reflexão crítica**.
* **Competência geral 6 (EM)** – Expressar, representar e comunicar informações e ideias de forma clara, usando objetos computacionais e diferentes linguagens, o que se conecta diretamente ao uso de vocabulário técnico e à explicação oral do código.
* **Competência geral 7 (EM)** – Agir com respeito, responsabilidade, ética e compromisso com o bem comum em ambientes mediados por tecnologias – base explícita para as disposições **Ético** e **Responsável** de C5.

**Competências específicas:**

* **(EM13CO19)** – Expor, argumentar e negociar propostas de soluções computacionais em contextos colaborativos, o que se alinha à **justificativa oral do código** frente ao professor e ao colega.
* **(EM13CO21)** – Comunicar ideias complexas por meio de objetos computacionais, considerando diferentes públicos e linguagens; aqui, explicar um programa de jogo da velha de forma clara e fundamentada é uma concretização direta dessa habilidade.
