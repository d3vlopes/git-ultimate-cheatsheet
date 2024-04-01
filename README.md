
![Content](https://github.com/d3vlopes/ultimate-git-cheetseat/assets/59663666/f9666bc5-49f7-476d-b176-507d5e349964)


- [Config](#config)
- [Log](#log)
- [Commit](#commit)
- [Branch](#branch)
- [Rebase](#rebase)
- [Tag](#tag)
- [Stash](#stash)
- [Revert](#revert)
- [Remote](#remote)
- [Bonus](#bonus)

## <a id="config"></a> Config

### Configura o nome de usuário
```
git config --global user.name "my-username"
```

### Configura o email de usuário
```
git config --global user.email "my-email"
```

### Retorna o nome de usuário configurado
```
git config user.name
```

### Lista todas as configurações do seu git
```
git config --list
```

## <a id="log"></a> Log

### Mostra todos os commits feitos.
```
git log
```

### Mostra os commits de uma forma simplificada
```
git log --oneline
```

### Mostra só os commits feitos pelo o autor informado
```
git log --author="nome"
```

### Ordena os commits por autor, mostrando o que cada um fez
```
git shortlog
```

### Mostra informações sobre um commit especifico
```
git show <hash>
```

### Retorna o head e outras informações sobre cada commit 
```
git reflog
```

## <a id="commit"></a> Commit

### Adiciona o arquivo em staged
```
git add <caminho-arquivo>
```

### Adiciona todos os arquivos em staged
```
git add .
```

### Cria um commit
```
git commit  -m "mensagem"
```

### Altera a mensagem do último commit
```
git commit --amend -m "nova mensagem"
```

### Sobrescreve o último commit, utilizando a mesma mensagem
```
git commit --amend --no-edit
```

## <a id="branch"></a> Branch

### Cria uma branch
```
git branch <nome-branch>
```

### Remove a branch
```
git branch -D <nome-branch>
```

### Renomeia uma branch
```
git branch -m <old_name> <new_name>
```

### Lista todas as branchs
```
git branch
```

### Faz checkout para uma branch
```
git checkout <nome-branch>
```

### Cria uma nova branch e faz checkout 
```
git checkout -b <minha-nova-brach>
```

## <a id="rebase"></a> Rebase

### Sincroniza uma branch com outra
```
git rebase <nome-branch>
```

### Continua o processo de rebase
```
git rebase --continue
```

### Inicializa o rebase interativo
```
git rebase -i <hash>
```

### Continua o processo de rebase
```
git rebase --continue
```

## <a id="tag"></a> Tag

### Cria uma tag
```
git tag <v1.0.0>
```

### Cria uma tag com mensagem
```
git tag -a <1.0.0> -m "mensagem"
```

### Remove tag local
```
git tag -d <v1.0.0>
```

### Remove tag do remote
```
git push --delete origin <tag_name>
```

### Faz checkout para o momento que a tag foi criada
```
git checkhout <tag>
```

## <a id="stash"></a> Stash

### Salva as alterações na memoria
```
git stash
```

### Lista todos os stash
```
git stash list
```

### Carrega o stash selecionado
```
git stash apply <ref>
```

### Carrega e remove o último stash
```
git stash pop
```

### Remove o stash com o ref informado
```
git stash drop <ref>
```

### Remove todos os stashs salvos
```
git stash clear
```

## <a id="revert"></a> Revert

### Salva as alterações na memoria
```
git stash
```
