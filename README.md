<p align="center">
  <a href="https://github.com/arthurspk/guiadevbrasil">
    <img src="./images/guia.png" alt="Guia Dev Brasil" width="160" height="160">
  </a>
  <h1 align="center">Guia de Algoritmos e Estruturas de Dados</h1>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/arthurspk/guiadealgoritmos?style=flat-square" alt="Stars">
  <img src="https://img.shields.io/github/forks/arthurspk/guiadealgoritmos?style=flat-square" alt="Forks">
  <img src="https://img.shields.io/github/last-commit/arthurspk/guiadealgoritmos?style=flat-square" alt="Último commit">
  <img src="https://img.shields.io/github/license/arthurspk/guiadealgoritmos?style=flat-square" alt="Licença">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square" alt="PRs Welcome">
</p>

> Guia completo de Algoritmos e Estruturas de Dados: trilhas, cursos, livros, canais, ferramentas e comunidades
> para você entrar e evoluir na área. Última revisão: setembro/2026.

## 🌍 Idiomas
🇧🇷 Português (você está aqui) · [🇺🇸 English](./translations/README.en.md)

## 📚 Sumário
- [🎯 Sobre este guia](#-sobre-este-guia)
- [🗺️ Roadmap](#-roadmap)
- [🚀 Por onde começar](#-por-onde-começar)
- [🎓 Cursos gratuitos](#-cursos-gratuitos)
- [💰 Cursos pagos](#-cursos-pagos)
- [📖 Documentação e apostilas](#-documentação-e-apostilas)
- [📚 Livros](#-livros)
- [🎥 Canais no YouTube](#-canais-no-youtube)
- [🎙️ Podcasts](#-podcasts)
- [📰 Sites, blogs e newsletters](#-sites-blogs-e-newsletters)
- [🛠️ Ferramentas](#-ferramentas)
- [🧪 Projetos práticos e desafios](#-projetos-práticos-e-desafios)
- [🏆 Programação competitiva](#-programação-competitiva)
- [👁️ Visualizadores](#-visualizadores)
- [🤖 IA na prática](#-ia-na-prática)
- [📜 Certificações](#-certificações)
- [💼 Carreira e vagas](#-carreira-e-vagas)
- [👥 Comunidades](#-comunidades)
- [🚨 Como contribuir](#-como-contribuir)
- [📄 Licença](#-licença)
- [💙 Apoie o projeto](#-apoie-o-projeto)

## 🎯 Sobre este guia
Algoritmos são receitas precisas para resolver problemas; estruturas de dados são as formas de organizar informação para que essas receitas sejam rápidas. Juntos, eles são a parte da programação que **não muda quando o framework muda**: o mesmo `HashMap`, a mesma busca binária e o mesmo Dijkstra estão por trás do banco de dados, do GPS, do compilador e do feed da rede social. É também o assunto central das entrevistas técnicas de big techs e o que separa "faz funcionar" de "funciona com um milhão de usuários".

Este guia é para quem está começando (sabe o básico de alguma linguagem) e para quem já programa mas nunca estudou o tema de forma estruturada. Os recursos em **português e gratuitos** vêm primeiro em cada seção; 💰 marca conteúdo pago, 🇺🇸 conteúdo em inglês e 🆕 material publicado ou atualizado entre 2024 e 2026. Todo link foi verificado na data da última revisão.

## 🗺️ Roadmap
- [roadmap.sh — Data Structures and Algorithms](https://roadmap.sh/datastructures-and-algorithms) — Roadmap visual e interativo da comunidade: complexidade, estruturas, ordenação, grafos e DP, com links por tópico. 🇺🇸
- [roadmap.sh — Computer Science](https://roadmap.sh/computer-science) — Currículo de Ciência da Computação para autodidatas; algoritmos e estruturas de dados são o eixo central. 🇺🇸
- [Coding Interview University (tradução PT-BR)](https://github.com/jwasham/coding-interview-university/blob/main/translations/README-ptbr.md) — Plano de estudos completo de CS que levou o autor a uma vaga na Amazon: ordem dos tópicos, vídeos e leituras, traduzido para português.
- [NeetCode Roadmap](https://neetcode.io/roadmap) — Árvore de dependências entre tópicos (arrays → dois ponteiros → ... → DP) com problemas selecionados para cada nó. 🇺🇸
- [OSSU — Computer Science](https://github.com/ossu/computer-science) — Graduação completa e gratuita em CS com cursos abertos; a trilha de algoritmos usa Princeton e MIT. 🇺🇸
- [kelvins/algorithms-and-data-structures](https://github.com/kelvins/algorithms-and-data-structures) — Repositório brasileiro com algoritmos e estruturas implementados em várias linguagens, organizados por tema — bom para ver o mesmo algoritmo em C, Python, Java e Go.

**Trilha resumida** (siga na ordem; cada etapa tem recursos nas seções abaixo):

1. **Lógica e uma linguagem** — variáveis, condições, laços, funções e recursão em Python, C, Java ou JavaScript. Sem isso, o resto não faz sentido.
2. **Complexidade** — notação Big-O, O(1)/O(log n)/O(n)/O(n log n)/O(n²), tempo × espaço, análise de laços e recorrências.
3. **Estruturas lineares** — arrays, strings, listas ligadas, pilhas, filas e deques; dois ponteiros e janela deslizante.
4. **Busca e ordenação** — busca binária; bubble/insertion/selection para entender, merge sort, quick sort e heap sort para usar; ordenação em tempo linear.
5. **Hashing** — tabelas hash, `dict`/`HashMap`/`Map`, colisões e quando o O(1) mente.
6. **Árvores e heaps** — árvores binárias, BST, percursos, árvores balanceadas (AVL/rubro-negra, só o conceito), heaps e filas de prioridade, tries.
7. **Grafos** — representação, BFS/DFS, ordenação topológica, Dijkstra, união-busca (union-find), árvore geradora mínima.
8. **Técnicas de projeto** — recursão e backtracking, dividir e conquistar, guloso e programação dinâmica.
9. **Avançado (opcional)** — árvores de segmentos e Fenwick, algoritmos de strings (KMP, Z, sufixos), fluxo em redes, NP-completude.

## 🚀 Por onde começar
1. **Aprenda a programar primeiro.** Se ainda não sabe, faça o [Curso de Algoritmos e Lógica de Programação](https://www.youtube.com/playlist?list=PLHz_AreHm4dmSj0MHol_aoNYCSGFqvfXV) do Curso em Vídeo ou o [Introdução à Ciência da Computação com Python (USP)](https://www.coursera.org/learn/ciencia-computacao-python-conceitos).
2. **Entenda Big-O em uma tarde:** leia [Notação Big O explicada com exemplos](https://www.freecodecamp.org/portuguese/news/notacao-big-o-explicada-com-exemplos/) e deixe o [Big-O Cheat Sheet](https://www.bigocheatsheet.com/) nos favoritos.
3. **Leia um livro leve:** [Entendendo Algoritmos](https://novatec.com.br/livros/entendendo-algoritmos-2ed/) (ilustrado, em português) é o melhor primeiro livro da área.
4. **Faça um curso completo em português:** [Estrutura de Dados em C (Programação Descomplicada)](https://www.youtube.com/playlist?list=PL8iN9FQ7_jt6H5m4Gm0H89sybzR9yaaka), [Estrutura de Dados e Algoritmos Java (Loiane)](https://www.youtube.com/playlist?list=PLGxZ4Rq3BOBrgumpzz-l8kFMw2DLERdxi) ou a disciplina da [UNIVESP](https://www.youtube.com/playlist?list=PLxI8Can9yAHf8k8LrUePyj0y3lLpigGcl).
5. **Veja cada estrutura funcionando** no [VisuAlgo](https://visualgo.net/en) e rode seu próprio código passo a passo no [Python Tutor](https://pythontutor.com/).
6. **Implemente você mesmo** lista ligada, pilha, fila, BST, heap e tabela hash, do zero, sem biblioteca — e compare com [kelvins/algorithms-and-data-structures](https://github.com/kelvins/algorithms-and-data-structures).
7. **Pratique todo dia:** comece pelos problemas fáceis do [HackerRank](https://www.hackerrank.com/domains/data-structures) e da [Neps Academy](https://neps.academy/br); depois, o [CSES Problem Set](https://cses.fi/problemset/) por tópico.
8. **Aprofunde com o MIT:** [6.006 Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/) é o curso definitivo — e, se o objetivo for entrevista, siga para o [NeetCode Roadmap](https://neetcode.io/roadmap).

Seu primeiro algoritmo "de verdade" — busca binária em Python, O(log n):

```python
def busca_binaria(lista, alvo):
    esq, dir = 0, len(lista) - 1
    while esq <= dir:
        meio = (esq + dir) // 2
        if lista[meio] == alvo:
            return meio            # achou: devolve a posição
        if lista[meio] < alvo:
            esq = meio + 1         # o alvo está à direita
        else:
            dir = meio - 1         # o alvo está à esquerda
    return -1                      # não está na lista

print(busca_binaria([2, 5, 8, 12, 16, 23, 38, 56, 72, 91], 23))  # 5
```

Numa lista de 1 milhão de itens ordenados, a busca linear faz até 1.000.000 comparações; a binária faz no máximo 20. Essa diferença é o motivo de estudar este guia.

## 🎓 Cursos gratuitos
### Em português
- [Curso de Algoritmos e Lógica de Programação (Curso em Vídeo)](https://www.youtube.com/playlist?list=PLHz_AreHm4dmSj0MHol_aoNYCSGFqvfXV) — Curso do Gustavo Guanabara para quem nunca programou: variáveis, condições, repetições e vetores em português claro.
- [UNIVESP — Estrutura de Dados (Engenharia de Computação)](https://www.youtube.com/playlist?list=PLxI8Can9yAHf8k8LrUePyj0y3lLpigGcl) — Disciplina completa da universidade pública paulista no YouTube: listas, pilhas, filas, árvores e grafos.
- [UNICAMP — MC202 Estruturas de Dados (aulas gravadas)](https://www.youtube.com/playlist?list=PL5TPkym335qzgzl0jW6Xf4XITmCofzOCy) — Gravações das aulas de MC202 do Instituto de Computação da UNICAMP reunidas em playlist.
- [UNICAMP — MC202 Estruturas de Dados (slides e vídeos do Prof. Rafael Schouery)](https://www.ic.unicamp.br/~rafael/mc202.html) — Página do professor com slides de todas as aulas e vídeos correspondentes, em C: ponteiros, listas, árvores, hashing e grafos.
- [UNICAMP — MC102 Algoritmos e Programação de Computadores](https://www.ic.unicamp.br/~mc102/) — Material aberto da disciplina introdutória da UNICAMP: slides, exercícios e referências para quem está começando.
- [USP e-Aulas — Algoritmos e Estruturas de Dados (PCS3110)](https://eaulas.usp.br/portal/course.action?course=8049) — 49 vídeos do Prof. Romero Tori (Poli-USP): análise de algoritmos, listas, hash, heaps, ordenação e grafos.
- [Coursera — Introdução à Ciência da Computação com Python Parte 1 (USP)](https://www.coursera.org/learn/ciencia-computacao-python-conceitos) — Curso da USP que ensina lógica e algoritmos básicos em Python; gratuito para assistir (certificado é pago).
- [Coursera — Introdução à Ciência da Computação com Python Parte 2 (USP)](https://www.coursera.org/learn/ciencia-computacao-python-conceitos-2) — Continuação: recursão, ordenação, busca e complexidade, ainda com foco em quem está começando.
- [Estrutura de Dados em Linguagem C — Curso Completo (Programação Descomplicada)](https://www.youtube.com/playlist?list=PL8iN9FQ7_jt6H5m4Gm0H89sybzR9yaaka) — Mais de 100 aulas do Prof. André Backes (UFU) implementando cada estrutura em C, do zero.
- [Curso Estrutura de Dados e Algoritmos Java (Loiane Groner)](https://www.youtube.com/playlist?list=PLGxZ4Rq3BOBrgumpzz-l8kFMw2DLERdxi) — Curso gratuito com certificado: pilhas, filas, listas, árvores, ordenação e busca em Java, com código no GitHub.
- [Repositório do curso de Estrutura de Dados e Algoritmos Java](https://github.com/loiane/estrutura-dados-algoritmos-java) — Código-fonte de cada aula da Loiane, organizado por estrutura.
- [Estrutura de Dados (Programação Dinâmica)](https://www.youtube.com/playlist?list=PL5TJqBvpXQv5Bb71AE5Cd_kB5rNsfU4Cp) — Playlist do canal de Kizzy Terra e Hallison Paz explicando estruturas com Python e muita didática visual.
- [Estruturas de Dados e Algoritmos (Bóson Treinamentos)](https://www.youtube.com/playlist?list=PLucm8g_ezqNpHdoSlPrLMB1Ga8dBrNRsz) — Série do Fábio dos Reis com conceitos e implementações passo a passo.
- [Aprenda Estrutura de Dados e Algoritmos (DIO)](https://www.dio.me/courses/aprenda-o-que-sao-estrutura-de-dados-e-algoritmos) — Curso gratuito com certificado: listas, pilhas, filas, árvores, tabela hash e grafos.
- [Curso de Estrutura de Dados (Cursa)](https://cursa.com.br/curso-de-estrutura-de-dados/207) — Curso online gratuito com certificado digital ao concluir, teoria e prática.
- [Neps Academy](https://neps.academy/br) — Plataforma brasileira gratuita com trilhas de algoritmos, estruturas de dados e programação competitiva, com juiz online integrado.
- [Introdução à Programação Competitiva (Neps Academy)](https://neps.academy/br/course/introducao-a-programacao-competitiva) — Curso de entrada da Neps: como funcionam os juízes online, leitura de entrada, complexidade e primeiros problemas.

### Em inglês
- [MIT 6.006 — Introduction to Algorithms (OCW, 2020)](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/) — O curso de algoritmos mais famoso do mundo, com vídeos, notas, problemas e provas resolvidas. 🇺🇸
- [MIT 6.006 — playlist das aulas no YouTube](https://www.youtube.com/playlist?list=PLUl4u3cNGP63EdVPNLG3ToM6LaEUuStEY) — As 32 aulas de 6.006 (2020) no canal oficial do MIT OpenCourseWare. 🇺🇸
- [MIT 6.046J — Design and Analysis of Algorithms (OCW)](https://ocw.mit.edu/courses/6-046j-design-and-analysis-of-algorithms-spring-2015/) — Sequência de 6.006: dividir e conquistar, DP avançada, fluxo em redes, NP-completude e algoritmos aproximados. 🇺🇸
- [MIT 6.042J — Mathematics for Computer Science (OCW)](https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-spring-2015/) — A matemática discreta por trás dos algoritmos: provas, indução, grafos, contagem e probabilidade. 🇺🇸
- [Algorithms, Part I (Princeton — Coursera)](https://www.coursera.org/learn/algorithms-part1) — Curso de Sedgewick e Wayne: union-find, ordenação, árvores balanceadas e hashing em Java; gratuito para assistir. 🇺🇸
- [Algorithms, Part II (Princeton — Coursera)](https://www.coursera.org/learn/algorithms-part2) — Continuação: grafos, caminhos mínimos, fluxo máximo, strings e compressão. 🇺🇸
- [Algorithms Specialization (Stanford — Coursera)](https://www.coursera.org/specializations/algorithms) — Quatro cursos de Tim Roughgarden com foco em análise e projeto; assistir é gratuito, certificado é pago. 🇺🇸
- [Data Structures and Algorithms Specialization (UC San Diego — Coursera)](https://www.coursera.org/specializations/data-structures-algorithms) — Especialização prática com juiz automático em várias linguagens, do básico a strings e grafos avançados. 🇺🇸
- [Khan Academy — Algorithms](https://www.khanacademy.org/computing/computer-science/algorithms) — Introdução suave (com Dartmouth) a busca binária, ordenação, recursão e grafos, com exercícios interativos. 🇺🇸
- [CS50x 2026 (Harvard)](https://cs50.harvard.edu/x/) — Introdução à Ciência da Computação de Harvard; as semanas de C, algoritmos e estruturas de dados são a base perfeita. 🆕 🇺🇸
- [Data Structures Easy to Advanced (William Fiset — freeCodeCamp)](https://www.youtube.com/watch?v=RBSGKlAvoiM) — 8 horas de um engenheiro do Google implementando cada estrutura, com análise de complexidade. 🇺🇸
- [Algorithms and Data Structures Tutorial — Full Course for Beginners (freeCodeCamp)](https://www.youtube.com/watch?v=8hly31xKli0) — Curso de 5 horas para iniciantes, em Python, cobrindo busca, ordenação, listas, árvores e grafos. 🇺🇸
- [Codeforces EDU (ITMO Academy)](https://codeforces.com/edu/courses) — Cursos gratuitos em vídeo com problemas: busca binária, dois ponteiros, árvores de segmentos, sufixos e mais. 🇺🇸
- [USACO Guide](https://usaco.guide/) — Trilha gratuita e completa de programação competitiva (Bronze → Platinum) com problemas para cada módulo. 🇺🇸
- [Intro to Algorithms (Udacity)](https://www.udacity.com/course/intro-to-algorithms--cs215) — Curso gratuito que usa redes sociais como fio condutor para ensinar grafos e análise de algoritmos. 🇺🇸

## 💰 Cursos pagos
- [Learn Data Structures and Algorithms with Python (Codecademy)](https://www.codecademy.com/learn/learn-data-structures-and-algorithms-with-python) — Trilha interativa no navegador, com certificado no plano Pro. 💰 🇺🇸
- [Grokking the Coding Interview Patterns (Educative)](https://www.educative.io/courses/grokking-coding-interview) — Ensina os ~20 padrões que resolvem a maioria das questões de entrevista (sliding window, two pointers, etc.). 🆕 💰 🇺🇸
- [AlgoExpert](https://www.algoexpert.io/) — 160+ questões com vídeo-explicações e ambiente de código, voltado a entrevistas. 💰 🇺🇸
- [NeetCode Courses (Pro)](https://neetcode.io/courses) — Cursos de algoritmos, DP avançada e system design do criador do NeetCode 150. 💰 🇺🇸
- [Data Structures and Algorithms Nanodegree (Udacity)](https://www.udacity.com/course/data-structures-and-algorithms-nanodegree--nd256) — Programa com projetos revisados por mentores, em Python. 💰 🇺🇸

## 📖 Documentação e apostilas
- [Projeto de Algoritmos em linguagem C (Paulo Feofiloff, IME-USP)](https://www.ime.usp.br/~pf/algoritmos/) — Apostila clássica e gratuita do IME-USP: recursão, busca, ordenação, listas, árvores e grafos em C, com exercícios.
- [Curso de Análise de Algoritmos (Paulo Feofiloff, IME-USP)](https://www.ime.usp.br/~pf/analise_de_algoritmos/) — Notas de aula em português sobre notação assintótica, recorrências, ordenação ótima e programação dinâmica.
- [Curso de Estruturas de Dados (Feofiloff, baseado em Sedgewick e Wayne)](https://www.ime.usp.br/~pf/estruturas-de-dados/) — Apostila em português que acompanha o livro *Algorithms* de Sedgewick e Wayne, com implementações em Java.
- [Linguagem C Descomplicada — índice de Estrutura de Dados](https://programacaodescomplicada.wordpress.com/indice/estrutura-de-dados/) — Índice escrito das aulas do Prof. André Backes, com o código de cada estrutura.
- [Material de Programação Competitiva (UnBalloon — UnB)](https://github.com/UnBalloon/programacao-competitiva) — Tutoriais em português do grupo da UnB sobre as técnicas e estruturas usadas na Maratona.
- [Livreto FACOMpetindo (UFMS)](https://facompetindo.gitbook.io/facompetindo) — Guia introdutório em português para competições, com foco na OBI, em C++ e Python.
- [NOIC — Materiais de Informática](https://noic.com.br/materiais-informatica/) — Aulas escritas em português para a OBI, organizadas por nível, mantidas por ex-olímpicos.
- [Algorithms for Competitive Programming (cp-algorithms)](https://cp-algorithms.com/) — A referência técnica de programação competitiva: cada algoritmo com prova, código e problemas. 🇺🇸
- [Algorithms, 4th Edition — booksite (Sedgewick e Wayne)](https://algs4.cs.princeton.edu/home/) — Site do livro de Princeton com todo o código Java, resumos e exercícios de cada capítulo, gratuito. 🇺🇸
- [DSA Tutorial (GeeksforGeeks)](https://www.geeksforgeeks.org/dsa/dsa-tutorial-learn-data-structures-and-algorithms/) — A enciclopédia de DSA: artigo para praticamente todo algoritmo, com código em várias linguagens. 🇺🇸
- [Learn DSA (Programiz)](https://www.programiz.com/dsa) — Tutoriais curtos e visuais, ótimos para uma primeira passada por cada estrutura. 🇺🇸
- [DSA Tutorial (W3Schools)](https://www.w3schools.com/dsa/) — Tutorial passo a passo com simulações no navegador e exercícios. 🇺🇸
- [Big-O Cheat Sheet](https://www.bigocheatsheet.com/) — Tabela de complexidade de tempo e espaço das principais estruturas e algoritmos de ordenação. 🇺🇸
- [Study cheatsheets de algoritmos (Tech Interview Handbook)](https://www.techinterviewhandbook.org/algorithms/study-cheatsheet/) — Resumo por tópico do que cai em entrevista: pegadinhas, técnicas e problemas essenciais. 🇺🇸

## 📚 Livros
- [Entendendo Algoritmos — 2ª edição (Aditya Bhargava, Novatec)](https://novatec.com.br/livros/entendendo-algoritmos-2ed/) — O livro ilustrado mais recomendado para iniciantes, em português; nova edição com árvores, NP-completude e Python 3. 🆕
- [Algoritmos: Teoria e Prática — 4ª edição (Cormen, Leiserson, Rivest e Stein, GEN)](https://www.grupogen.com.br/livro-algoritmos-thomas-cormen-9788595159907) — Tradução oficial do CLRS, a bíblia da área; edição de 2024 com capítulos novos sobre grafos bipartidos e machine learning. 🆕
- [Estruturas de Dados e Algoritmos com JavaScript — 2ª edição (Loiane Groner, Novatec)](https://novatec.com.br/livros/estruturas-de-dados-algoritmos-em-javascript-2ed/) — Cada estrutura implementada em JavaScript moderno, por uma autora brasileira.
- [Lógica de Programação e Algoritmos com JavaScript — 2ª edição (Edécio Iepsen, Novatec)](https://novatec.com.br/livros/logica-programacao-algoritmos-com-javascript-2ed/) — Para quem está no zero: lógica, estruturas de controle e primeiros algoritmos com JavaScript.
- [Grokking Algorithms, 2nd Edition (Aditya Bhargava, Manning)](https://www.manning.com/books/grokking-algorithms-second-edition) — Edição original em inglês de *Entendendo Algoritmos*, lançada em 2024. 🆕 🇺🇸
- [Algorithms, 4th Edition (Sedgewick e Wayne)](https://algs4.cs.princeton.edu/home/) — O livro-texto de Princeton, com código Java e o material do curso no Coursera. 🇺🇸
- [The Algorithm Design Manual (Steven Skiena)](https://www.algorist.com/) — Foco em *como* projetar algoritmos na prática, com um catálogo de problemas famoso. 🇺🇸
- [Algorithms (Jeff Erickson) — gratuito](https://jeffe.cs.illinois.edu/teaching/algorithms/) — Livro-texto completo e gratuito (Creative Commons) da Universidade de Illinois, com centenas de exercícios. 🇺🇸
- [Open Data Structures (Pat Morin) — gratuito](https://opendatastructures.org/) — Livro aberto sobre estruturas de dados, com edições em Java, C++ e pseudocódigo. 🇺🇸
- [Competitive Programmer's Handbook (Antti Laaksonen) — gratuito](https://cses.fi/book/book.pdf) — PDF gratuito do autor: o livro de referência para começar em programação competitiva, em C++. 🇺🇸
- [Competitive Programming 4 (Steven e Felix Halim)](https://cpbook.net/) — O manual mais completo para Maratona/ICPC, com milhares de problemas classificados. 💰 🇺🇸
- [Cracking the Coding Interview (Gayle Laakmann McDowell)](https://www.crackingthecodinginterview.com/) — 189 questões de entrevista com soluções, e o processo das big techs explicado. 💰 🇺🇸
- [Elements of Programming Interviews (Aziz, Lee e Prakash)](https://elementsofprogramminginterviews.com/) — Coleção mais difícil que o CtCI, com versões em Python, Java e C++. 💰 🇺🇸

## 🎥 Canais no YouTube
### Em português
- [Curso em Vídeo](https://www.youtube.com/@CursoemVideo) — Canal do Gustavo Guanabara; o curso de Algoritmos é a porta de entrada de milhões de brasileiros.
- [Programação Dinâmica](https://www.youtube.com/@pgdinamica) — Kizzy Terra e Hallison Paz explicam algoritmos, estruturas e matemática com clareza rara.
- [Loiane Groner](https://www.youtube.com/@loianegroner) — Autora do livro de estruturas em JavaScript; cursos completos e gratuitos em Java.
- [Fabio Akita](https://www.youtube.com/@Akita) — Vídeos longos e profundos sobre ciência da computação, hardware e o porquê das coisas.
- [Árvores: O Começo de TUDO | Estruturas de Dados e Algoritmos (Fabio Akita)](https://www.youtube.com/watch?v=9GdesxWtOgs) — Vídeo da trilogia de estruturas de dados do Akita: por que árvores estão em tudo, do banco de dados ao compilador.
- [Programação Descomplicada](https://www.youtube.com/@progdescomplicada) — Prof. André Backes (UFU): C, estrutura de dados e algoritmos, aula por aula.
- [Bóson Treinamentos](https://www.youtube.com/@bosontreinamentos) — Fábio dos Reis com cursos de lógica, C, Python e estruturas de dados.
- [Professor Douglas Maioli](https://www.youtube.com/@ProfessorDouglasMaioli) — Curso de estrutura de dados em C++ e vídeos de programação para iniciantes.
- [UNIVESP](https://www.youtube.com/@univesptv) — Canal oficial da universidade virtual paulista com disciplinas inteiras gravadas.
- [Neps Academy](https://www.youtube.com/@nepsacademy) — Aulas e resoluções de problemas de programação competitiva em português.
- [Big O Notation fácil de entender! (Attekita Dev)](https://www.youtube.com/watch?v=FR44uWofQ7o) — Complexidade de tempo e espaço explicada em 15 minutos, com exemplos de código.
- [Big O Notation — explicação para entrevistas (Augusto Galego)](https://www.youtube.com/watch?v=g-hIXvdDeZk) — Como falar de complexidade numa entrevista técnica, por quem já entrevistou em big tech.

### Em inglês
- [Abdul Bari — Algorithms](https://www.youtube.com/playlist?list=PLDN4rrl48XKpZkf03iYFl-O29szjTrs_O) — Playlist de 80+ aulas de quadro-negro cobrindo um curso universitário inteiro de algoritmos. 🇺🇸
- [mycodeschool — Data structures](https://www.youtube.com/playlist?list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P) — A playlist clássica de estruturas de dados em C/C++, ainda a mais clara para listas, pilhas e árvores. 🇺🇸
- [WilliamFiset — Data structures playlist](https://www.youtube.com/playlist?list=PLDV1Zeh2NRsB6SWUrDFW2RmDotAfPbeHu) — Estruturas avançadas (Fenwick, union-find, heaps indexados) com código no GitHub. 🇺🇸
- [NeetCode](https://www.youtube.com/@NeetCode) — Soluções curtas e visuais para os problemas de entrevista mais comuns. 🇺🇸
- [NeetCode — Leetcode BLIND-75 Solutions](https://www.youtube.com/playlist?list=PLot-Xpze53ldVwtstag2TL4HQhAnC8ATf) — As 75 questões mais cobradas em entrevista, resolvidas uma a uma. 🇺🇸
- [MIT OpenCourseWare](https://www.youtube.com/@mitocw) — Canal oficial com 6.006, 6.046 e 6.042 completos. 🇺🇸
- [Errichto Algorithms](https://www.youtube.com/@Errichto) — Um dos maiores competidores do mundo ensinando técnicas e resolvendo contests ao vivo. 🇺🇸
- [Reducible](https://www.youtube.com/@Reducible) — Animações no estilo 3Blue1Brown para algoritmos: FFT, DP, grafos e mais. 🇺🇸
- [Back To Back SWE](https://www.youtube.com/@BackToBackSWE) — Explicações longas e cuidadosas de problemas de entrevista, com intuição antes do código. 🇺🇸
- [Colin Galen](https://www.youtube.com/@ColinGalen) — Como pensar em programação competitiva: mentalidade, treino e resolução de problemas. 🇺🇸
- [Tushar Roy — Coding Made Simple](https://www.youtube.com/@tusharroy2525) — Programação dinâmica e grafos explicados com tabelas desenhadas passo a passo. 🇺🇸

## 🎙️ Podcasts
- [Hipsters Ponto Tech #186 — Algoritmos e estrutura de dados](https://www.hipsters.tech/algoritmos-e-estrutura-de-dados-hipsters-186/) — Episódio com engenheiros de Amazon e outras empresas: precisa mesmo saber algoritmos para trabalhar com programação?
- [Fronteiras da Engenharia de Software](https://fronteirases.github.io/) — Podcast brasileiro que traz pesquisadores para falar de engenharia de software em linguagem acessível.
- [ADSP: The Podcast (Algorithms + Data Structures = Programs)](https://adspthepodcast.com/) — Conor Hoekstra e Bryce Lelbach conversam semanalmente sobre algoritmos, linguagens e bibliotecas. 🇺🇸
- [Lex Fridman Podcast — Donald Knuth](https://lexfridman.com/donald-knuth/) — Conversa com o autor de *The Art of Computer Programming* sobre algoritmos, TeX e a vida. 🇺🇸
- [CoRecursive](https://corecursive.com/) — Histórias de bastidores de software, várias sobre algoritmos e estruturas que mudaram a indústria. 🇺🇸

## 📰 Sites, blogs e newsletters
- [Meus cursos gratuitos favoritos para aprender estruturas de dados e algoritmos a fundo (freeCodeCamp PT)](https://www.freecodecamp.org/portuguese/news/meus-cursos-gratuitos-favoritos-para-aprender-estruturas-de-dados-e-algoritmos-a-fundo/) — Artigo em português comparando os melhores cursos abertos de DSA.
- [Notação Big O explicada com exemplos (freeCodeCamp PT)](https://www.freecodecamp.org/portuguese/news/notacao-big-o-explicada-com-exemplos/) — O(1), O(n), O(log n) e O(n²) com exemplos de código, em português.
- [freeCodeCamp PT — tag Algoritmos](https://www.freecodecamp.org/portuguese/news/tag/algoritmos/) — Todos os artigos traduzidos do freeCodeCamp sobre algoritmos.
- [O que são estruturas de dados? (Alura)](https://www.alura.com.br/artigos/estruturas-de-dados-introducao) — Introdução em português a estruturas e algoritmos, com exemplos do dia a dia.
- [NOIC — Informática](https://noic.com.br/informatica/) — Notícias, materiais e simulados para a Olimpíada Brasileira de Informática.
- [Code Marathon — Como estudar para a Maratona de Programação](https://www.codemarathon.com.br/conteudos/introducao/como-estudar-para-maratona-de-programacao) — Site brasileiro com trilha de estudo e conteúdos para a Maratona SBC.
- [interviewing.io — Blog](https://interviewing.io/blog) — Dados reais de milhares de entrevistas técnicas: o que funciona e o que não funciona. 🇺🇸
- [Hello Interview — Data Structures and Algorithms](https://www.hellointerview.com/learn/code) — Guia de DSA para entrevistas escrito por ex-entrevistadores de Meta e Amazon. 🆕 🇺🇸
- [DEV Community — tag #algorithms](https://dev.to/t/algorithms) — Artigos da comunidade sobre algoritmos, muitos em português. 🇺🇸
- [Lista de algoritmos (Wikipedia)](https://en.wikipedia.org/wiki/List_of_algorithms) — Catálogo enciclopédico por área — para descobrir que o algoritmo que você precisa já existe. 🇺🇸

## 🛠️ Ferramentas
- [Visual Studio Code](https://code.visualstudio.com/) — Editor gratuito com depurador para C, C++, Python, Java e JavaScript — depurar passo a passo é a melhor forma de entender um algoritmo. 🇺🇸
- [Competitive Programming Helper (cph) — extensão do VS Code](https://github.com/agrawal-d/cph) — Roda os casos de teste do problema com um clique e importa problemas de juízes online. 🇺🇸
- [LeetCode — extensão do VS Code](https://github.com/LeetCode-OpenSource/vscode-leetcode) — Resolva e submeta problemas do LeetCode sem sair do editor. 🇺🇸
- [Compiler Explorer (godbolt)](https://godbolt.org/) — Veja o assembly gerado pelo compilador e entenda por que uma implementação é mais rápida que outra. 🇺🇸
- [OnlineGDB](https://www.onlinegdb.com/) — Compilador e depurador online para C/C++, Python, Java e outras; útil para testar sem instalar nada. 🇺🇸
- [Python Tutor](https://pythontutor.com/) — Executa seu código passo a passo mostrando a memória: ponteiros, pilha de chamadas e recursão ficam visíveis. 🇺🇸
- [AtCoder Library (ACL)](https://github.com/atcoder/ac-library) — Biblioteca oficial do AtCoder em C++ com estruturas prontas: segment tree, DSU, fluxo, strings. 🇺🇸
- [online-judge-tools (oj)](https://github.com/online-judge-tools/oj) — CLI que baixa casos de teste, gera casos aleatórios e testa sua solução contra um brute force. 🇺🇸
- [Hypothesis (Python)](https://hypothesis.readthedocs.io/en/latest/) — Testes baseados em propriedades: gera milhares de entradas para achar o caso em que seu algoritmo quebra. 🇺🇸
- [fast-check (JavaScript/TypeScript)](https://fast-check.dev/) — Equivalente do Hypothesis para JS/TS. 🇺🇸
- [CLion (JetBrains)](https://www.jetbrains.com/clion/) — IDE para C/C++ com depurador visual excelente; gratuito para estudantes. 💰 🇺🇸

## 🧪 Projetos práticos e desafios
Resolver problemas é a única forma de aprender algoritmos de verdade. Comece pelos juízes com problemas fáceis e por tópico; depois, implemente estruturas do zero e compare com os repositórios de referência.
- [HackerRank — Data Structures](https://www.hackerrank.com/domains/data-structures) — Problemas por estrutura (arrays, listas, árvores, heaps, tries) com dificuldade progressiva. 🇺🇸
- [HackerRank — Algorithms](https://www.hackerrank.com/domains/algorithms) — Trilha de algoritmos: ordenação, busca, greedy, DP e grafos. 🇺🇸
- [CSES Problem Set](https://cses.fi/problemset/) — 300 problemas clássicos organizados por tópico — o melhor conjunto para treinar de forma estruturada. 🇺🇸
- [AtCoder](https://atcoder.jp/) — Juiz japonês com contests semanais para iniciantes (ABC) e problemas de altíssima qualidade. 🇺🇸
- [Kattis](https://open.kattis.com/) — Milhares de problemas de competições reais, muitos usados na Maratona e no ICPC. 🇺🇸
- [HackerEarth — Practice](https://www.hackerearth.com/practice/) — Trilhas de prática por tópico com tutoriais antes dos problemas. 🇺🇸
- [Codewars](https://www.codewars.com/) — Katas em dezenas de linguagens; compare sua solução com as mais votadas depois de resolver. 🇺🇸
- [CodeChef](https://www.codechef.com/) — Contests mensais e trilhas de prática, do iniciante ao avançado. 🇺🇸
- [Project Euler](https://projecteuler.net/) — Problemas matemáticos que só saem com algoritmo eficiente — ótimo para treinar complexidade. 🇺🇸
- [Advent of Code](https://adventofcode.com/) — Calendário de dezembro com 25 quebra-cabeças que exigem parsing, grafos, DP e simulação; edição 2025 no ar. 🆕 🇺🇸
- [CodinGame](https://www.codingame.com/start/) — Aprenda algoritmos programando bots e jogos, com ranking e desafios multiplayer. 🇺🇸
- [Rosalind](https://rosalind.info/problems/locations/) — Problemas de algoritmos aplicados à bioinformática — strings e grafos com propósito. 🇺🇸
- [The Algorithms](https://the-algorithms.com/) — Implementações abertas de centenas de algoritmos em todas as linguagens populares. 🇺🇸
- [TheAlgorithms/Python](https://github.com/TheAlgorithms/Python) — O repositório mais estrelado de algoritmos em Python; leia, compare e contribua. 🇺🇸
- [TheAlgorithms/JavaScript](https://github.com/TheAlgorithms/JavaScript) — Mesma coleção em JavaScript, com boas práticas e testes. 🇺🇸
- [TheAlgorithms/Java](https://github.com/TheAlgorithms/Java) — Mesma coleção em Java. 🇺🇸
- [TheAlgorithms/C-Plus-Plus](https://github.com/TheAlgorithms/C-Plus-Plus) — Mesma coleção em C++. 🇺🇸
- [javascript-algorithms (README em PT-BR)](https://github.com/trekhleb/javascript-algorithms/blob/master/README.pt-BR.md) — Algoritmos e estruturas em JavaScript com explicações e links para aprofundar, traduzido.
- [interactive-coding-challenges (donnemartin)](https://github.com/donnemartin/interactive-coding-challenges) — 120+ desafios de entrevista em Jupyter Notebooks com testes unitários e soluções. 🇺🇸
- [williamfiset/Algorithms](https://github.com/williamfiset/Algorithms) — Implementações em Java de tudo que aparece nos vídeos do William Fiset. 🇺🇸
- [Build your own X](https://github.com/codecrafters-io/build-your-own-x) — Reconstrua um banco de dados, um compilador ou um Git do zero — algoritmos e estruturas na vida real. 🇺🇸

> Plataformas muito usadas que **não** estão linkadas aqui porque bloqueiam verificadores automáticos de links (não conseguimos confirmar a página): LeetCode, Codeforces (site principal), Beecrowd (antigo URI Online Judge) e SPOJ. Procure-as pelo nome — todas continuam ativas.

## 🏆 Programação competitiva
Programação competitiva é resolver problemas algorítmicos contra o relógio. No Brasil, o caminho é a **OBI** (escolas) e a **Maratona SBC de Programação** (universidades), que classifica para o ICPC mundial. Mesmo sem competir, treinar nesse formato é a preparação mais eficiente para entrevistas técnicas.
- [OBI — Olimpíada Brasileira de Informática](https://olimpiada.ic.unicamp.br/) — Olimpíada oficial para alunos do ensino fundamental, médio e universitário, organizada pela SBC e pela UNICAMP. 🆕
- [OBI — provas de anos anteriores](https://olimpiada.ic.unicamp.br/passadas/) — Todas as provas passadas com gabarito — a melhor forma de treinar para a OBI.
- [Maratona SBC de Programação](https://maratona.sbc.org.br/) — A competição universitária brasileira, classificatória para o ICPC; regras, datas e sedes. 🆕
- [Maratona SBC — histórico e provas](https://maratona.sbc.org.br/hist/) — Provas e resultados de edições anteriores da Maratona.
- [ICPC — International Collegiate Programming Contest](https://icpc.global/) — A final mundial para onde os melhores times da Maratona vão. 🇺🇸
- [Neps Academy — trilhas de competição](https://neps.academy/br) — Cursos gratuitos de técnicas de programação, grafos, matemática e estruturas, com problemas da OBI.
- [Clube de Programação UPF — vídeo-oficinas](https://maratonaupf.github.io/videos/introducao-programacao-competitiva) — Oficinas em vídeo da Universidade de Passo Fundo para quem quer começar a competir.
- [Livreto FACOMpetindo (repositório)](https://github.com/FACOMpetindo/livreto) — Código e exercícios em Python e C++ que acompanham o livreto da UFMS.
- [Codeforces EDU](https://codeforces.com/edu/courses) — Cursos da ITMO Academy dentro do Codeforces, com problemas para praticar cada técnica. 🇺🇸
- [USACO Guide](https://usaco.guide/) — Trilha completa e gratuita, do Bronze ao Platinum, com problemas resolvidos e teoria. 🇺🇸
- [cp-algorithms](https://cp-algorithms.com/) — A referência técnica de cada algoritmo usado em competições. 🇺🇸
- [Competitive Programmer's Handbook (PDF gratuito)](https://cses.fi/book/book.pdf) — O livro para começar, do criador do CSES. 🇺🇸
- [How to test your solution in Competitive Programming (Errichto)](https://www.youtube.com/watch?v=JXTVOyQpSGM) — Como montar um *stress test* comparando sua solução com um brute force em entradas aleatórias. 🇺🇸

## 👁️ Visualizadores
Ver uma árvore se rebalancear ou um Dijkstra expandir nós vale mais que dez páginas de texto. Use os visualizadores enquanto estuda cada estrutura.
- [VisuAlgo](https://visualgo.net/en) — Animações de dezenas de estruturas e algoritmos (ordenação, BST, heap, grafos, DP), com modo de treino. 🇺🇸
- [Data Structure Visualization (David Galles, USF)](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html) — Visualizador clássico: insira valores e veja árvores AVL, B-trees, heaps e hashing se reorganizarem. 🇺🇸
- [Python Tutor](https://pythontutor.com/) — Visualize a execução do seu próprio código, incluindo recursão e ponteiros, em Python, C, C++, Java e JavaScript. 🇺🇸
- [Pathfinding Visualizer](https://clementmihailescu.github.io/Pathfinding-Visualizer/) — Desenhe paredes num grid e compare Dijkstra, A*, BFS e DFS achando o caminho. 🇺🇸
- [Introduction to the A* Algorithm (Red Blob Games)](https://www.redblobgames.com/pathfinding/a-star/introduction.html) — O melhor artigo interativo sobre busca de caminhos: BFS → Dijkstra → A* com diagramas manipuláveis. 🇺🇸
- [CS Academy — Graph Editor](https://csacademy.com/app/graph_editor/) — Cole a lista de arestas de um problema e veja o grafo desenhado na hora. 🇺🇸
- [HackerEarth — visualizador de ordenação](https://www.hackerearth.com/practice/algorithms/sorting/bubble-sort/visualize/) — Animação passo a passo dos algoritmos de ordenação, com o código ao lado. 🇺🇸

## 🤖 IA na prática
Assistentes de IA são ótimos professores particulares de algoritmos — e péssimos substitutos para o seu próprio raciocínio. A regra: **a IA explica, você implementa; a IA sugere, o juiz online decide.**

**Para aprender**
- Cole sua implementação e peça: *"analise a complexidade de tempo e espaço linha a linha, aponte o gargalo e diga se dá para melhorar sem mudar o algoritmo"*. Depois confira no [Big-O Cheat Sheet](https://www.bigocheatsheet.com/).
- Peça a **mesma estrutura em duas linguagens** (ex.: tabela hash em C e em Python) e compare o que muda — isso separa o conceito da sintaxe.
- Peça uma **prova informal de corretude** (invariante de laço, por que a busca binária termina) e tente encontrar furos na explicação.
- Pediu uma solução pronta? Então peça também **três casos de teste que a quebrariam** e rode no [Python Tutor](https://pythontutor.com/) para ver onde falha.
- Use a IA como gerador de exercícios: *"cinco problemas de dois ponteiros, do fácil ao difícil, sem solução; só me dê a dica se eu pedir"*.

**Para trabalhar e treinar**
- Use [GitHub Copilot](https://github.com/features/copilot), [Cursor](https://cursor.com/) ou [Claude Code](https://code.claude.com/docs/en/overview) para escrever **geradores de casos de teste** e *stress tests*: uma solução ingenua O(n²) como oráculo, milhares de entradas aleatórias, compare as saídas. É exatamente o que o [vídeo do Errichto](https://www.youtube.com/watch?v=JXTVOyQpSGM) ensina — a IA só tira o trabalho braçal.
- Peça testes baseados em propriedades com [Hypothesis](https://hypothesis.readthedocs.io/en/latest/) (Python) ou [fast-check](https://fast-check.dev/) (JS/TS): "para qualquer lista, a saída da minha ordenação é uma permutação ordenada da entrada".
- Em código de produção, peça à IA para identificar **estruturas erradas para o acesso** (lista onde deveria ser conjunto, busca linear dentro de laço) — é o bug de desempenho mais comum e o mais fácil de ela achar.

**Limites e boas práticas**
- **Entrevistas técnicas proíbem IA.** Google, Amazon, Meta e a maioria das empresas brasileiras pedem que você resolva sozinho, explicando o raciocínio em voz alta. Se só sabe resolver com IA, não sabe resolver.
- **Competições também proíbem.** Desde setembro de 2024 o Codeforces proíbe usar IA para gerar a lógica da solução (só autocompletar de sintaxe é tolerado); OBI, Maratona e ICPC seguem a mesma linha. Treinar com IA e competir sem ela é como treinar com boia.
- Modelos de raciocínio já resolvem problemas de nível medalha de ouro — veja o [artigo da OpenAI](https://arxiv.org/abs/2502.06807) e o [LiveCodeBench](https://livecodebench.github.io/). Isso muda o que o mercado valoriza: menos "sabe decorar Dijkstra", mais "sabe escolher a estrutura certa, provar que está correta e verificar o que a IA produziu".
- A IA erra complexidade com confiança (chama de O(n log n) o que é O(n²)) e inventa propriedades de estruturas. Verifique com um contraexemplo ou com um teste de tempo de execução.
- Não cole código proprietário, dados de clientes ou provas de processo seletivo em ferramentas sem a política da empresa.

**Ferramentas e leituras**
- [GitHub Copilot](https://github.com/features/copilot) — Autocomplete e chat no editor; gratuito para estudantes e com plano free. 🆕 🇺🇸
- [Cursor](https://cursor.com/) — Editor baseado no VS Code com IA integrada ao fluxo de trabalho. 🆕 🇺🇸
- [Claude Code](https://code.claude.com/docs/en/overview) — Agente de código no terminal: explica complexidade, gera testes e refatora implementações. 🆕 🇺🇸
- [Claude](https://claude.com/product/overview) — Assistente da Anthropic; bom para pedir explicações passo a passo e provas de corretude. 🆕 🇺🇸
- [Competitive Programming with Large Reasoning Models (OpenAI, arXiv 2025)](https://arxiv.org/abs/2502.06807) — Artigo que mostra modelos de raciocínio atingindo nível de ouro em competições — leia para entender o que a IA já resolve. 🆕 🇺🇸
- [LiveCodeBench](https://livecodebench.github.io/) — Benchmark que avalia LLMs em problemas novos de LeetCode, AtCoder e Codeforces, sem contaminação. 🆕 🇺🇸
- [AlphaCode 2 — relatório técnico (Google DeepMind)](https://storage.googleapis.com/deepmind-media/AlphaCode2/AlphaCode2_Tech_Report.pdf) — Como o DeepMind fez um sistema de IA competir no Codeforces: geração massiva + filtragem por testes. 🇺🇸

## 📜 Certificações
Não existe certificação oficial de Algoritmos e Estruturas de Dados — nem de uma empresa, nem de uma entidade da área. O que o mercado reconhece é **desempenho em entrevista técnica**, **medalhas e classificações** (OBI, Maratona SBC, ratings de Codeforces/AtCoder) e **projetos publicados**. Os certificados abaixo são de conclusão de curso ou de teste de habilidade: ajudam no currículo, mas não substituem prática.
- [JavaScript Algorithms and Data Structures Certification (freeCodeCamp)](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures-v8) — Certificação gratuita e reconhecida: centenas de exercícios e 5 projetos de algoritmos em JavaScript. 🇺🇸
- [HackerRank Skills Certification — Problem Solving (Basic)](https://www.hackerrank.com/skills-verification/problem_solving_basic) — Teste cronometrado gratuito de estruturas de dados e algoritmos; o certificado vai para o seu perfil. 🇺🇸
- [HackerRank Skills Certification — Problem Solving (Intermediate)](https://www.hackerrank.com/skills-verification/problem_solving_intermediate) — Nível intermediário do mesmo teste. 🇺🇸
- [Curso Estrutura de Dados e Algoritmos Java (Loiane) — com certificado](https://www.youtube.com/playlist?list=PLGxZ4Rq3BOBrgumpzz-l8kFMw2DLERdxi) — Curso gratuito em português que emite certificado de conclusão.
- [Aprenda Estrutura de Dados e Algoritmos (DIO) — com certificado](https://www.dio.me/courses/aprenda-o-que-sao-estrutura-de-dados-e-algoritmos) — Certificado gratuito de conclusão.
- [Algorithms, Part I (Princeton — Coursera) — certificado](https://www.coursera.org/learn/algorithms-part1) — Assistir é gratuito; o certificado de Princeton é pago. 💰 🇺🇸
- [Data Structures and Algorithms Specialization (UC San Diego — Coursera) — certificado](https://www.coursera.org/specializations/data-structures-algorithms) — Certificado pago da especialização com juiz automático. 💰 🇺🇸

## 💼 Carreira e vagas
Algoritmos e estruturas de dados são o critério principal das entrevistas em Google, Amazon, Meta, Microsoft, Nubank, iFood, Mercado Livre e da maioria das startups que pagam em dólar — quase sempre no formato *coding interview*: 45 minutos, 1–2 problemas, complexidade explicada em voz alta. Também aparecem nos testes das plataformas brasileiras de recrutamento. No Brasil, a Pesquisa Código Fonte TV traz as faixas salariais por nível; para big techs com escritório no país, o Levels.fyi é a referência.
- [Tech Interview Handbook](https://www.techinterviewhandbook.org/) — Guia completo e gratuito de entrevistas técnicas: currículo, algoritmos, comportamental e negociação. 🇺🇸
- [Grind 75](https://www.techinterviewhandbook.org/grind75/) — Lista de problemas personalizável por semanas disponíveis e horas por semana, do autor do Blind 75. 🇺🇸
- [Blind 75 (Best practice questions)](https://www.techinterviewhandbook.org/best-practice-questions/) — As 75 questões que cobrem os padrões mais cobrados em entrevistas. 🇺🇸
- [NeetCode 150](https://neetcode.io/practice) — Lista organizada por tópico, com vídeo-solução para cada problema. 🇺🇸
- [Coding Interview University](https://github.com/jwasham/coding-interview-university) — O plano de estudos de CS mais popular do GitHub para entrevistas em big techs. 🇺🇸
- [kdn251/interviews](https://github.com/kdn251/interviews) — Tudo o que você precisa saber para a entrevista: algoritmos, estruturas, Big-O e links por empresa. 🇺🇸
- [A Senior Engineer's Guide to FAANG Interviews (interviewing.io)](https://interviewing.io/guides/hiring-process) — Como funciona o processo de Google, Meta, Amazon e afins, etapa por etapa. 🇺🇸
- [Google Careers — Our hiring process](https://www.google.com/about/careers/applications/how-we-hire/) — Página oficial do Google explicando as etapas, incluindo as entrevistas de código. 🇺🇸
- [Google Careers — Build your future: resources](https://www.google.com/about/careers/applications/buildyourfuture/resources/) — Materiais oficiais de preparação técnica recomendados pelo Google. 🇺🇸
- [Amazon — Software Development Interview Topics](https://www.amazon.jobs/content/en/how-we-hire/interview-prep/software-development-topics) — A lista oficial de tópicos que a Amazon cobra: estruturas de dados, algoritmos, complexidade e design. 🇺🇸
- [interviewing.io](https://interviewing.io/) — Entrevistas simuladas anônimas com engenheiros de big techs; gratuito para praticar como entrevistado em alguns formatos. 🇺🇸
- [Pramp](https://www.pramp.com/) — Entrevistas simuladas gratuitas entre pares: você entrevista e é entrevistado. 🇺🇸
- [Pesquisa Salarial de Programadores 2026 (Código Fonte TV)](https://pesquisa.codigofonte.com.br/2026) — Maior pesquisa de salários de devs do Brasil, filtrável por nível, linguagem, estado e modelo de contratação. 🆕
- [Salario.com.br — Desenvolvedor back-end](https://www.salario.com.br/profissao/desenvolvedor-back-end/) — Piso e média salarial oficiais (CAGED) por cargo e região.
- [Levels.fyi](https://www.levels.fyi/) — Salários e níveis das big techs, inclusive escritórios no Brasil. 🇺🇸
- [Stack Overflow Developer Survey 2025](https://survey.stackoverflow.co/2025/) — Panorama global de linguagens, ferramentas e salários. 🆕 🇺🇸
- [Programathor](https://programathor.com.br/) — Vagas de tecnologia no Brasil filtráveis por linguagem e nível.
- [GeekHunter](https://www.geekhunter.com/pt) — Plataforma brasileira onde empresas fazem propostas a devs; tem teste técnico de algoritmos.
- [Coodesh](https://coodesh.com/) — Vagas tech no Brasil com desafios técnicos padronizados.
- [Remotar](https://remotar.com.br/) — Vagas 100% remotas para brasileiros.
- [backend-br/vagas](https://github.com/backend-br/vagas) — Vagas de back-end publicadas como issues no GitHub.
- [frontendbr/vagas](https://github.com/frontendbr/vagas) — Vagas de front-end publicadas como issues no GitHub.

## 👥 Comunidades
- [Neps Academy — comunidade](https://neps.academy/br) — Fórum e ranking da maior plataforma brasileira de programação competitiva.
- [r/programacao](https://www.reddit.com/r/programacao/) — Subreddit em português sobre programação.
- [TabNews](https://www.tabnews.com.br/) — Comunidade brasileira de conteúdo técnico criada por Filipe Deschamps.
- [He4rt Developers](https://heartdevs.com/) — Comunidade brasileira open source com Discord ativo e grupos de estudo.
- [Desenvolvedores Brasil (Discord)](https://discord.com/invite/t3vYGUuK6P) — Comunidade brasileira com dicas, cursos, mentorias e vagas.
- [Lista de grupos de tecnologia no Telegram (TI-Brasil)](https://github.com/TI-Brasil/lista-telegram-brasil) — Diretório de grupos brasileiros no Telegram, incluindo programação competitiva e linguagens.
- [Rocketseat — comunidade](https://www.rocketseat.com.br/) — Uma das maiores comunidades de devs do Brasil, com Discord aberto.
- [Codeforces Discord](https://discord.com/invite/codeforces) — Servidor da comunidade Codeforces para discutir problemas e contests. 🇺🇸
- [r/codeforces](https://www.reddit.com/r/codeforces/) — Subreddit sobre contests, ratings e editoriais. 🇺🇸
- [r/leetcode](https://www.reddit.com/r/leetcode/) — Relatos de entrevistas, listas de estudo e dúvidas sobre problemas. 🇺🇸
- [r/algorithms](https://www.reddit.com/r/algorithms/) — Discussões teóricas sobre algoritmos e complexidade. 🇺🇸
- [r/cscareerquestions](https://www.reddit.com/r/cscareerquestions/) — Carreira, entrevistas e negociação em empresas de tecnologia. 🇺🇸

## 🚨 Como contribuir
Achou um link quebrado, um curso novo ou uma ferramenta que merece estar aqui? Abra uma issue usando os templates do repositório ou envie um pull request. Critérios: link funcionando, conteúdo legal e gratuito ou claramente marcado como pago, com uma linha de descrição. Detalhes em [CONTRIBUTING.md](./CONTRIBUTING.md).

## 📄 Licença
Este projeto está sob a licença [MIT](./LICENSE). Feito com 💙 por [Arthur Coutinho (@arthurspk)](https://github.com/arthurspk) e pela comunidade do [Guia Dev Brasil](https://github.com/arthurspk/guiadevbrasil).

## 💙 Apoie o projeto
Dê uma ⭐ neste repositório e no [guia principal](https://github.com/arthurspk/guiadevbrasil), compartilhe com quem está começando e siga o projeto nas redes:

[<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">](https://github.com/arthurspk)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">](https://www.linkedin.com/in/arthurspk/)
[<img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X (Twitter)">](https://x.com/manotoquinho)
[<img src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">](https://www.instagram.com/arthurspk/)
[<img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook">](https://www.facebook.com/seixasqlc/)
