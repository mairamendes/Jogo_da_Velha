# Jogo da Velha - Bomberman Theme

Este é um jogo da velha inspirado na temática do clássico jogo Bomberman. O jogo pode ser jogado entre duas pessoas ou contra um oponente controlado pelo computador.

## Tecnologias Utilizadas
- **HTML** para estruturação da página
- **CSS** para estilização
- **JavaScript** para a lógica do jogo e interação com o usuário

## Como Jogar
1. Abra o arquivo `index.html` em um navegador.
2. Escolha entre jogar contra outro jogador ou contra o computador.
3. Clique nos espaços vazios do tabuleiro para fazer sua jogada.
4. O jogo alterna entre os jogadores "preto" e "vermelho".
5. O primeiro jogador a alinhar três símbolos na horizontal, vertical ou diagonal vence.
6. Se todas as casas forem preenchidas e não houver vencedor, o jogo termina em empate ("Deu Velha").

## Regras
- Os jogadores se alternam a cada jogada.
- Apenas pode-se jogar em casas vazias.
- O jogo detecta automaticamente uma vitória ou empate e finaliza a partida.

## Implementação
O jogo é implementado em JavaScript, com funções para:
- Verificar a jogada do jogador (`checkjogo(id)`).
- Determinar se houve um vencedor (`wincheck()`).
- Controlar a jogada do computador (`JogoDoPc()`).

## Melhorias Futuras
- Adicionar animações para as jogadas.
- Melhorar a inteligência artificial do computador.
- Criar um design mais sofisticado para o tabuleiro.

## Autor
Projeto desenvolvido por Maíra Mendes Silva.

