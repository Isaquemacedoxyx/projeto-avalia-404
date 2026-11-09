# Avalia 404

Projeto desenvolvido em Python com o objetivo de praticar conceitos de programação por meio de um sistema de gerenciamento de notas e acompanhamento do desempenho acadêmico de alunos.

A aplicação funciona pelo terminal e permite registrar notas e faltas, calcular médias, verificar situações acadêmicas e gerar relatórios individuais e gerais.

## Funcionalidades

- Cadastro de notas e faltas para uma lista predefinida de alunos.
- Registro de notas de dois semestres em cinco disciplinas.
- Validação de notas, aceitando valores entre 0 e 10.
- Validação da quantidade de faltas, impedindo valores negativos.
- Cálculo da média por disciplina.
- Verificação da situação do aluno por nota e frequência.
- Geração de relatórios individuais e resumo geral de aprovados e reprovados.

## Regras de avaliação

O sistema utiliza os seguintes critérios:

- Média igual ou superior a 6,0: aprovação por nota.
- Média inferior a 6,0: reprovação por nota.
- 51 faltas ou mais: reprovação por faltas.
- A aprovação geral do aluno depende da aprovação em todas as disciplinas.

## Tecnologias utilizadas

- Python
- Estruturas condicionais
- Laços de repetição
- Funções
- Listas e dicionários
- Tratamento de exceções (`try` e `except`)

## Como executar

**Pré-requisito:** Python instalado.

1. Clone este repositório:

```bash
git clone https://github.com/Isaquemacedoxyx/projeto-avalia-404.git
```

2. Acesse a pasta do projeto:

```bash
cd projeto-avalia-404
```

3. Execute o programa:

```bash
python avalia_404.py
```

## Estrutura do projeto

```text
projeto-avalia-404/
│
├── avalia_404.py
└── README.md
```

## Objetivo de aprendizagem

Este projeto foi desenvolvido para colocar em prática os fundamentos da linguagem Python, trabalhando principalmente com organização de funções, validação de dados, estruturas de repetição, estruturas condicionais e manipulação de coleções.

É um projeto de caráter acadêmico, desenvolvido como parte do meu processo de aprendizagem em programação.
