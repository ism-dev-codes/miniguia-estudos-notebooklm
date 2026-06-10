# 📓 Miniguia de Estudos: Introdução à Linguagem de Programação Python

## 📝 Contexto e Objetivos
Este repositório foi desenvolvido como parte de um desafio prático para a **Refatoração e Aprendizagem Ativa da DIO (Digital Innovation One)**. O objetivo principal é aplicar o conceito de curadoria de conteúdo utilizando o **NotebookLM** da Google para sintetizar, organizar e aprofundar conhecimentos sobre os fundamentos da linguagem Python.

* **Tema Escolhido:** Introdução à Linguagem de Programação Python.
* **Objetivo de Estudo:** Compreender a sintaxe básica, as estruturas de dados fundamentais (listas, tuplas, dicionários) e as características que tornam o Python uma das linguagens mais populares do mundo (como legibilidade e multiparadigma).

---

## 📚 Curadoria de Fontes (Top 5 Fontes Abertas)
Para garantir a qualidade do conhecimento gerado pela IA, o NotebookLM foi alimentado com as seguintes fontes oficiais, abertas e complementares:

1. **Documentação Oficial do Python (Tutorial em PT-BR)** - O guia definitivo e oficial para entender a sintaxe e a filosofia da linguagem. Disponível em: [docs.python.org](https://docs.python.org/pt-br/3/tutorial/index.html)
2. **Apostila Python e Orientação a Objetos (Caelum/Alura)** - Material didático aberto com foco prático em lógica de programação e fundamentos orientados a objetos. Disponível em: [alura.com.br/apostila-python](https://www.alura.com.br/apostila-python-orientacao-a-objetos)
3. **Curso de Python do Professor Gustavo Guanabara (Mundo 1 - Curso em Vídeo)** - Material de apoio textual e roteiros práticos amplamente recomendados para iniciantes. Disponível em: [cursoemvideo.com](https://www.cursoemvideo.com/curso/python-3-mundo-1/)
4. **Wiki Python Brasil (Seção de Exercícios e Conceitos)** - Repositório mantido pela comunidade brasileira com explicações práticas e estruturas de lógica. Disponível em: [python.org.br](https://python.org.br/)
5. **Introdução à Programação em Python (UFRGS)** - Notas de aula e material textual de introdução à ciência da computação mantido pela Universidade Federal do Rio Grande do Sul. Disponível em: [ufrgs.br](https://www.ufrgs.br/reamat/ComputacaoCientifica/livro/cc-com-python.html)

---

## 🧠 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)
Durante a interação com o NotebookLM, o foco foi extrair respostas técnicas, porém didáticas, evitando explicações genéricas de internet e focando no ecossistema das fontes fornecidas.

### 🧪 Teste 1: Abordagem Direta (Superficial)
* **Prompt:** *"O que é Python e como funcionam as variáveis?"*
* **Resultado:** A IA explicou o que era Python de forma muito rasa (estilo Wikipédia) e esqueceu de citar as peculiaridades da linguagem, como a tipagem dinâmica.
* **Troubleshooting:** Percebi que o prompt aberto dava margem para respostas superficiais. Ajustei a abordagem para exigir maior rigor técnico com base restrita nos documentos enviados.

### 🚀 Teste 2: Abordagem Restritiva e Estruturada (Sucesso)
* **Prompt:** *"Com base estritamente no tutorial oficial do Python e nos materiais fornecidos, explique o conceito de tipagem dinâmica e forte. Forneça um exemplo de código em texto para ilustrar como o Python lida com isso e liste os cuidados que um iniciante deve ter."*
* **Resultado:** O NotebookLM trouxe uma resposta precisa: explicou que Python não exige declaração de tipo (dinâmica), mas não permite operações inválidas entre tipos diferentes sem conversão (forte). Trouxe exemplos práticos de erros comuns (como tentar somar `string` com `int`).

---

## 🏆 Miniguia de Estudo (Entrega Final)

### 📌 Resumo Estruturado dos Fundamentos de Python

* **Filosofia Zen do Python:** Python prioriza a legibilidade do código sobre a complexidade. O famoso *"bonito é melhor que feio"* se traduz na sintaxe limpa e no uso obrigatório de **indentação** para definir blocos de código (substituindo as chaves `{}` ou palavras-chave como `end` de outras linguagens).
* **Tipagem Dinâmica e Forte:** Em Python, você não precisa dizer que uma variável é um número ou um texto, a linguagem descobre sozinha em tempo de execução (dinâmica). Porém, ela é forte: o código `“Ano: ” + 2026` quebrará com um erro de tipo (`TypeError`), exigindo a conversão explícita `“Ano: ” + str(2026)`.
* **Estruturas de Dados Nativas:**
  * **Listas (`[]`):** Mutáveis, ordenadas, aceitam dados de vários tipos.
  * **Tuplas (`()`):** Imutáveis (uma vez criadas, não mudam), ótimas para segurança de dados.
  * **Dicionários (`{}`):** Estruturas de Chave-Valor, extremamente rápidas para busca de informações mapeadas.

### 📖 Glossário de Conceitos Aprendidos
* **Indentação:** Espaçamento no início de uma linha de código. Em Python, ela não é apenas estética, mas sim a forma como a linguagem entende onde começa e termina uma função, condição (`if`) ou estrutura de repetição.
* **Interpretada:** Diferente de linguagens compiladas (como C++), o código Python é lido e executado linha por linha por um programa chamado interpretador, o que acelera o processo de desenvolvimento e teste.
* **PEP 8:** O guia de estilo oficial para o código Python. Ele define as boas práticas de formatação para que a comunidade escreva códigos legíveis e visualmente padronizados.
* **Garbage Collector:** Mecanismo automático do Python que limpa a memória do computador de forma inteligente, deletando variáveis e dados que não estão mais sendo usados pelo programa.

### 🔄 Prompts Reutilizáveis para Revisões Futuras
Guarde estes prompts no seu bloco de notas para usar no NotebookLM quando precisar revisar Python:

* `"Aja como um entrevistador técnico de Python. Crie 3 perguntas com níveis de dificuldade Fácil, Médio e Difícil sobre Estruturas de Dados baseadas exclusivamente nos textos enviados."`
* `"Crie um roteiro de estudos de 5 dias para revisar funções (def) e escopo de variáveis utilizando apenas os capítulos dos livros anexados."`
* `"Explique a diferença prática entre Listas e Tuplas usando uma metáfora do mundo real baseada na documentação fornecida."`

---

## 👨‍💻 Expert

<p>
    <img 
      align=left 
      margin=10 
      width=80 
      src="https://avatars.githubusercontent.com/u/105826184?v=4"
    />
    <p>&nbsp&nbsp&nbspIsmael Medeiros<br>
    &nbsp&nbsp&nbsp
    <a 
        href="https://github.com/ism-dev-codes">
        GitHub
    </a>
    &nbsp;|&nbsp;
    <a 
        href="https://www.linkedin.com/in/ismael-medeiros-5b2bb51ab/">
        LinkedIn
    </a>
    &nbsp;|&nbsp;
    <a 
        href="https://www.instagram.com/ismaelsmedeiros?igsh=YXA1OW1mNXhkNmVy">
        Instagram
    </a>
    &nbsp;|&nbsp;</p>
</p>
<br/><br/>
<p>
