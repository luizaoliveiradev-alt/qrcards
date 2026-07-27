# qrcards
Aplicação web em Vanilla JS/CSS3 para sorteio aleatório de cartas com suporte a vídeos MP4 dinâmicos e proteção anti-cheat.

# 🃏 QR CARDS - Cartas Interativas com Vídeo

O **QR CARDS** é uma aplicação web interativa desenvolvida para sortear aleatoriamente comandos em um jogo de cartas. O diferencial desta versão é o uso de **vídeos animados em looping/execução automática (MP4)** no lugar de artes estáticas, proporcionando uma experiência imersiva e dinâmica para os jogadores.

![Preview do Projeto](https://img.shields.io/badge/Status-Concluído-brightgreen)
![License](https://img.shields.io/badge/Licença-MIT-blue)

---

## 🚀 Funcionalidades

- 🎲 **Sorteio Aleatório**: A cada carregamento/chamada, uma carta de comando é selecionada de forma randômica.
- 🎥 **Animações em Vídeo**: Uso de vídeos otimizados (`.mp4`) com execução automática (*autoplay*) e silenciosa (*muted*), garantindo compatibilidade com navegadores web e dispositivos móveis (iOS/Android).
- 🛡️ **Proteção de Tela / Anti-Cheat**: Bloqueio de menu de contexto (clique direito), teclas de atalho de inspeção do navegador (F12, Ctrl+Shift+I, etc.) e tentativa de captura de tela.
- 📱 **Design Responsivo**: Adaptado para telas de smartphones e tablets, utilizando unidades dinâmicas e proporcionalidade ideal para cartas de baralho (`aspect-ratio: 3/5`).

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica utilizando elementos `<video>` e tags dinâmicas.
- **CSS3**: Estilização moderna com Flexbox, CSS Clamp para tipografia responsiva e efeitos de transição de visibilidade.
- **JavaScript (Vanilla JS)**: Lógica de sorteio, manipulação de DOM e interceptação de eventos de teclado/mouse.
- **Google Fonts**: Fontes *Figtree* e *Fraunces* para tipografia estilizada.

---

## 🃏 Lista de Cartas e Efeitos

| Carta | Ação | Mídia |
| :--- | :--- | :--- |
| **Ataque!** | Escolha um jogador para comprar 5 cartas. | Vídeo MP4 |
| **Sorte** | Todos compram uma carta, menos você. | Vídeo MP4 |
| **Extra** | Jogue novamente. | Vídeo MP4 |
| **Bloqueio** | Pule a vez de um jogador. | Vídeo MP4 |
| **Troca** | Troque toda sua mão com o jogador à esquerda. | Vídeo MP4 |
| **Silêncio** | Fique em silêncio até sua próxima rodada. | Vídeo MP4 |
| **Humor** | Conte uma piada para poder jogar novamente. | Vídeo MP4 |
| **Punição** | Compre 5 cartas. | Vídeo MP4 |
| **Confusão** | Escolha dois jogadores para trocarem de mão. | Vídeo MP4 |
| **Dança das cadeiras** | Todos mudam de lugar na mesa. | Vídeo MP4 |
