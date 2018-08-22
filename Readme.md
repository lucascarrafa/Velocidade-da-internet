# Enviando por email a velocidade da internet

## Instalando o speedtest
Speedtest-cli é um pequeno aplicativo de linha de comando destinado a verificar a velocidade da internet via Terminal em várias distribuições Linux.
O programa é uma boa ferramenta porque interage com o popular site Speedtest.net e é especialmente útil para quem não tem acesso a um navegador no sistema operacional (servidores, por exemplo), além de permitir uma medição mais precisa.
Para instalr é bem simples, bastar executar os seguintes comandos no terminal:
```
$ sudo apt-get update
$ sudo apt-get install speedtest-cli
```

## O código
O código foi desenvolvido para quem deseja monitorar a conexão da internet de um lugar distante. O algoritmo fica em um loop contendo um intervalo de tempo para que um novo email seja enviado com a informação da velocidade naquele instante. 