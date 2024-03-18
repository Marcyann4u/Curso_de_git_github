# Aula 4

Baixa as atualizações do repositório remoto mas sem fundir com o que já existe localmente.

```
git fetch origin main
```

Verificar as diferenças entre o repositório local com o remoto

```
git diff nome_branch_local nome_branch_remota
```

Fundir a branch remota após usar o fetch

```
git merge origin/main
```

Clonar branch específica

```
git clone url_repositório --branch nome_branch
```
