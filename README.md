# CodeTables: Medieval

CodeTables: Medieval é um jogo de tabuleiro estratégico que ensina conceitos fundamentais de lógica de programação através de mecânicas inspiradas em programação por blocos. Os jogadores devem criar sequências de comandos para controlar seus personagens, enfrentar adversários e cumprir os objetivos do modo de jogo escolhido.

O jogo combina estratégia, raciocínio lógico, trabalho em equipe e tomada de decisão, proporcionando uma experiência divertida enquanto desenvolve habilidades relacionadas à programação e resolução de problemas.

## Autores

- Emanuel Gomes Bispo
- Neemias Vasconcelos
- Marco Antonio Bomfim
- Gustavo Ramon Ribeiro

## Sobre o jogo

O tabuleiro possui dimensões de **11x7 casas**, dividido em dois territórios separados por uma ravina. Os jogadores precisam utilizar blocos de programação para movimentar seus personagens, atacar inimigos e conquistar seus objetivos.

O jogo possui três modos principais:

| Modo | Objetivo | Duração |
|------|----------|---------|
| Duelo Solo | Derrotar todos os personagens inimigos | ~15 minutos |
| Duelo em Dupla | Derrotar todos os personagens inimigos | ~30 minutos |
| Guerra | Destruir a fortaleza inimiga e derrotar todos os personagens | 1 hora ou mais |

## Componentes

O jogo é composto por:

- Tabuleiro 11x7
- Personagens
- Fortalezas
- Pontes
- Obstáculos
- Cartas
- Blocos de programação
- Dados de ação
- Marcadores de vida

## Preparação

Antes do início da partida:

1. Escolha o modo de jogo.
2. Defina as equipes.
3. O monitor monta o tabuleiro.
4. Posicione as fortalezas.
5. Coloque as pontes.
6. Cada equipe posiciona seus obstáculos na área adversária.
7. Os jogadores posicionam seus personagens na área inicial.
8. Defina a ordem dos jogadores utilizando um dado.

Após essa preparação, a partida pode começar.

## Como jogar

O jogo acontece em turnos.

No início de cada turno:

1. O jogador lança o dado de ação.
2. O número obtido representa a quantidade de ações disponíveis.
3. Utilizando os blocos de programação, o jogador monta sua sequência de comandos.
4. O monitor verifica se a sequência é válida.
5. Caso esteja correta, os movimentos são executados.

Se a sequência estiver incorreta, o jogador possui uma segunda tentativa. Caso erre novamente, perde o turno.

## Blocos de Programação

O sistema utiliza blocos semelhantes aos encontrados em ambientes de programação visual.

### Blocos obrigatórios

- Início
- Fim

Sem esses dois blocos a sequência é considerada inválida.

### Blocos de Movimento

- Mover
- Virar à esquerda
- Virar à direita
- Virar para trás

Somente o bloco **Mover** consome ações.

### Bloco de Ação

O bloco **FAÇA** executa uma ação do personagem, normalmente um ataque.

## Sistema de Combate

Cada personagem possui:

- 4 pontos de vida

No modo Guerra:

- A fortaleza possui 10 pontos de vida.

Os ataques são realizados utilizando o bloco **FAÇA**, desde que o inimigo esteja exatamente uma casa à frente do personagem.

O ataque básico causa:

- 1 ponto de dano.

Cartas especiais podem modificar ou fortalecer esse ataque.

## Cartas

Durante a partida, os jogadores podem adquirir cartas que oferecem vantagens estratégicas.

Tipos de cartas:

- Ataque
- Defesa
- Jogabilidade
- Neutra

Raridades:

- Comum
- Especial
- Coringa

Cada jogador pode possuir até **5 cartas** em seu deck e utilizar apenas **1 carta por turno**, salvo exceções descritas pela própria carta.

## Obstáculos

Os obstáculos tornam a movimentação mais estratégica.

### Obstáculos Padrão

Impedem completamente a passagem.

- Árvore
- Pedra

### Obstáculos Perigosos

Podem ser atravessados, porém aplicam penalidades.

- Buraco
- Poça de água

## Condições de Vitória

### Duelo

A equipe vence ao derrotar todos os personagens adversários.

### Guerra

A equipe vence quando:

- Destrói a fortaleza inimiga;
- Elimina todos os personagens adversários.

## Objetivos Educacionais

O CodeTables foi desenvolvido para estimular habilidades importantes, como:

- Pensamento computacional;
- Lógica de programação;
- Planejamento de algoritmos;
- Resolução de problemas;
- Trabalho em equipe;
- Estratégia.

## Tecnologias Utilizadas

Projeto físico desenvolvido utilizando:

- Modelagem 3D
- Impressão 3D
- Blocos de programação físicos
- Cartas ilustradas
- Tabuleiro modular

## Licença

Este projeto foi desenvolvido para fins educacionais e de entretenimento.
