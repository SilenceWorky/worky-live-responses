# 🎮 RPG Marbion — Comandos do Chat

Sistema RPG persistente da live de **SilenceWorky**.

---

# 🌍 Perfil

## `!raça`
Sorteia e salva sua raça.

## `!elemento`
Desperta seus elementos/mentalidades.

## `!pinfo`
Mostra perfil completo: raça, elementos, tag, nível, XP e nível elemental.

---

# 🏷️ Tags

## `!tag`
Mostra sua tag equipada.

## `!tags`
Mostra suas tags desbloqueadas.

## `!settag NOME`
Equipa uma tag desbloqueada.

Exemplo:
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

Cooldown: **15 min**

## `!xpchest`
Abre baú de XP.

Pode dar:
- XP geral
- XP elemental

Cooldown: **12h**

## `!daily`
Coleta recompensa diária.

Cooldown: **24h**

---

# 🔥 Sistema Elemental

Cada elemento pode evoluir até **Lv.10**.

| Marco | Recompensa |
|---|---|
| Elemento Lv.5 | desbloqueia tag elemental |
| Elemento Lv.10 | direito a pedir novo elemento |

---

# 🔄 Elementos

## `!reroll`
Rerolla elementos.

Disponível apenas para subs.

Cooldown: **24h**

---

# 👹 Mobs

## `!vermob`
Mostra o mob ativo.

## `!combate`
Ataca o mob ativo.

## `!mob`
Força spawn de mob.  
Disponível apenas para SilenceWorky.

## `!mobon`
Ativa spawn automático de mobs.  
Disponível apenas para SilenceWorky.

## `!moboff`
Desativa spawn automático de mobs.  
Disponível apenas para SilenceWorky.

---

# ⚔️ PvP

## `!duelo usuario`
Desafia outro jogador para duelo.

```txt
!duelo Worky
```

## `!aceito`
Aceita um duelo recebido.

## `!recuso`
Recusa um duelo recebido.

## `!responder palavra`
Responde a palavra rápida do duelo.

Quem responder primeiro corretamente ganha vantagem.

```txt
!responder cristal
```

## `!pvp`
Mostra histórico PvP.

Mostra:
- rank
- RP
- vitórias
- derrotas
- winrate
- duelos aceitos
- duelos recusados
- streak atual
- maior streak

## `!toprank`
Mostra o Top 5 PvP.

## `!rankuser usuario`
Mostra a posição PvP de um usuário específico.

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

Vitória:
```txt
+25 RP
```

Derrota:
```txt
-15 RP
```

Bônus por streak:
- streak 3: +5 RP
- streak 5: +10 RP
- streak 10: +20 RP

---

# 🛠️ Comandos Administrativos

Disponíveis apenas para SilenceWorky.

## `!setlvl usuario NÍVEL`
Define nível geral.

```txt
!setlvl Worky 50
```

## `!setlvlelem usuario Elemento NÍVEL`
Define nível elemental.

```txt
!setlvlelem SilenceWorky Agua 10
```

## `!resetelemento usuario`
Remove elementos e progresso elemental.

```txt
!resetelemento Worky
```

## `!resetraca usuario`
Apaga completamente o perfil.

```txt
!resetraca Worky
```

## `!synclevel`
Sincroniza nível com XP atual.

## `!admsettag usuario NOME`
Define tag manualmente.

```txt
!admsettag Worky Filho da Singularidade
```

## `!addtag NOME`
Cria tag
