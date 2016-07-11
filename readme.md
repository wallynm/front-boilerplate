# Intro
Todos os arquivos compilados encontram se dentro da pasta public e são acessíveis aos arquivos HTML, a pasta build são agrupados todos arquivos source para edição, arquivos JS, LESS e gulp tasks para automatização de tarefas.

### DEMO - [http://wallynm.github.io/projects/meliuz/](http://wallynm.github.io/projects/meliuz/)

---


###Plugins e frameworks utilizados
- jQuery - Para aplicação de algumas animações e controle do DOM
- Gulp - Compilação de arquivos LESS, concatenação e minificação


### Build
É necessário ter o NodeJS instalado e o gerenciador de depenências bower instalado globalmente, caso não possua execute o seguitne comando no console:
```
$ bower install -g
```

Uma vez baixado o repositório execute o comando a seguir no console/terminal dentro da pasta "build"
```
$ npm install
```

- Para então compilar os arquivos e executar as tarefas do gulp e execute o seguinte comando dentro da pasta "build":
``` 
$ gulp
```

Ou caso deseje, também é possível executar qualquer um destes comandos de maneira isolada:
``` 
$ gulp less;
$ gulp copy-images;
$ gulp scripts;
```

Para testar o basta acessar o arquivo index.html
