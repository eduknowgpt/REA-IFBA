# Sobre a OntoKSD

A **OntoKSD** (*Ontology for Knowledge–Skill–Disposition*) é uma ontologia desenvolvida para representar formalmente competências educacionais no domínio da Computação, segundo o modelo de *Competency-Based Education* (CBE) e os referenciais internacionais da **ACM/IEEE CC2020**.
Ela permite descrever uma competência como uma entidade composta, que articula três dimensões fundamentais:

1. **Knowledge (K)** – o conhecimento conceitual ou factual que o estudante deve mobilizar;
2. **Skill (S)** – a ação cognitiva ou prática que o estudante deve realizar, associada a um nível da Taxonomia de Bloom (ex.: *Compreender, Aplicar, Analisar, Criar*);
3. **Disposition (D)** – as atitudes, valores ou posturas demonstradas pelo estudante ao executar a tarefa (ex.: *meticuloso, colaborativo, ético*).

Essa estrutura visa tornar as competências **observáveis, avaliáveis e semanticamente interoperáveis**, permitindo que elas sejam reutilizadas, validadas e alinhadas a frameworks de referência (BNCC Computação, CC2020, CS2023 etc.).

No contexto desta tarefa — **Implementação do Jogo da Velha** —, a OntoKSD é aplicada para mapear o aprendizado de programação (estruturas de dados, controle de fluxo, modularização e comunicação) a evidências de desempenho e disposições observáveis durante a atividade prática e a avaliação oral.



## Significado dos Pares (KS)

Os **pares (KS)** representam a associação entre um conhecimento específico e uma habilidade cognitiva derivada da Taxonomia de Bloom. Cada par define **o que** o estudante mobiliza (K) e **o que faz** com esse conhecimento (S) no contexto da tarefa.

O **Conhecimento (K)** é sempre identificado a partir de vocabulários padronizados (CC2020, CS2013, BNCC Computação ou domínios fundamentais como `AnalyticalThinking`, `DataStructures`, `RequirementsSpecification`).

A **Skill (S)** é um verbo de ação cognitiva — como *Compreender, Aplicar, Analisar, Criar* — que expressa o nível de proficiência esperado e é mapeado na ontologia por meio da propriedade `hasBloomLevel`.

**Exemplo:**

**(KS): Estruturas de dados / Aplicar**
O estudante utiliza seus conhecimentos sobre **estruturas de dados** (K) para **aplicar** (S) listas ou matrizes na representação do jogo.



## Significado das Disposições (D)

As **disposições (D)** representam atitudes e traços observáveis de comportamento que qualificam o modo como o estudante aplica o conhecimento e a habilidade. Elas não descrevem **o “quê”** o estudante sabe ou faz, mas **como** ele age cognitivamente e socialmente ao fazê-lo.

Essas disposições podem ser de natureza:

* **Cognitiva**: meticuloso, analítico, criativo;
* **Interpessoal**: colaborativo, comunicativo;
* **Ética e profissional**: responsável, ético.
