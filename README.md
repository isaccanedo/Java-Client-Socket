# Java-Client-Socket
:dog: # Exemplo para executar o soquete do cliente em um terminal ou prompt de comando do Windows

### Servidor
Running Server: Host=192.168.1.5 Port=56439

### Para executar

java -cp server.jar br.com.isaccanedo.server.MyClientSocket 192.168.1.5 56439

Por exemplo, o Client é iniciado usando:
java -cp server.jar br.com.isaccanedo.server.MyClientSocket 192.168.1.5 56439.
É necessário passar 02 parâmetros: Endereço IP e a Porta. Os 02 argumentos de entrada que são acessados no método principal com args [0]. Se você não passar esses argumentos, a matriz args [] ficará vazia e você obterá a ArrayIndexOutOfBoundsException ao tentar ler a partir dela.

Link para o Server Socket: https://github.com/isaccanedo/Java-Server-Socket

