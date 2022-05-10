# Minecraft-Python
Coloque o Python dentro do minecraft!!!

Galera os comandos usaveis estão aqui :

                                                Commandos Suportados

• world.get/setBlock

• world.getBlockWithData

• world.setBlocks

• world.getPlayerIds

• world.getBlocks

• chat.post

• events.clear

• events.block.hits

• player.getTile

• player.setTile

• player.getPos

• player.setPos

• world.getHeight

• entity.getTile

• entity.setTile

• entity.getPos

• entity.setPos

                                               Comandos não suportados

• Camera angles

                                               Comandos Extras

• getBlocks(x1,y1,z1,x2,y2,z2) - foi implementado

• getDirection, getRotation, getPitch functions - obter a 'direção' que os jogadores e entidades estão enfrentando

• setDirection, setRotation, setPitch functions - definir a 'direção' que jogadores e entidades estão enfrentando

• getPlayerId(playerName) - obter a entidade de um jogador pelo nome

• pollChatPosts() - obter eventos de volta para postagens no bate-papo

• spawnEntity(x,y,z,entity) - cria uma entidade e retorna seu ID de entidade. veja entity.py para lista.

• getEntityTypes - retorna todas as entidades suportadas pelo servidor.

• entity.getName(id) - obter um nome de jogador para o ID da entidade. Reverso de getPlayerId(playerName)

• getEntities - obter todas as listas de entidades atualmente carregadas por ID de tipo de entidade opcional

• removeEntity - remove a entidade com o id especificado

• removeEntities - remove todas as entidades atualmente carregadas por ID de tipo de entidade opcional

• entity.getEntities - obter a lista de entidades atualmente carregadas perto do ID da entidade do jogador especificado pelo ID do tipo de entidade opcional

• entity.removeEntities - remove entidades atualmente carregadas próximas à entidade especificada, por ID de tipo de entidade opcional

• player.getEntities - obter a lista de entidades atualmente carregadas perto do ID da entidade do jogador especificado pelo ID do tipo de entidade opcional

• player.removeEntities - remove entidades atualmente carregadas próximas ao ID de entidade do player especificado, por ID de tipo de entidade opcional

• events.pollProjectileHits - obter eventos de volta do acerto da flecha

• player.pollProjectileHits - obter eventos de volta da flecha atingida para o jogador

• player.pollBlockHits - obter hits de bloqueio para o jogador

• player.pollChatPosts - obter eventos de volta para postagens no bate-papo do jogador

• player.clearEvents - eventos claros para o jogador

• entity.pollProjectileHits - obter eventos de volta da flecha atingida para uma entidade

• entity.pollBlockHits - obter hits de bloco para uma entidade

• entity.pollChatPosts - obter eventos de volta para postagens no bate-papo de uma entidade

• entity.clearEvents - eventos claros para esta entidade

Observação - NÃO há garantia de manutenção de recursos extras em versões futuras, principalmente se forem feitas atualizações na API Pi original que substituem a funcionalidade



