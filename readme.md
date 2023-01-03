## Wordpress latest no docker

> Basta rodar o comando no arquivo docker-compose.yaml, dentro do mesmo diretorio

`docker-compose up`

*Obs:*

- O comando tem que ser executado dentro do diretório do arquivo docker-compose.yaml
- O nome do arquivo **"docker-compose.yaml"** tem que ser esse mesmo, nao pode mudar.
- Se estiver rodando no WSL no windows, é melhor criar o volume dentro do ambiente Linux e mapear o projeto de lá, se mapear numa pasta dentro do windows, pode apresentar lentidao, pois o container terá que usar o wsl para acessar as pastas do windows que utiliza o protocolo 9P para acessa-lo e assim ficar lento o I/O dos arquivos.

[Protocolo 9P WSL - W10](https://devblogs.microsoft.com/commandline/whats-new-for-wsl-in-windows-10-version-1903/ "WSL - 9Protocol on W10").

(a principio é isso 😎 )
