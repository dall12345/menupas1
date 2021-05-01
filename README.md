# menupas1

Program MENU;
VAR
opcao:integer;
x:string;
y:string;
BEGIN
X:='[OLA UUARIO {DIGITE SEU NIK}]';
textbackground(5);
CLRSCR;
textcolor(7);
writeln(X);
READLN(X);
WRITELN('                         [OPCAO] {1}');
WRITELN('                         [OPCAO] {2}');
WRITELN('                         [OPCAO] {3}');
WRITELN('                         [OPCAO] {4}');
WRITELN('                         [OPCAO] {5}  ');
WRITELN('                         [OPCAO ]{6} [SENHA E OUTRAS INFORMACOES]');
WRITELN('                         [OPCAO] {7}  ');
WRITELN('');
WRITELN('');
WRITELN(X,'........[DIGITE UMA OPCAO]');
READLN(OPCAO);
CASE OPCAO OF
1:WRITELN('[ABRA FOX DIGITE FOX.LNK]');
2:WRITELN('[ABRA FILE DIGITE FILE]');
3:WRITELN('[ABRA IDLE DIGITE IDE.LNK]');
4:WRITELN('[ABRA NOT DIGITE NOT]');
5:WRITELN('[ABRA DEVC++ DIGITE DEVCPP.LNK]');
6:WRITELN('[PARA ACESSAR SEU NIK [darklinux] ,  E SUA SENHA [bucetuda12345678]  , SITE [https://www.flyordie.com/jogo/xadrez.html]');
7:WRITELN('[ABRA CHESSPAS DIGITE CHESSPAS]');
END;
END.

