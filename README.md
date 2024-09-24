# Projeto Bola 8 Mágica

Este projeto é uma implementação simples de uma **Bola 8 Mágica** usando JavaScript. O programa simula uma bola mágica que responde a qualquer pergunta de sim ou não feita pelo usuário.

## Descrição

O código foi criado como parte de um exercício da Codecademy para praticar conceitos básicos de JavaScript, como:
- **Variáveis**
- **Operadores condicionais (ternários)**
- **Declaração switch**
- **Geração de números aleatórios**

O programa permite que o usuário insira seu nome e uma pergunta de sim ou não. Com base em um número gerado aleatoriamente, o programa fornece uma resposta da bola 8 mágica.

## Detalhamento do Código

1. **Informações do Usuário**:
   - A variável `userName` armazena o nome do usuário.
   - A variável `userQuestion` armazena a pergunta feita pelo usuário.
   - Se um nome for fornecido, o programa cumprimenta o usuário pessoalmente; caso contrário, ele usa uma saudação genérica.

2. **Geração de Resposta Aleatória**:
   - Um número aleatório entre 0 e 7 é gerado usando `Math.random()` e `Math.floor()`.
   - Esse número é então mapeado para uma das oito respostas predefinidas usando uma declaração `switch`.

3. **Respostas da Bola 8**:
   - Dependendo do valor de `randomNumber`, a variável `eightBall` é definida com uma das possíveis respostas da bola 8:
     - "É certo"
     - "Definitivamente sim"
     - "Resposta incerta, tente novamente"
     - "Não posso prever agora"
     - "Não conte com isso"
     - "Minhas fontes dizem não"
     - "As perspectivas não são boas"
     - "Os sinais apontam que sim"

4. **Saída**:
   - O programa exibe uma saudação e, em seguida, mostra a pergunta do usuário.
   - Ele então fornece a resposta da bola 8 mágica.

## Exemplo de Saída

Aqui está um exemplo do que o programa pode exibir ao ser executado:

```bash
Olá, Pedro!
Pedro perguntou - Eu sou feio?
A bola 8 mágica disse, Minhas fontes dizem não
