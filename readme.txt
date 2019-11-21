https://github.com/MarceloGuerreiroUnicamp/tt304/

Instrução de compilação:
gcc read.c -lpthread -o read 
Instrução de execução : O programa read tem como entrada o número de Threads, os arquivos a serem lidos e nome do arquivo de saída. Exemplo:  
./read 16 a.dat b.dat c.dat d.dat e.dat saida.dat 
O programa mostrará o tempo total de execução da ordenação dos vetores e salvará em um arquivo texto chamado threads_[num_thread].dat. E salvará o arquivo de saída com as linhas de cada arquivo ordenadas. 
