# Animação de Eclipse Solar 🌒

Este projeto cria uma animação simples de um eclipse solar, simulando o movimento da lua passando em frente ao sol. A ideia é representar visualmente a transição do dia para a noite usando apenas animações CSS.

Este projeto foi uma aula sobre CSS que explora animações visuais e efeitos interessantes com `transform`, `animation`, `@keyframes`, e manipulação de cores.

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3 (com `@keyframes` para animações)

## 🎨 Como funciona

- O elemento `.sun` representa o sol com um círculo amarelo.
- A `.shadow` simula a lua passando à frente do sol, com movimento horizontal via `@keyframes moveshadow`.
- O `body` muda de cor com `@keyframes dayToNight`, alternando de branco (dia) para preto (noite) e retornando.

## ⏱️ Animação

- A animação é contínua e cíclica, com duração de 10 segundos.
- Inclui um pequeno atraso inicial de 1.5 segundos (`animation-delay`).

## 📌 Observações

- Este projeto é totalmente responsivo ao tamanho da janela.
- Não requer nenhuma biblioteca externa ou JavaScript.
