Criação de ficheiro Excel

Este script nasceu da necessidade de criação de um ficheiro Excel através da importação de dados de uma tabela SQL. 
Algumas notas importantes sobre o ficheiro a ser criado: 
  * o ficheiro tem de conter um título no topo
  * a versão e data do documento deve constar no final
  * não é desejável que o cabeçalho dos dados tenha borders

O script mostra a criação do documento nas seguintes opções:
* Criação de ficheiro Excel v1 com utilização da função "to_excel"
* Criação de ficheiro Excel v2 com utilização da classe "ExcelWriter"

Por fim, é explicado o uso da Transposta em Pandas para remoção dos borders.

O output final tem o seguinte aspecto:

![image](https://github.com/JorgeGomes72/AdvancedExcelCreation/assets/57633568/9f68b5d3-83ca-48ca-8d3d-8907fb93effa)



