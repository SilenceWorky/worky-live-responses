# 🎮 RPG Marbion — Comandos do Chat

Sistema RPG persistente da live de **SilenceWorky**.

---

# 🌍 Perfil

## `!raça`
Sorteia sua raça permanente.

```txt
!raça
```

## `!elemento`
Desperta seus elementos. Pode vir 1 ou 2 elementos.

```txt
!elemento
```

## `!pinfo`
Mostra perfil completo.

```txt
!pinfo
```

Mostra:
- raça
- elementos
- tag equipada
- nível
- XP
- level elemental

---

# 🏷️ Tags

## `!tag`
Mostra sua tag equipada.

```txt
!tag
```

## `!tags`
Mostra suas tags desbloqueadas.

```txt
!tags
```

## `!settag NOME`
Equipa uma tag já desbloqueada.

```txt
!settag Filho das Chamas
```

---

# 📚 Lore

## `!infraca NOME`
Mostra informações sobre uma raça.

```txt
!infraca Tritão
```

## `!infelem NOME`
Mostra informações sobre um elemento.

```txt
!infelem Gravidade
```

---

# ⚔️ Progressão

## `!checkin`
Ganha XP por presença.

Cooldown: **15 minutos**

```txt
!checkin
```

## `!xpchest`
Abre um baú de XP.

Pode dar:
- XP geral
- XP elemental

Cooldown: **12 horas**

```txt
!xpchest
```

## `!daily`
Coleta recompensa diária.

Cooldown: **24 horas**

```txt
!daily
```

---

# 🔥 Sistema Elemental

Cada elemento evolui até **Lv.10**.

| Marco | Recompensa |
|---|---|
| Elemento Lv.5 | desbloqueia tag elemental |
| Elemento Lv.10 | direito a pedir novo elemento |

---

# 👹 Mobs

## `!vermob`
Mostra o mob ativo sem spawnar outro.

```txt
!vermob
```

## `!combate`
Ataca o mob ativo.

```txt
!combate
```

## `!mob`
Força spawn manual de mob.

Disponível apenas para SilenceWorky.

```txt
!mob
```

## `!mobon`
Ativa spawn automático de mobs.

Disponível apenas para SilenceWorky.

```txt
!mobon
```

## `!moboff`
Desativa spawn automático de mobs.

Disponível apenas para SilenceWorky.

```txt
!moboff
```

---

# ⚔️ PvP

## `!duelo USUARIO`
Desafia outro usuário para um duelo.

```txt
!duelo Worky
```

## `!aceito`
Aceita um duelo recebido.

```txt
!aceito
```

## `!recuso`
Recusa um duelo recebido.

```txt
!recuso
```

## `!responder PALAVRA`
Responde a palavra rápida do duelo.

Quem acertar primeiro ganha vantagem.

```txt
!responder caos
```

## `!pvp`
Mostra seu histórico PvP.

Mostra:
- rank
- RP
- vitórias
- derrotas
- duelos
- winrate
- aceitos
- recusados
- streak
- recorde de streak

```txt
!pvp
```

## `!toprank`
Mostra o Top 5 PvP.

```txt
!toprank
```

## `!rankuser USUARIO`
Mostra a posição de um usuário no ranking PvP.

```txt
!rankuser Worky
```

---

# 🏆 Ranks PvP

| Rank | RP necessário |
|---|---:|
| Iniciante | 0 |
| Bronze | 100 |
| Prata | 250 |
| Ouro | 500 |
| Diamante | 900 |
| Mestre | 1400 |
| Prodígio | 2000 |

Vitória: **+25 RP**  
Derrota: **-15 RP**  
Streak pode dar bônus extra.

---

# 🔄 Elementos

## `!reroll`
Rerolla seus elementos.

Disponível apenas para subs.

Cooldown: **24 horas**

```txt
!reroll
```

---

# 🛠️ Comandos Administrativos

Disponíveis apenas para SilenceWorky.

## `!setlvl @usuario NÍVEL`
Define o nível geral de um usuário.

```txt
!setlvl @Worky 50
```

## `!setlvlelem usuario Elemento NÍVEL`
Define o nível elemental de um usuário.

```txt
!setlvlelem SilenceWorky Agua 10
```

## `!resetelemento @usuario`
Remove elementos e progresso elemental.

```txt
!resetelemento @Worky
```

## `!resetraca @usuario`
Apaga completamente o perfil.

```txt
!resetraca @Worky
```

## `!synclevel`
Sincroniza nível com base no XP.

```txt
!synclevel
```

## `!admsettag @usuario NOME`
Define manualmente a tag de alguém.

```txt
!admsettag @Worky Filho da Singularidade
```

## `!addtag NOME`
Cria uma tag customizada.

```txt
!addtag Caçador de Corrompidos
```

## `!removetag NOME`
Remove uma tag customizada.

```txt
!removetag Caçador de Corrompidos
```

---

# 🌌 Sobre

O RPG é persistente.

Seus dados ficam salvos entre lives:
- raça
- elementos
- XP
- nível
- tags
- PvP
- ranking
- progresso elemental

Boa sorte em Marbion.
