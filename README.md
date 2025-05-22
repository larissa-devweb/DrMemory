# DrMemory
Explicando como usar:

* Crie um executavel do meu projeto:
   ---Se windows:
   1. vazamento.c
   2. Abre o terminal e cd C:\Users\SeuUsuario\Desktop
   3. gcc vazamento.c -o vazamento.exe
   4.drmemory -- vazamento.exe

  ---Linux:
  1.gcc vazamento.c -o vazamento
  ./vazamento
  2.valgrind --leak-check=full ./vazamento



