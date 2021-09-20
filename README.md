# Animação das Bandas de Bollinger

Em um jupyter notebook, o algoritmo de bollinger bands é instanciado para uma lista de preços com o passo de 5 minutos. É plotado um gráfico com informações como Buy, Sell, Hold e um gif é feito com base nos gráficos plotados.

![](animation.gif)

### Execução do Server

O intuito do projeto é simular uma comunicação entre um server e um cliente, através de um socket criado localmente o arquivo main.c (server) se comunica com o main.py (cliente). Para executar o server compile com o gcc no terminal, na pasta do repositório:

```
$ gcc -Wall -pedantic -std=gnu99 -Og -o main main.c
```
Após isso, execute o seguinte comando para inicializar o server:

```
$ ./main
```

### Execução do Cliente

Uma vez que o server está sendo executado no terminal, abra o jupyter notebook e execute todas as células. A execução da célula irá baixar 801 plots de gráficos em formato png, para transformá-los em um GIF utiliza-se um conversor online: https://ezgif.com/apng-to-gif
