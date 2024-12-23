# Compilador - Análise Léxica, Sintática e Semântica

Este projeto implementa as etapas de **análise léxica**, **análise sintática** e **análise semântica** de um compilador, conforme o diagrama apresentado.

## Descrição

- **Análise Léxica**:
  - Identifica e categoriza os tokens do código-fonte, incluindo:
    - **Identificadores**: `(letra | "_")(letra | "_" | dígito)*`
    - **Números inteiros**: `dígito+`
    - **Números reais**: `dígito+.dígito+`
    - **Caracteres especiais**: `")", "(", "{", "}", ",", ";"`
    - **Fim de código**: `$`

- **Análise Sintática**:
  - Verifica a conformidade da sequência de tokens de acordo com as regras gramaticais definidas.

- **Análise Semântica**:
  - Realiza a validação dos significados dos tokens e da estrutura do código, garantindo que os identificadores, tipos de dados e demais elementos estejam semanticamente corretos.

 ## Representação Gráfica

O diagrama abaixo representa as etapas de análise do compilador:

![Exemplo - Máquinas - Expressões](https://github.com/user-attachments/assets/92ddfca3-191c-4f65-b470-2c2420abd559)

