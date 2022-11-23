# Statistical Inference (BSc)

Material para o curso de [Inferência Estatística](https://emap.fgv.br/disciplina/inferencia-estatistica-0) oferecido como disciplina obrigatória das graduações em [Matemática Aplicada](https://emap.fgv.br/curso/matematica-aplicada) e [Ciência de Dados e Inteligência Artificial](https://emap.fgv.br/curso/ciencia-de-dados-e-inteligencia-artificial) da [Escola de Matemática Aplicada](https://emap.fgv.br/) da Fundação Getulio Vargas (FGV EMAp). 

Programa (provisório) [aqui](https://docs.google.com/spreadsheets/d/1hXvrf1YdXj9c_hQCytV3-ka9J2flK8u-DDAuqkg59tQ/edit?usp=sharing).

Slides [aqui](https://github.com/maxbiostat/Statistical_Inference_BSc/blob/master/slides/inferencia.pdf).

Notas (independentes) feitas por [@wellington36](https://github.com/wellington36) estão [aqui](https://github.com/wellington36/Resumos_EMAP-FGV/blob/main/4%20periodo/Inferencia_estatistica.pdf). 

Tópicos marcados com um `*` são extra e em geral designam material mais avançado.

### Bibliografia

- Principal: [DG] DeGroot MH, Schervish MJ. Probability and statistics. Pearson Education; 2012.
- Apoio: [CB] Casella, G., & Berger, R. L. (2002). Statistical Inference. Pacific Grove, CA: Duxbury.

### News

- O trabalho III já está [disponível](https://github.com/maxbiostat/Statistical_Inference_BSc/blob/master/trabalhos/trabalho_III.pdf). O prazo de entrega é **28/10/2022**.
- O exercício de fixação da semana (17/10/2022) já está [disponível](https://github.com/maxbiostat/Statistical_Inference_BSc/blob/master/exercicios/CMT_1_2022.pdf).

- Soluções propostas para as questões da A1 podem ser encontradas [aqui](https://github.com/maxbiostat/Statistical_Inference_BSc/blob/master/provas/A12022_solucoes.pdf).

### Leituras adicionais

**Aula 1 - Revisão de probabilidade:**

- Esta [apostila](https://sites.google.com/site/probfgv/teoria-da-probabilidade-20211?authuser=0) tem material relevante para quem precisa revisar alguns conceitos. 
- `*` Sobre a lei forte dos grandes números: uma [prova](http://www.im.ufrj.br/nuno/SLLN.pdf) elementar com taxas de convergência e [notas](https://terrytao.wordpress.com/2008/06/18/the-strong-law-of-large-numbers/) de Terence Tao com um tratamento mais refinado, incluindo algumas desigualdades probabilísticas. 
- `*` Sobre a prova do Teorema Central do Limite e a existência de muitos TCLs, sob premissas diferentes: [neste](http://downloads.hindawi.com/journals/aaa/2013/294910.pdf) artigo temos essencialmente a mesma demonstração de Casela & Berger (2002) teorema 5.5.14, mas de forma mais rigorosa e detalhada. 
Já este [artigo](https://github.com/maxbiostat/Statistical_Inference_BSc/blob/master/material_apoio/Trotter1959_Article_AnElementaryProofOfTheCentralL.pdf) descreve uma demonstração elementar do TCL -- isto é, uma demonstração que não envolve funções características -- e mostra, nas seções 3 e 4, outros casos de interesse;
- [Lista de exercícios](https://github.com/maxbiostat/Statistical_Inference_BSc/blob/master/exercicios/exerc%C3%ADcios_revis%C3%A3o_probabilidade.pdf).

**Aula 2 - Inferência Estatística (fundamentos):**

- `*` [Artigo](https://projecteuclid.org/download/pdf_1/euclid.aos/1035844977) de Peter McCullagh sobre o que é um modelo estatístico (avançado).
- Material do [curso](https://github.com/maxbiostat/stats_modelling) de Modelagem Estatística. 
- `*` Em [Finite Exchangeable Sequences](https://www.jstor.org/stable/pdf/2242823.pdf), Persi Diaconis e David Freedman mostram que se a geração de um conjunto finito de variáveis aleatórias pode ser representada como um experimento envolvendo urnas, este conjunto será permutável (_exchangeable_) -- avançado.  

**Aula 3 - Inferência bayesiana:**

- Esta [vignette](https://cran.r-project.org/web/packages/LaplacesDemon/vignettes/BayesianInference.pdf) oferece um panorama da inferência bayesiana, mencionando tópicos avançados que não serão discutidos neste curso.  
- Este [artigo](http://www.cs.ru.nl/P.Lucas/teaching/CI/efron.pdf) de Bradley Effron discorre sobre porque nem todo mundo é bayesiano.
- `*` O blog de Larry Wasserman tem uma [discussão](https://normaldeviate.wordpress.com/2012/11/17/what-is-bayesianfrequentist-inference/) mais técnica sobre as diferenças entre os paradigmas de inferência (avançado).

**Aula 4 - Prioris conjugadas:**

- [Artigo](https://projecteuclid.org/euclid.aos/1176344611) de Ylvisaker e Diaconis (1979) sobre a familia de prioris conjugadas para distribuições conjuntas dos dados morando na família exponencial (avançado).

- Este [compêndio](https://www.johndcook.com/CompendiumOfConjugatePriors.pdf) traz um catálogo de prioris conjugadas e suas respectivas verossimilhanças.

**Aula 5 - Estimadores de Bayes:**

- [Verbete](https://encyclopediaofmath.org/wiki/Bernstein-von_Mises_theorem) da _Encyclopedia of Mathematics_ sobre o teorema de Bernstein-von Mises e a normalidade assintótica da posteriori (avançado).

**Aula 6 - Estimador de máxima verossimilhança**

- Neste [artigo](https://www.jstor.org/stable/pdf/2236315.pdf?casa_token=vEzRlL3BCkMAAAAA:YCNdxwXeHAO4Kv5NktCHa8xMBbjnYBwIR9L90nwI966gZlEhugejQnXkJrVlFM-NHYVRnyafYs3hXQ8TmxyCvDEkffhwX1GK0GvmU5wRfUYB1nEhxhXtvg), o grande [Abraham Wald](https://en.wikipedia.org/wiki/Abraham_Wald) dá um tratamento formal mas elementar da consistência do EMV sob condições brandas.

- Uma demonstração da consistência da EMV pode ser encontrada na seção 4 [deste](http://www.stat.cmu.edu/~larry/=stat705/Lecture9.pdf) documento. 
A nota contém ainda vários resultados interessantes sobre teoria assintótica.

**Aula  8 - Suficiência**

- A [história épica do EMV](https://www.ime.usp.br/~abe/lista/pdfW987Cm4f2K.pdf) fala sobre o tópico da aula 6 assim como o resultado de suficiência do EMV.

**Aula 9 - Rao-Blackwell e admissibilidade**

- O artigo referenciado na seção 8.7.6 de DeGroot e tópico da questão bônus da A12020 é [este](https://idp.springer.com/authorize/casa?redirect_uri=https://link.springer.com/content/pdf/10.1007/BF02868569.pdf&casa_token=06U6kaM0_dkAAAAA:zGbdUZ6Zr0CBkpomi8nqnu_zL2PN907WvgfWZlTZxNx90z3L3BpVIZAbJELosJhCzPrdY-iDbOFBltpq) aqui. 

- [Aqui](http://eblackcu.net/portal/archive/files/blackwell-article-jstor_f4b0f250fc.pdf) um artigo sobre a vida e obra de David Blackwell (1919-2010). 

**Aula 12 - Distribuição da média e variância amostrais**

- O [Teorema de Basu](https://en.wikipedia.org/wiki/Basu%27s_theorem)  tem como caso particular a independência da média e variância amostrais para o caso Normal.
Em particular, esse resultado _caracteriza_ a distribuição Normal.

**Aula 13 - Intervalos de confiança**

- [Este](https://rpsychologist.com/d3/ci/) link tem uma visualização legal de intervalos de confiança.
Basicamente uma versão interativa da visualização que vimos em [aula](https://github.com/maxbiostat/Statistical_Inference_BSc/blob/master/code/IC_normal.r).
- O [artigo](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1339793/pdf/bmjcred00225-0036.pdf) de Gardner & Altman na _Statistics in Medicine_ advoga o uso de intervalos de confiança para testar hipóteses.

**Aula 15 - Razão de verossimilhança**

- A prova do Teorema 9.1.4 de DeGroot, originalmente formulado por [Samuel Wilks](https://en.wikipedia.org/wiki/Samuel_S._Wilks) neste [paper](https://projecteuclid.org/euclid.aoms/1177732360) de 1938, pode ser encontrada [aqui](http://math.bu.edu/people/cgineste/classes/ma782/p/w1_2.pdf). 


**Miscelânea**
- O Canal [A Ciência da Estatística](https://www.youtube.com/c/ACi%C3%AAnciadaEstat%C3%ADstica) do Professor [Alexandre Patriota](https://www.ime.usp.br/~patriota/) é um excelente recurso para aprender mais. Ver, por exemplo, [este](https://www.youtube.com/watch?v=knmMunEzdZo) vídeo sobre a aplicação de variáveis aleatórias Bernoulli a um problema em atuária. 

- [Este](https://stat.uiowa.edu/sites/stat.uiowa.edu/files/cae/Lo_Expectation.pdf) artigo apresenta o resultado `E[X] = int_0^inf Pr(X > x)dx`, chamado em inglês de "tail formula for the expectation".
- Sobre a "diferenciação sob o sinal da integral", ou regra de Leibniz, [este](https://medium.com/cantors-paradise/richard-feynmans-integral-trick-e7afae85e25c) post mostra bem o poder da técnica, muito embora não dê um tratamento completo. Para isso, o [artigo](https://en.wikipedia.org/wiki/Leibniz_integral_rule) da Wikipedia serve bem.
- [Este](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4960505/) artigo foi a inspiração das questões 4 e 5 da [A1 2021](https://github.com/maxbiostat/Statistical_Inference_BSc/blob/master/provas/A12021_solucoes.pdf). 

- [Neste](https://normaldeviate.wordpress.com/2012/11/17/what-is-bayesianfrequentist-inference/) post, Larry Wasserman explica que você não precisa assumir que todas as amostras vêm da mesma distribuição para ter a cobertura correta do intervalo de confiança.

**Versões anteriores**
- [2020](https://github.com/maxbiostat/Statistical_Inference_BSc/releases/tag/2020-2)
- [2021](https://github.com/maxbiostat/Statistical_Inference_BSc/releases/tag/2021-2)

**Agradecimentos**

@IgorMichels, @lucasmoschen, @reneroliveira, @wellington36, @MaisaFraiz, @jpdonasolo, @Caioflp e @lfzinho ajudaram a consertar typos e esclarecer alguns argumentos. 
