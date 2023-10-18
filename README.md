# Jogo de Ludo em C

Este projeto é um jogo de Ludo feito com a linguagem C, ele foi desenvolvido como parte do trabalho final do curso de Algoritmos e Estrutura de Dados 1 no curso de Engenharia da Computação na Universidade do Estado de Minas Gerais - UEMG. O jogo segue basicamente as regras clássicas do Ludo, oferecendo uma experiência autêntica aos jogadores.

## Funcionalidades

- **Jogo de Ludo Clássico**: Implementa o tradicional jogo de tabuleiro Ludo, com suporte para 2 a 4 jogadores, onde cada jogador controla 4 peões.
- **Início e Movimento**: Os jogadores só podem mover um peão para o início da corrida, na casa de sua respectiva cor, ao lançar um 6 no dado. Após a colocação do peão no início, o jogador tem direito a um novo lançamento do dado.
- **Três Seis em Sequência**: Se um jogador tirar três vezes seguidas o valor 6 no dado, ele deve passar a vez, promovendo um jogo justo e dinâmico.
- **Finalização do Jogo**: O jogador deve levar os 4 peões até a casa final para vencer o jogo. Para fazer isso, ele deve tirar o valor exato restante no dado e, se bem-sucedido, terá direito a outra rodada no dado.
- **Captura de Peças**: É possível capturar o peão de outro jogador ao cair em uma casa já ocupada por um peão adversário. A captura força o peão adversário a retornar à posição inicial fora da trilha, proporcionando um elemento estratégico ao jogo. Além disso, após uma captura bem-sucedida, o jogador pode lançar o dado mais uma vez.
- **Pontos Seguros**: O tabuleiro possui casas seguras, que são consideradas pontos seguros onde os peões não podem ser capturados.
- **Movimentação Estratégica**: Os peões devem se mover e viajar contornando o tabuleiro até chegar à última casa. A cada rodada do dado, o jogador deve mover um peão, e não é permitido abdicar do movimento.
- **Escolha de Peão para Mover**: O programa permite que o jogador escolha qual dos peões (quando possível) ele deseja mover, oferecendo controle estratégico sobre suas peças.

## Como Jogar

1. Clone este repositório em sua máquina local.
2. Compile o programa usando um compilador C.
3. Execute o programa e siga as instruções para definir o número de jogadores, nomes e cores.

## Licença

Este projeto é licenciado sob a Licença MIT - consulte o arquivo ['LICENSE'](LICENSE) para obter mais detalhes.

## Contribuição

Contribuições são bem-vindas! Se você encontrar problemas ou tiver ideias para melhorias, sinta-se à vontade para abrir um problema ou enviar um pull request.
