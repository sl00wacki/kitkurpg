## Ruch:

### player_speed
- Opis: Szybkość gracza.
- Wartość domyślna: `5`.

### enemy_speed
- Opis: Szybkość przeciwnika
- Wartość domyślna: zalezy od rasy przeciwnika
  - Dobberman: 3
  - Owczarek: 4
  - York: 4.75

### image_speed
- Opis: Szybkość przemieszczania się sprite'a.
- Notka: Przy zapisaniu, wyznacz to jako `player_speed / [ilość klatek w gifie]`.

### spr_player[direction]
- Opis: Sprite do kierunku przemieszczania się postaci.

### image_index
- Opis: Ustawienie klatki dla sprite'a.

### sprite_index
- Opis: Ustawienie sprite'a na postać bez ruchu (`player_idle`).




## Serduszka:

###player_currentHp
- Opis: aktualny stan serduszek gracza.
  
### player_MaxHp
- Opis: maksymalna wartość serduszek gracza
- Wartość domyślna: `3`.

### enemy_[name]_MaxHp
- Opis: maksymalna wartość serduszek przeciwnika
- Wartość domyślna:
   - Dobberman: 2;
   - Owczarek: 3;
   - York = 5;
### enemy_[name]_currentHp
-Opis: aktualna wartość serduszek przeciwnika

