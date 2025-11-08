# **Tarefa: Censo Escolar e Algoritmos em Linguagem Natural**

## **Descrição e Objetivos de Aprendizagem da Tarefa – “Censo Escolar e Algoritmos em Linguagem Natural”**

A tarefa, estruturada em **quatro passos progressivos**, tem como propósito central **desenvolver, de forma incremental, a habilidade de descrever algoritmos em linguagem natural** para processar e analisar **registros estruturados**.
Essa habilidade constitui um dos pilares do **Pensamento Computacional**, particularmente nos eixos de **abstração, decomposição e generalização de problemas**, além de apoiar a construção de competências em **representação de dados e raciocínio lógico**.

Cada etapa reutiliza e amplia as estruturas lógicas do passo anterior — promovendo **reuso conceitual, sintático e cognitivo** — e introduz gradualmente **novos campos, condições e relações entre variáveis**, conduzindo o estudante a níveis mais altos de abstração e autonomia na formulação de soluções algorítmicas.

### **Justificativa Pedagógica**

A atividade foi concebida para integrar o raciocínio lógico-matemático ao pensamento computacional, aproximando o estudante do modo de pensar de um programador sem o uso prévio de uma linguagem formal. Ao trabalhar em linguagem natural, o foco está na **organização do pensamento, clareza de instruções e antecipação de resultados**, preparando o aluno para futuras transições ao pseudocódigo e à programação.
A progressão também estimula a reflexão sobre **qualidade e eficiência de algoritmos**, elementos fundamentais da formação em Computação.


### **Objetivos de Aprendizagem**

Ao final da sequência de quatro passos, espera-se que o estudante seja capaz de:

1. **Compreender a estrutura de um registro de dados** e reconhecer os campos relevantes para um problema (ex.: Nome, Sexo, Miopia).

2. **Descrever algoritmos em linguagem natural de forma lógica e ordenada**, detalhando entradas, condições e saídas.

3. **Usar operadores lógicos e estruturas condicionais** para classificar, filtrar e contabilizar informações com base em atributos dos registros.

4. **Calcular totais e médias**, empregando raciocínio algorítmico e uso de variáveis acumuladoras, demonstrando compreensão de ciclos de processamento de dados.

5. **Refinar e generalizar soluções**, adaptando algoritmos anteriores para lidar com novos campos (Miopia, Hipermetropia, Astigmatismo) e combinando condições múltiplas.

6. **Avaliar a coerência e eficiência de uma solução algorítmica**, identificando redundâncias, erros lógicos e oportunidades de modularização ou reuso.

7. **Relacionar algoritmos a contextos reais de coleta e análise de dados**, compreendendo a relevância social e ética do processamento automatizado de informações (ex.: censos escolares, diagnósticos, pesquisas).


## **Etapas da Tarefa (com progressão de complexidade)**

### **Passo 1 — Censo por Sexo**

**Descrição:**
> O estudante descreve, em linguagem natural, um algoritmo que lê registros contendo `Nome` e `Sexo` e exibe o total de meninos, meninas e alunos.

> **Conceitos-chave:** Estrutura de dados simples, contagem condicional, processamento sequencial.

> **Complexidade cognitiva:** *Baixa (Aplicar)*.



### **Passo 2 — Censo por Sexo e Miopia**

**Descrição:**
> Mantendo a estrutura do passo anterior, o estudante amplia o algoritmo para incluir o campo `Miopia`, computando contagens e médias específicas por sexo e uma média geral.

> **Conceitos-chave:** Introdução a variáveis acumuladoras, cálculo de médias, comparação de valores numéricos.

> **Complexidade cognitiva:** *Média (Analisar e Aplicar)*.

> **Reuso:** Reutiliza estrutura de leitura e contagem do passo 1.



### **Passo 3 — Censo com Duas Condições (Miopia e Hipermetropia)**

**Descrição:**
> O algoritmo agora considera dois atributos de disfunção visual (`Miopia` e `Hipermetropia`), realizando contagens e médias específicas por sexo e tipo.

> **Conceitos-chave:** Estruturas condicionais compostas, uso de operadores lógicos (E/OU), generalização de funções de cálculo.

> **Complexidade cognitiva:** *Média-Alta (Analisar)*.

> **Reuso:** Expande o modelo do passo 2 com novas variáveis e condições lógicas compostas.



### **Passo 4 — Censo com Três Condições e Combinações (Miopia, Hipermetropia, Astigmatismo)**

**Descrição:**
> O estudante descreve o algoritmo completo, considerando três atributos e suas interseções. Deve calcular totais, médias e combinações (ex.: alunos com Miopia e Astigmatismo).

> **Conceitos-chave:** Estruturas de repetição, lógica combinatória, modularização de funções.

> **Complexidade cognitiva:** *Alta (Criar e Avaliar)*.

