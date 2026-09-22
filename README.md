# Sistema de cadastro de veículos

## Identificação

- **Disciplina:** Organização e Abstração na Programação
- **Trabalho:** Sistema de cadastro de veículos
- **Integrante:** Talysson da Costa
- **Instituição:** Universidade Atitus
- **Professor:** Luciano Ferretto

## Descrição do sistema

Este trabalho consiste no desenvolvimento de um sistema de cadastro de veículos em Java, executado pelo terminal. O programa apresenta um menu interativo que permite ao usuário cadastrar veículos, visualizar todos os veículos cadastrados e consultar um veículo específico por meio da placa.

Cada veículo é representado pelos dados de placa, modelo, marca e ano de fabricação. Durante o cadastro, o sistema verifica se todos os campos foram preenchidos, impede o registro de placas duplicadas, normaliza a placa informada e valida se o ano está dentro de um intervalo aceitável. Também são exibidas mensagens para orientar o usuário sobre o sucesso ou erro de cada operação.

O programa utiliza uma estrutura de repetição `do-while` para manter o menu em execução até que o usuário escolha a opção de saída. A seleção das operações é realizada com `switch`, enquanto as validações e buscas utilizam estruturas condicionais `if` e laços `for`. A classe `Veiculo` organiza os dados e os comportamentos básicos dos veículos cadastrados, e uma lista mantém os registros durante a execução do programa.

### Relação com o enunciado da atividade

O enunciado fornecido pelo professor descreve uma atividade de cálculo e classificação do IMC, com entrada de nome, gênero, altura e peso. A implementação presente neste projeto possui uma proposta diferente: trata-se de um sistema de cadastro de veículos. Portanto, ela não realiza o cálculo do IMC nem utiliza o `switch` para classificar gênero conforme a tabela apresentada no enunciado.

Apesar dessa diferença de tema, o programa aplica conceitos semelhantes aos trabalhados na atividade, como entrada e saída de dados, uso de `switch`, estruturas `if`, repetição, validação de informações e organização dos dados em Java.

## Instruções de execução

### Requisitos

- Java SDK 27 ou superior;
- Terminal ou IDE compatível com Java.

## Tecnologias e conceitos

- Java SDK;
- Git;
- Programação orientada a objetos;
- Entrada e saída de dados pelo terminal com `IO.readln` e `IO.println`;
- Estrutura de repetição `do-while`;
- Estrutura condicional `switch`;
- Estruturas condicionais `if`;
- Listas com `ArrayList`;
- Validação e tratamento de entradas inválidas;
- Manipulação e normalização de texto.