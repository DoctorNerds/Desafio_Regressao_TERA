# 📊 Desafio de Regressão Linear da [TERA](https://somostera.com/)

Este desafio é parte da minha formação na pós graduação de [Data Science & Machine Learning](https://somostera.com/cursos/data-science-machine-learning) da TERA.

## 🧑🏼‍🔬 Sobre o Desafio.

### Problema:
Entender quais são os principais fatores que influenciam a nota de um aluno no ENEM, tal como tentar prever a sua nota através de um modelo de regressão linear.

### Etapas do desafio:
- Parte 1: Interpretabilidade usando uma Regressão Linear.
  - Através da Regressão Linear, entender quais variáveis são mais representativas ao tentar explicar a variável target, a nota do aluno do ENEM.
- Parte 2: Poder preditivo, Regressão via Scikit-Learn (SGD)
  - Criar um modelo de Regresão Linear para prever a nota do aluno no ENEM.

## 🗂️ Sobre as fontes dos dados.

### ENEM.

O Exame Nacional do Ensino Médio (ENEM) é uma avaliação realizada anualmente no Brasil. Criado em 1998, o exame tem como objetivo avaliar o desempenho dos estudantes do ensino médio em diferentes áreas de conhecimento, como Linguagens, Matemática, Ciências Humanas e Ciências da Natureza.
Além de avaliar o conhecimento dos estudantes, o ENEM também é utilizado como uma forma de ingresso em instituições de ensino superior no Brasil. Através do Sistema de Seleção Unificada (SISU), os estudantes podem utilizar as notas do ENEM para se candidatarem a vagas em diversas universidades e institutos federais do país.
Além disso, o exame também é utilizado como critério de seleção para programas de financiamento estudantil, como o Programa Universidade para Todos (PROUNI) e o Fundo de Financiamento Estudantil (FIES).
O ENEM é aplicado em dois dias consecutivos e é composto por uma prova objetiva, com 180 questões de múltipla escolha, e uma prova de redação. As questões objetivas são baseadas no conteúdo programático do ensino médio e avaliam habilidades como interpretação de texto, raciocínio lógico e resolução de problemas.
O exame é considerado uma das principais formas de avaliação do ensino médio no Brasil e possui grande importância para os estudantes que desejam ingressar em uma instituição de ensino superior.

### Conjunto de dados.

O conjunto de dados que será utilziado descreve o desempenho dos candidatos do ENEM em 2021, contendo 168.979 observações e 76 variáveis explicativas.
Essas variáveis são provenientes de um questionário socioeconômico preenchido pelos candidatos antes do exame e incluem tanto features contínuas quanto discretas.
Algumas variáveis, como o código de um município, são representadas por valores numéricos, portanto, é importante entender o significado dessas variáveis ao analisar os dados.
É importante notar que a variável target (a nota média dos candidatos) é derivada diretamente de outras variáveis do conjunto de dados. Como resultado, é crucial considerar essa relação ao construir um modelo coerente.


## 🎯 Objetivo do estudo

Primeiro, encontrar quais variáveis explicam melhor a target (nota do aluno no ENEM) utilizando um modelo de Regressão Lienar em Python. 
Por fim, prever a nota de um aluno no ENEM partindo das informações disponíveis no banco de dados, também através de um modelo de Regressão Linear em Python.
