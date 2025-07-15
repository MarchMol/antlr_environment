Commands in wsl:
```
docker build --rm . -t <name>
```

En la carpeta /program yace el driver y la gramatica g4, con este comando podemos acceder a ella desde el ambiente en docker y correr los comandos de antlr
```
docker run --rm -ti -v "$(pwd)/program":/program <name>
```