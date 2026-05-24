# 🎮 CMD RPG — MARBION

---

# 👤 PERFIL

## !raça
Desperta uma raça aleatória para o jogador.

Se o jogador já tiver raça:
- mostra a raça atual
- mostra a Arma Vínculo atual, se tiver

Se o jogador estiver morto:
- permite reencarnar
- morte não conta como rebuff
- reencarnação por morte não entrega buff

---

## !pinfo
Mostra:
- raça
- elementos
- tag equipada
- nível
- XP total
- níveis elementais
- mortes
- rebuffs
- Arma Vínculo, se existir

---

## !synclevel
Sincroniza o nível baseado no XP atual.

---

## !setlvl @usuario nível
Define manualmente:
- nível
- XP correspondente

Ex:
```txt
!setlvl @SilenceWorky 100
```

---

## !resetraca @usuario
Reseta completamente:
- raça
- XP
- nível
- elementos
- inventário
- progresso

---

# 🌌 ELEMENTOS

## !elemento
Desperta:
- 1 elemento
- ou combinação de 2 elementos

Sistema:
- pesos de raridade
- combinações raras
- elementos exclusivos

---

## !reroll
Rerolla os elementos do jogador.

Cooldown:
- 24h

---

## !infelem nome
Mostra:
- descrição
- raridade
- emoji
- informações do elemento

Ex:
```txt
!infelem Fogo
```

---

## !setlvlelem usuario elemento nivel
Define:
- nível elemental
- XP elemental

Ex:
```txt
!setlvlelem SilenceWorky Agua 10
```

---

## !resetelemento @usuario
Reseta:
- elementos
- XP elemental
- níveis elementais

---

# 🏷️ TAGS

## !tag
Mostra a tag equipada.

---

## !tags
Mostra:
- tag equipada
- tags desbloqueadas

---

## !settag nome
Equipa uma tag desbloqueada.

Ex:
```txt
!settag Chama Suprema
```

---

## !admsettag @usuario tag
Entrega/equipa tags manualmente.

---

## !addtag nome
Cria uma tag customizada.

---

## !removetag nome
Remove uma tag customizada.

---

# 🎁 XP E RECOMPENSAS

## !checkin
Ganha XP.

Cooldown:
- 15min

---

## !daily
Sistema de recompensa diária.

Inclui:
- streak
- bônus de streak
- XP escalável

Cooldown:
- 24h

---

## !xpchest
Baú de XP.

Pode entregar:
- XP normal
- XP elemental

Cooldown:
- 12h

---

# 👹 MOBS

## Sistema de mobs
- Spawn automático ✔️
- Spawn manual ✔️
- Spawn por raridade ✔️
- Spawn específico ✔️
- Despawn automático ✔️
- Sistema elemental ✔️
- Sistema de drops ✔️
- Boss impede spawn ✔️

---

## !mob
Spawna:
- mob aleatório
- mob específico
- raridade específica

Ex:
```txt
!mob
!mob Slime_Corrompido
!mob raro
!mob lendario
```

---

## !vermob
Mostra:
- nome
- raridade
- elementos
- HP
- tempo restante

---

## !combate
Ataca:
- mobs
- bosses

Sistema:
- hit chance
- dano
- XP
- drops
- cooldown
- dano da Arma Vínculo ✔️
- crítico da Arma Vínculo ✔️
- efeitos especiais de Armas ADM ✔️
- durabilidade da Arma Vínculo ✔️
- bônus de rebuff ✔️

---

## !mobon
Ativa spawn automático de mobs.

---

## !moboff
Desativa spawn automático de mobs.

---

# 👑 BOSSES

## Sistema de bosses
- Spawn automático ✔️
- Spawn manual ✔️
- Boss global ⏳
- Fila de espera ✔️
- Despawn automático ✔️
- Boss impede spawn de mob ✔️
- Spawn entre 1h–2h ✔️
- Boss surge após morte do mob ✔️
- Barra global de HP ✔️
- Alertas animados ✔️
- Música dinâmica ✔️

---

## !boss
Spawna um boss aleatório.

Se houver mob:
- entra na fila

---

## !boss nome
Spawna um boss específico.

Ex:
```txt
!boss Jean_Darwin
```

---

## !viewboss
Mostra:
- boss ativo
- HP
- tempo restante
- boss na fila
- bosses disponíveis

---

## !killboss
Remove o boss ativo.

---

## !bosson
Ativa spawn automático de bosses.

---

## !bossoff
Desativa spawn automático de bosses.

---

# 🗡️ ARMAS VÍNCULOS E ARMAS ADM

