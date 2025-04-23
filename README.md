# Documentação do Projeto: Classificador de Nível de Herói

## Descrição

Este projeto consiste em um site desenvolvido com as tecnologias HTML, CSS e JavaScript, onde o usuário pode inserir o nome e a quantidade de XP (experiência) de um herói. Com base na quantidade de XP informada, o sistema retorna o nível correspondente ao herói, conforme a seguinte tabela de níveis:

- **Ferro**: XP menor que 1000
- **Bronze**: XP entre 1000 e 2000
- **Prata**: XP entre 2000 e 5000
- **Ouro**: XP entre 5000 e 7000
- **Platina**: XP entre 7000 e 8000
- **Ascendente**: XP entre 8000 e 9000
- **Imortal**: XP entre 9000 e 10000
- **Radiante**: XP maior ou igual a 10000

A lógica de cálculo do nível do herói é implementada utilizando um código JavaScript simples, que compara a quantidade de XP informada com os intervalos definidos para cada nível.

## Tecnologias Utilizadas

- **HTML**: Para estruturação do conteúdo da página.
- **CSS**: Para estilização e apresentação visual da página.
- **JavaScript**: Para a implementação da lógica de cálculo e interação com o usuário.

## Estrutura do Projeto

### Arquivos do Projeto

1. **index.html**: Página principal com o formulário de entrada e exibição do nível.
2. **style.css**: Arquivo de estilos para o design da página.
3. **script.js**: Arquivo JavaScript que contém a lógica de cálculo do nível do herói.

## Como Usar

1. Abra o arquivo `index.html` em um navegador.
2. Insira o nome do herói no campo "Nome do Herói".
3. Insira a quantidade de XP no campo "Quantidade de XP".
4. Clique no botão "Consultar".
5. O nível do herói será exibido abaixo do formulário.

## Explicação da Lógica de Cálculo

A lógica de cálculo do nível do herói é baseada em uma série de condições `if` em JavaScript. Quando o formulário é enviado, o script obtém a quantidade de XP fornecida pelo usuário e compara com os intervalos predefinidos para determinar o nível correspondente.

Exemplo de como a lógica funciona:
- Se o XP for inferior a 1000, o nível será "Ferro".
- Se o XP estiver entre 1000 e 2000, o nível será "Bronze", e assim por diante até o nível "Radiante" para XP superior a 10000.

## Conclusão

Este projeto oferece uma forma simples e interativa de calcular o nível de um herói com base na quantidade de XP. Ele pode ser expandido para incluir mais funcionalidades, como salvar o histórico de heróis ou aplicar diferentes estilos de visualização para cada nível.
