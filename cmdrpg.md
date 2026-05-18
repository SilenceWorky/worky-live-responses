# 🎮 CMD RPG — MARBION

---

# 👤 PERFIL

## !raça
Desperta uma raça aleatória para o jogador.

---

## !pinfo
Mostra:
- raça
- elementos
- tag equipada
- nível
- XP total
- níveis elementais

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

- Overlay OBS de boss ⏳
- Alertas animados de boss ⏳
- Raid Boss global ⏳
- Bosses com múltiplas fases ⏳
- Sistema de skills ⏳
- Sistema de classes ⏳
- Sistema de guildas ⏳
- Sistema de crafting ⏳
- Sistema de marketplace ⏳
- Sistema de quests ⏳
- Sistema de NPCs ⏳
- Sistema de biomas ⏳
- Eventos globais ⏳
- Sistema de dungeons ⏳
- Sistema de achievements ⏳
- Sistema de títulos ⏳
- Sistema de relíquias ⏳
- Sistema de armas ⏳
- Sistema de armaduras ⏳
- Sistema de efeitos/status ⏳
- Sistema de pets ⏳
- Sistema de pesca ⏳
- Sistema de mineração ⏳
- Sistema de alquimia ⏳
- Sistema de economia ⏳
- Sistema de loja ⏳
- Sistema de trade ⏳
- Sistema de clans ⏳
- Leaderboard PvP global ✔️
- Leaderboard global geral ⏳
- Sistema de drops ✔️
- Sistema de bosses ✔️
- Sistema de fila de bosses ✔️
- Spawn automático de bosses ✔️
- Spawn automático de mobs ✔️
- PvP ranqueado ✔️
