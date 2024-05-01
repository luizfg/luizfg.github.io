<a id="ancora"></a>
![cs2](imagens/cs2-logo.png)

# Config
- [Usar durante o jogo](#ingame)
- [Para treino](#treino)

<a id="ingame"></a>
## Config utilizada para jogo
[Topo](#ancora)
```
// Para fazer jumpthrow
alias "+boing" "+jump"
alias "+ding" "-attack; -attack2"
alias "+dong" "-jump"
bind MOUSE4 "+boing; +ding; +dong"

// run e jumpthrow
alias "+wthrow" "+forward;+jump;"
alias "-wthrow" "-jump;-forward"
bind "x" "+wthrow; +ja"

// Pular no scroll pra cima: 
bind "MWHEELUP" "+jump"

// Pular no scroll pra baixo: 
bind "MWHEELDOWN" "+jump"

// remover as informacoes de build que ficam no canto inferior direito
r_show_build_info 0
```

<a id="treino"></a>
## Config de treino
[Topo](#ancora)
```
// Habilitar sv_cheats
sv_cheats 1

// Para fazer jumpthrow
alias "+boing" "+jump"
alias "+ding" "-attack; -attack2"
alias "+dong" "-jump"
bind MOUSE4 "+boing; +ding; +dong"

// Para habilitar/desabilitar noclip (poder voar pelo mapa) com a mesma tecla
alias "+clipon" "noclip true;bind n +clipoff"
alias "+clipoff" "noclip false;bind n +clipon"
bind "n" "noclip"

// run e jumpthrow
alias "+wthrow" "+forward;+jump;"
alias "-wthrow" "-jump;-forward"
bind "x" "+wthrow; +ja"

// Lançar novamente a última granada
bind "l" "sv_rethrow_last_grenade"

// Acelerar o tempo para a smoke terminar mais rápido
bind "j" "incrementvar host_timescale 1 11 10"

// comprar qualquer coisa em qualquer lugar do mapa
mp_buy_anywhere 1

// Pular no scroll pra cima: 
bind "MWHEELUP" "+jump"

// Pular no scroll pra baixo: 
bind "MWHEELDOWN" "+jump"

// para não morrer na molotov 
sv_regeneration_force_on true
```