## Sistema de Armas Vínculos
- Arma Vínculo por perfil ✔️
- Apenas 1 Arma Vínculo por jogador ✔️
- Arma ligada à alma ✔️
- Arma não é perdida em rebuff normal ✔️
- Arma não é perdida em morte normal ✔️
- Arma é perdida se quebrar ✔️
- Quebra da Arma Vínculo causa morte ✔️
- 10 mortes apagam o perfil ✔️
- Raridades organizadas por:
  - Comum
  - Incomum
  - Raro
  - Muito Raro
  - Lendário
  - ADM

---

## Sistema de Armas ADM
- 7 Armas ADM especiais ✔️
- Efeitos definidos pelo ADM portador ✔️
- Elementos inicialmente vazios/neutros até definição do ADM ✔️
- Armas ADM podem ter efeitos programados individualmente ✔️

Armas ADM atuais:
- Espada do Rei
- Adagas do Príncipe
- Machado do Caos
- Lança da Guarda
- Arco Imperial
- Foice das Sombras
- Khopesh dos Rios

---

## !arma nome_da_arma
Mostra as informações de uma arma pelo nome.

Ex:
```txt
!arma Khopesh_dos_Rios
```

---

## !minhaarma
Mostra a Arma Vínculo atual do jogador:
- nome
- raridade
- tipo
- elementos
- dano
- crítico
- durabilidade
- efeito
- descrição

---

## !rollarma
Sorteia uma Arma Vínculo para jogadores antigos que ainda não possuem uma.

---

## !addarma @usuario nome_da_arma
Comando ADM.

Define manualmente:
- Arma Vínculo
- ou Arma ADM

Ex:
```txt
!addarma @SilenceWorky Khopesh_dos_Rios
```

---

## !removerarma @usuario
Comando ADM.

Remove a Arma Vínculo de um jogador.

Ex:
```txt
!removerarma @SilenceWorky
```

---

# 💀 MORTE E REENCARNAÇÃO

## Sistema de morte
Quando um jogador morre:
- ganha +1 morte
- fica marcado como morto
- precisa usar !raça para reencarnar
- morte normal não conta como rebuff
- morte normal não remove Arma Vínculo

---

## Bloqueio de comandos ao morrer
Jogador morto não pode usar comandos principais.

Permitido:
- !raça para reencarnar

Bloqueado:
- combate
- checkin
- daily
- xpchest
- rebuff
- outros comandos de progressão

---

## Quebra de Arma Vínculo
Se a Arma Vínculo quebra:
- o jogador morre
- perde a Arma Vínculo
- conta como morte
- precisa reencarnar com !raça

---

## Limite de mortes
Ao atingir 10 mortes:
- ocorre ruptura total da alma
- o perfil é apagado completamente
- o jogador recomeça do zero absoluto

---

# ♻️ REBUFF

## !rebuff
Reinicia o progresso voluntariamente para ganhar bônus permanentes.

Rebuff normal:
- não conta como morte
- não remove Arma Vínculo
- mantém durabilidade atual da arma
- reseta nível
- reseta XP
- rerolla raça
- rerolla elementos
- concede buff permanente

---

## Requisitos de rebuff
- Rebuff 1: nível 50
- Rebuff 2: nível 100
- Rebuff 3: nível 200
- Rebuff 4: nível 500
- Rebuff 5: nível 1000
- Rebuff 6: nível 2000
- Rebuff 7: nível 3500
- Rebuff 8: nível 5000
- Rebuff 9: nível 7500
- Rebuff 10: nível 10000

---

## Buffs de rebuff
Cada rebuff concede:
- +2 dano permanente
- +5% XP permanente
- +1% crítico permanente

Ex:
```txt
Rebuff 5 = +10 dano, +25% XP, +5% crítico
```

---

# ⚔️ PVP

## Sistema PvP
- Duelo ✔️
- Rank ✔️
- RP ✔️
- Winrate ✔️
- Sistema de streak ✔️
- Sistema de vantagem elemental ✔️
- Palavra rápida ✔️

---

## !duelo @usuario
Desafia outro jogador.

---

## !aceito
Aceita duelo.

---

## !recuso
Recusa duelo.

---

## !responder palavra
Sistema de vantagem rápida.

---

## !pvp
Mostra:
- rank
- RP
- vitórias
- derrotas
- streak
- melhor streak
- winrate

---

## !toprank
Mostra top ranking PvP.

---

## !toprank usuario
Mostra posição específica.

Ex:
```txt
!toprank SilenceWorky
```

