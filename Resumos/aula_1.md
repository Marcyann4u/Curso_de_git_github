# 📖 Aula 1 

### Comandos básicos do terminal 

Criar uma nova pasta
```
mkdir nome_da_pasta
```

Entrar em uma pasta

```
cd NOME_DA_PASTA
```
Sair de uma pasta
```
cd ..
```

Verificar arquivos pastas do diretório selecionado

```
dir
```

Criar novo arquivo
```
echo nome_arquivo.txt
```

Mover arquivos
```
mv nome_arquivo.txt nome_destino
```

Limpar o terminal
```
ctrl + l
```

### Comandos básicos do Git

Tornar pasta local em repositório do github
```
git init
```

Conectar repositório local com o remoto
```
git remote add origin url_do_repositório
```

Ver status/mudanças que ocorreram no repositório
```
git status
```

Clonar repositório remoto
```
git clone url_do_repositório
```

Adicionar alterações como "prontas para envio remoto"
```
git add nome_do_arquivo
```
Adicionar todas as alterações como "prontas para envio remoto"
```
git add .
```


Criar um commit/registrar alteração para envio remoto
```
git commit -m "nome da alteração"
```

Sincronizar repositório local com remoto
```
git pull origin nome_da_branch
```

Enviar atualizações do repositório local para o remoto
```
git push origin nome_da_branch
```
