# apacmovils

## Variables onCreate
contador -> contador para bloquejar el intent de login <br>
login -> link al botó de login <br>
contafallos -> link al text de numero de fallos <br>
salidafallo -> variable per a conviar el text de contafallos <br>
<br>
## Funcio comprobacio()
Comproba si el input del usuari i contrasenya son valids <br>
<br>
## Variables funcio comprobacio()
intento -> boolean para el return<br>
usuarioval -> string del usuario valido<br>
passval -> string de la contrasenya valida<br>
usuario -> link al input del usuario<br>
contrasenya -> link al input de la contrasenya<br>
<br>
## Canvis en manifest
Sols se ha insertat una linea<br>
android:configChanges="keyboardHidden|orientation|screenSize"<br>
que funciona para que mantenisca el stat en la rotacio del dispositiu<br>
<br>
## Traduccions 
El idioma per defecte es ingles i se ha posat el castella i catala
