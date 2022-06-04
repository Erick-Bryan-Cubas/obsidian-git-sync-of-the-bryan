É uma forma de inicializar e parar grupos na inicialização do sistema, tendo apenas um nível de inicialização por vez ativo 

Runlevel  |  Target 
----------|----------
0         | poweroff.target
1         | rescue.target
2, 3, 4   | multi-user.target
5         | graphical.target
6         | reboot.target


[[Runlevel 0]] - Desligamento do sistema;
[[Runlevel 1]] - Modo monousuário ativando a recuperação
[[Runlevel 2]] , [[Runlevel 3]] [[Runlevel 4]] - Modo padrão, comumente utilizado. Níveis sem GUI, pois a GUI encontra-se no [[Runlevel 5]];
[[Runlevel 6]] - runlevel em que a máquina será reiniciada. 