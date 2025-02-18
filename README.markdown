# Blackjack

Licence: [BSD](http://creativecommons.org/licenses/BSD/)

Um jogo de Blackjack em Java escrito por David Winter para um projeto universitário. [David Winter](http://davidwinter.me.uk) 

Para instruções de compilação, consulte o arquivo BUILDING.


## Histórico de Alterações

### Alterações realizadas - Disciplina intensiva

#### Correções e melhorias:
- Corrigido o botão **Double**, ajustando-o conforme as regras do jogo.
- Corrigido o nome dos jogadores.
- Adicionada a funcionalidade para visualizar o histórico das jogadas.
- Adicionados botões para reduzir o valor da aposta de 1 em 1 e 10 em 10.
- Adicionado o botão **All In**.
- Ajustado o pop-up exibido quando um ou mais jogadores zeram o saldo.
- Ajustada a funcionalidade de limpar o placar.
- Corrigida a mensagem de aviso quando todos os jogadores precisam escolher um valor de aposta.
- Melhorada a responsividade, evitando que alguns botões fiquem ocultos.
- Ajustado o botão **Deal**.

#### Outras melhorias no jogo:
- Ajustadas as cores dos textos para garantir visibilidade em qualquer cor de fundo.
- Limpando os dados da tela ao finalizar a rodada.
- Campos de ação bloqueados da mesma forma que os botões inferiores.
- Impedido o redimensionamento que cortava os valores exibidos.
- Reposicionamento de botões para melhor usabilidade.
- Adicionadas funcionalidades para configurar o perfil do jogador (válido para os dois jogadores).
- Modificado o layout de apresentação das cartas.
- Incluído um botão para reiniciar o jogo.
- Criado um segundo jogador, permitindo modo multiplayer.
- Dividida a interface de interação para que os jogadores possam jogar de forma independente.
- Adicionadas mensagens de fim de jogo.
- Implementada a jogabilidade do multiplayer, permitindo que um jogador continue jogando caso o outro perca.

#### Alterações realizadas recentemente - Disciplina de Manutenção 02/2024:
- Descrição de acordo com valores em carteira e apostado.
- Ajustado o **Botão de Reset** para iniciar com o valor correto.
- Adicionado arquivo pom.
- Redução de code smells.
- Visualização dos **code smells** pelo [SonarCloud](https://sonarcloud.io/project/issues?issueStatuses=OPEN%2CCONFIRMED&id=AnaBeCosta_blackjack_manutencao).
