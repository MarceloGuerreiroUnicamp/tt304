https://github.com/MarceloGuerreiroUnicamp/tt304/

Instru��o de compila��o:
gcc read.c -lpthread -o read 
Instru��o de execu��o : O programa read tem como entrada o n�mero de Threads, os arquivos a serem lidos e nome do arquivo de sa�da. Exemplo:  
./read 16 a.dat b.dat c.dat d.dat e.dat saida.dat 
O programa mostrar� o tempo total de execu��o da ordena��o dos vetores e salvar� em um arquivo texto chamado threads_[num_thread].dat. E salvar� o arquivo de sa�da com as linhas de cada arquivo ordenadas. 
