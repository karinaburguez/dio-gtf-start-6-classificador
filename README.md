# 🦸‍♂️ Desafio: Classificador de Nível de Herói

Este repositório contém a resolução do desafio "Classificador de Nível de Herói" da DIO, onde o objetivo é aplicar conceitos básicos de programação para classificar o nível de um herói com base em sua experiência (XP).

## 🚀 Objetivo

O desafio é criar um sistema que armazene o nome e a quantidade de XP de um herói e, a partir disso, utilize uma estrutura de decisão para determinar o nível do herói conforme as faixas de XP descritas abaixo:

- **Ferro**: XP menor do que 1.000
- **Bronze**: XP entre 1.001 e 2.000
- **Prata**: XP entre 2.001 e 5.000
- **Ouro**: XP entre 5.001 e 7.000
- **Platina**: XP entre 7.001 e 8.000
- **Ascendente**: XP entre 8.001 e 9.000
- **Imortal**: XP entre 9.001 e 10.000
- **Radiante**: XP maior ou igual a 10.001

## ⚠️ Observação

No enunciado original do desafio, a classificação é apresentada da seguinte forma:

- **Ferro**: XP menor do que 1.000
- **Bronze**: XP entre 1.001 e 2.000

Dessa forma, se o herói estiver com exatamente 1.000 XP, ele ficará sem classificação definida. Uma sugestão de correção seria ajustar a faixa de **Ferro** para incluir "XP menor ou igual a 1.000".

## 📝 Saída Esperada

Ao final da execução do programa, a saída deverá exibir a seguinte mensagem:
O Herói de nome {nome} está no nível de {nivel}

## 🛠 Tecnologias Utilizadas

- Variáveis
- Operadores
- Laços de repetição
- Estruturas de decisão

## 📁 Estrutura do Repositório

- **src/**: Contém o código-fonte do projeto.
- **docs/**: Contém arquivos relacionados ao projeto, como templates de design ou links úteis.
- **README.md**: Este arquivo, com instruções sobre o desafio e como executá-lo.

## 💡 Dicas

- Explore os conceitos aprendidos até agora e busque melhorar o projeto inicial.
- Caso tenha um repositório de referência, considere fazer um "fork" para evoluir e personalizar seu projeto mantendo uma conexão com o código original.

## 📦 Como Executar

1. Clone o repositório:
git clone https://github.com/karinaburguez/dio-gtf-start-6-classificador.git


2. Navegue até o diretório do projeto:
cd dio-gtf-start-6-classificador


3. Execute o programa.

## 📚 Links Úteis

- [DIO - Plataforma de Cursos](https://www.dio.me/)
- [GitHub para Desenvolvedores](https://docs.github.com/)

---

Desenvolvido por [Karina Burguez](https://github.com/karinaburguez) como parte do desafio do Bootcamp GFT Start #6 - Lógica de Programação da DIO.
