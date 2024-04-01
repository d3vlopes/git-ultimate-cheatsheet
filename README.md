
![Content](https://github.com/d3vlopes/ultimate-git-cheetseat/assets/59663666/f9666bc5-49f7-476d-b176-507d5e349964)


- [Config](#config)
- [Log](#log)
- [Commit](#commit)

## <a id="config"></a> Config

### Configura o nome de usuário
```
$ git config --global user.name "my-username"
```

### Configura o email de usuário
```
$ git config --global user.email "my-email"
```

### Retorna o nome de usuário configurado
```
$ git config user.name
```

### Lista todas as configurações do seu git
```
$ git config --list
```

## <a id="log"></a> Log

### Mostra todos os commits feitos.
```
$ git log
```

### Mostra os commits de uma forma simplificada
```
$ git log --oneline
```

### Mostra só os commits feitos pelo o autor informado
```
$ git log --author="nome"
```

### Ordena os commits por autor, mostrando o que cada um fez
```
$ git shortlog
```

### Mostra informações sobre um commit especifico
```
$ git show <hash>
```

### Retorna o head e outras informações sobre cada commit 
```
$ git reflog
```

## <a id="commit"></a> Commit

### Configura o nome de usuário
```
$ git config --global user.name "my-username"
```