> **Reuso:** Baseia-se na estrutura do passo 3, adicionando tratamento de combinações e modularização conceitual do algoritmo.



# **Competências OntoKSD Associadas**

### **C1 – Representar algoritmos em linguagem natural para resolver problemas baseados em dados estruturados**

**Descrição:**
> Descrever passo a passo um algoritmo, utilizando linguagem natural, para processar informações contidas em registros (base de dados simples). Essa competência envolve compreender a estrutura dos dados e planejar uma sequência lógica de ações para gerar resultados.

**KS (Conhecimento / Skill):**
* Estrutura de dados e registros | **Compreender**
* Descrição de algoritmos em linguagem natural | **Aplicar**
* Operadores lógicos e condicionais | **Aplicar**

**Disposições (D):**
* Organizado, preciso, analítico.

**BNCC associada:**

* **EF04CO03** – Criar e simular algoritmos com repetições simples e aninhadas, em linguagem oral, escrita ou pictográfica.
* **EF69CO03** – Descrever soluções de problemas utilizando estruturas lógicas.
* **EM13CO01** – Explorar e construir soluções para problemas utilizando abstrações computacionais.



### **C2 – Aplicar operadores lógicos e estruturas condicionais para filtrar e classificar dados**

**Descrição:**
> Usar condições e comparações para analisar registros de dados (ex.: sexo, presença de miopia), produzindo contagens e médias específicas. A competência envolve abstrair padrões, reconhecer atributos e decidir caminhos de execução.

**KS:**
* Condicionais e operadores lógicos | **Aplicar**
* Estruturas de decisão e filtragem de dados | **Analisar**

**Disposições (D):**
* Rigoroso, sistemático, atento a padrões.

**BNCC associada:**

* **EF04CO03** – Criar e simular algoritmos com repetições simples e aninhadas, em linguagem oral, escrita ou pictográfica.
* **EF69CO03** – Descrever soluções de problemas utilizando estruturas lógicas.
* **EM13CO01** – Explorar e construir soluções para problemas utilizando abstrações computacionais.
* **EF69CO04** – Decompor problemas complexos em partes menores para facilitar a solução.
* **EM13CO02** – Refinar soluções em diferentes níveis de abstração.



### **C3 – Generalizar soluções algorítmicas com reuso e modularização**

**Descrição:**
> Construir algoritmos reutilizando estruturas anteriores, aplicando o princípio de generalização. O estudante refatora trechos repetidos em funções conceituais (ex.: contagem por sexo, cálculo de média), consolidando a compreensão de *padrões de solução*.

**KS:**
* Reuso de estruturas algorítmicas | **Analisar**
* Modularização de soluções | **Criar**
* Organização de pseudocódigo | **Aplicar**

**Disposições (D):**
* Sistemático, reflexivo, colaborativo.

**BNCC associada:**

* **EM13CO01** – Reutilizar e refinar abstrações computacionais.
* **EF04CO03** – Criar e simular algoritmos com repetições simples e aninhadas, em linguagem oral, escrita ou pictográfica.
* **EF69CO03** – Descrever soluções de problemas utilizando estruturas lógicas.
* **EM13CO01** – Explorar e construir soluções para problemas utilizando abstrações computacionais.
* **EF69CO04** – Decompor problemas complexos em partes menores para facilitar a solução.
* **EM13CO02** – Refinar soluções em diferentes níveis de abstração.
* * **Competência Geral 5** – Desenvolver projetos e soluções de forma colaborativa.



### **C4 – Criar algoritmos complexos com múltiplas condições e combinações lógicas**

**Descrição:**
> Elaborar algoritmos capazes de processar múltiplos atributos e interseções de condições (ex.: alunos com Miopia e Astigmatismo). A competência exige síntese, abstração de padrões e avaliação de eficiência.

**KS:**

* Combinações condicionais (E, OU, NÃO) | **Analisar / Avaliar**
* Estruturas aninhadas e repetitivas | **Criar**
* Avaliação de consistência e eficiência | **Avaliar**

**Disposições (D):**
* Criativo, persistente, crítico.

**BNCC associada:**

* **EM13CO01** – Reutilizar e refinar abstrações computacionais.
* **EF04CO03** – Criar e simular algoritmos com repetições simples e aninhadas, em linguagem oral, escrita ou pictográfica.
* **EF69CO03** – Descrever soluções de problemas utilizando estruturas lógicas.
* **EM13CO01** – Explorar e construir soluções para problemas utilizando abstrações computacionais.
* **EF69CO04** – Decompor problemas complexos em partes menores para facilitar a solução.
* **EM13CO02** – Refinar soluções em diferentes níveis de abstração.
* * **Competência Geral 4** – Construir conhecimento com técnicas e tecnologias computacionais.
* * **Competência Geral 5** – Desenvolver projetos e soluções de forma colaborativa.
