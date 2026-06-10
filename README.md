# 📓 Miniguia de Estudos: Introdução à Linguagem de Programação Python

## 📝 Contexto e Objetivos
Este repositório foi desenvolvido como parte de um desafio prático para a **Refatoração e Aprendizagem Ativa da DIO (Digital Innovation One)**. O objectivo principal é aplicar o conceito de curadoria de conteúdo utilizando o **NotebookLM** da Google para adquirir, organizar e aprofundar conhecimentos sobre os fundamentos da linguagem Python.

* **Tema Escolhido:** Introdução à Linguagem de Programação Python.
* **Objetivo de Estudo:** Compreender a sintaxe básica, as estruturas de dados fundamentais (listas, tuplas, dicionários) e as características que tornam o Python uma das linguagens mais populares do mundo (como legibilidade e multiparadigma).

---

## 📚 Curadoria de Fontes (Top 5 Fontes Abertas)
Para garantir a qualidade do conhecimento gerado pela IA, o NotebookLM foi alimentado com as seguintes fontes oficiais, abertas e complementares:

1. **Documentação Oficial do Python (Tutorial em PT-BR)** - O guia definitivo e oficial para entender a sintaxe e a filosofia da linguagem. Disponível em: [docs.python.org](https://docs.python.org/pt-br/3/tutorial/index.html)
2. **Apostila Python e Orientação a Objetos (Caelum/Alura)** - Material didático aberto com foco prático em lógica de programação e fundamentos orientados a objetos. Disponível em: [alura.com.br/apostila-python](https://www.alura.com.br/apostila-python-orientacao-a-objetos)
3. **Curso de Python do Professor Gustavo Guanabara (Mundo 1 - Curso em Vídeo)** - Material de apoio textual e roteiros práticos amplamente recomendados para iniciantes. Disponível em: [cursoemvideo.com](https://www.cursoemvideo.com/curso/python-3-mundo-1/)
4. **Wiki Python Brasil (Seção de Exercícios e Conceitos)** - Repositório mantido pela comunidade brasileira com explicações práticas e estruturas de lógica. Disponível em: [python.org.br](https://python.org.br/)
5. **Livro Aberto - Computação Científica com Python (IF-UFRJ)** - Um livro didático completo e gratuito em formato PDF focado no aprendizado dos fundamentos da linguagem. Disponível em: [if.ufrj.br (PDF Oficial)](https://www.if.ufrj.br/~sandra/InfoEnsino/python_flavio07.pdf)

---

## 🧠 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)
Durante a interação com o NotebookLM, o foco foi extrair respostas técnicas e didáticas, documentando a evolução da abordagem para refinar os resultados gerados pela IA.

### 🧪 Teste 1: Abordagem Direta (Superficial)
* **Prompt:** *"O que é Python e como funcionam as variáveis?"*
* **Resposta Obtida da IA:** O Python foi definido como uma linguagem poderosa, versátil e de sintaxe clara, ideal para scripts e desenvolvimento ágil, destacando características como Orientação a Objetos, Multiplataforma e Extensibilidade. Sobre as variáveis, explicou que são identificadores que fazem referência a objetos na memória através da atribuição com o sinal de igual (`=`), seguindo regras de *case-sensitivity* e palavras reservadas.
* **Troubleshooting:** Embora a resposta tenha sido correta e abordado pontos cruciais como a tipagem dinâmica e forte, percebi que para um guia de estudos aprofundado, faltava um exemplo prático de código que tangibilizasse o erro de tipagem e as boas práticas para iniciantes.

### 🚀 Teste 2: Abordagem Restritiva e Estruturada (Sucesso)
* **Prompt:** *"Com base estritamente no tutorial oficial do Python e nos materiais fornecidos, explique o conceito de tipagem dinâmica e forte. Forneça um exemplo de código em texto para ilustrar como o Python lida com isso e liste os cuidados que um iniciante deve ter."*
* **Resposta Obtida da IA:** O NotebookLM refinou a explicação, trazendo o conceito de inferência de tipo (onde o interpretador determina o tipo automaticamente) combinado com a restrição da tipagem forte (bloqueio de misturas automáticas). A IA gerou o seguinte cenário prático:

```python
animal = 'Hamster 1 '
peso = 98

# A operação direta abaixo gerará um erro, pois o Python não concatena texto com número implicitamente:
# resultado = animal + ' : ' + peso + ' gramas'

# Erro gerado pelo Python: 
# TypeError: cannot concatenate 'str' and 'int' objects

# Solução usando formatação para converter o número inteiro em string:
resultado = '%s : %s gramas' % (animal, peso)
# Retorno: 'Hamster 1 : 98 gramas'

```
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


