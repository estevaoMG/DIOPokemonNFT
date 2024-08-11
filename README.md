# PokeDIO

PokeDIO é um contrato inteligente implementado em Solidity que permite a criação e batalha de Pokémons em um ambiente descentralizado na blockchain. Este contrato utiliza o padrão ERC721 para tokens não fungíveis (NFTs), permitindo que cada Pokémon seja único e possua características específicas.

## Funcionalidades

- **Criação de Pokémons**: Apenas o dono do jogo pode criar novos Pokémons.
- **Batalha entre Pokémons**: Proprietários de Pokémons podem batalhar entre si, com os níveis dos Pokémons sendo ajustados após a batalha.

## Detalhes do Contrato

### Estrutura `Pokemon`

Cada Pokémon é representado pela seguinte estrutura:

```solidity
struct Pokemon {
    string name;
    uint level;
    string img;
}
