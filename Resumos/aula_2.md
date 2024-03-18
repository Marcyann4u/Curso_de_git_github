# 📖 Aula 2

Reestaurando arquivos apagados ou modificados para a forma original

```
git restore nome_arquivo.txt
```

Ver histórico de commits

```
git log
q
```

Mudar a mensagem do último commit

```
 git commit --amend -m "nova mensagem"
```

Desfazer commit 

```
git reset --soft hash_do_commit
```

Desfazer commit e retorna ao estado anterior

```
git reset --mixed hash_do_commit
```

Desfazer commit e apagar tudo que foi alterado

```
git reset --hard hash_do_commit
```