---

# 🎒 ITENS

## Sistema de itens
- Inventário ✔️
- Drops ✔️
- Itens customizados ✔️

---

## !inventario
Mostra o inventário.

---

## !item nome
Mostra:
- descrição
- raridade
- tipo
- emoji

Ex:
```txt
!item Fragmento_Corrompido
```

---

## !giveitem
Entrega item manualmente.

Ex:
```txt
!giveitem @usuario item quantidade
```

---

# 🔮 Sistemas Futuros

## 🌟 PRIORIDADE MÁXIMA

- Sistema de HP real do jogador ⏳
- Sistema de skills/habilidades especiais ⏳
- Combate por turnos ⏳
- Sistema de morte completo ✔️
- Sistema de rebuff ✔️
- Sistema de fases de boss ✔️
- Boss enfurecido ✔️
- Mudança visual da barra por HP ✔️
- Alertas especiais de fase ✔️
- Sistema de execução/piedade PvP ⏳
- Comando `!poupar` ⏳
- Comando `!executar` ⏳
- Reencarnação forçada ✔️
- Sistema de Reencarnação ✔️
- Limite de 10 Reencarnações/Mortes ✔️
- Último Ciclo ⏳
- Recomeço oficial sem buffs ✔️

---

## 👑 SISTEMA DE BOSSES

- Raid Boss global ⏳
- Bosses com múltiplas fases ✔️
- Bosses lendários ultra raros ⏳
- Música dinâmica de boss ✔️
- Overlay de raid ✔️
- Overlay de loot ⏳
- Overlay de level up ⏳
- Overlay PvP ⏳
- Kill feed ⏳
- Mini mapa de eventos ⏳
- HUD MMORPG completa ⏳

---

## ⚔️ COMBATE

- Sistema de skills ⏳
- Sistema de classes ⏳
- Sistema de efeitos/status ⏳
- Crítico ✔️
- Esquiva ⏳
- Buffs/Debuffs ⏳
- Dano elemental ⏳
- Resistências elementais ⏳
- Fraquezas elementais ⏳
- Combos elementais ⏳
- Sistema de HP real do jogador ⏳

---

## 🗡️ ARMAS

- Sistema de armas ✔️
- Armas permanentes por perfil ✔️
- Armas Vínculos ✔️
- Armas ADM ✔️
- Sistema de armaduras ⏳
- Durabilidade de armas ✔️
- Ferreiro/reparo de armas ⏳
- Efeitos especiais de armas ✔️
- Armas infinitas ✔️
- Comando ADM `!rearma` ⏳
- 7 armas especiais de ADM ✔️
- Drops reais de armas ⏳
- Armas normais equipáveis ⏳

---

## 🏛️ SOCIAL

- Sistema de guildas ⏳
- Sistema de clans ⏳
- Guerra de guildas ⏳
- Boss de guilda ⏳
- Chat de guilda ⏳
- Sistema de títulos ⏳
- Sistema de achievements ⏳

---

## 💰 ECONOMIA

- Sistema de economia ⏳
- Sistema de loja ⏳
- Sistema de trade ⏳
- Sistema de marketplace ⏳
- Sistema de crafting ⏳

---

## 🌎 MUNDO

- Sistema de quests ⏳
- Sistema de NPCs ⏳
- Sistema de biomas ⏳
- Eventos globais ⏳
- Sistema de dungeons ⏳
- Sistema de relíquias ⏳

---

## 🎣 PROFISSÕES

- Sistema de pesca ⏳
- Sistema de mineração ⏳
- Sistema de alquimia ⏳
- Sistema de pets ⏳

---

## ✅ SISTEMAS JÁ IMPLEMENTADOS

- Overlay OBS de boss ✔️
- Alertas animados de boss ✔️
- Barra global de HP ✔️
- Sons personalizados de boss ✔️
- Música dinâmica de boss ✔️
- Fases visuais de boss ✔️
- Leaderboard PvP global ✔️
- Sistema de drops ✔️
- Sistema de bosses ✔️
- Sistema de fila de bosses ✔️
- Spawn automático de bosses ✔️
- Spawn automático de mobs ✔️
- PvP ranqueado ✔️
- Sistema de Armas Vínculos ✔️
- Sistema de Armas ADM ✔️
- Dano de arma no combate ✔️
- Crítico de arma no combate ✔️
- Durabilidade de Arma Vínculo ✔️
- Morte por quebra de Arma Vínculo ✔️
- Sistema de morte com limite de 10 mortes ✔️
- Sistema de rebuff ✔️
