# 04. Faça mudanças

> Revise edições e crie uma transação de commit.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)

---

## Comandos desta seção (6)

### 1. `git status`

```bash
git status
```

**O que faz:**

Serve para ver o status atual do repositorio, mostrando branch atual, modificaçoes, arquivos novos etc..

**Quando usar / observação:**

Usar como garantia de estar no lugar certo, verificar se há algum processo pendente etc...

---

### 2. `git diff`

```bash
git diff
```

**O que faz:**

Mostra o que foi alterado nos arquvios, fazendo uma comparação.

**Quando usar / observação:**

Recomendado usar antes de fazer um commit, para conferir o que foi modificado

---

### 3. `git add [arquivo]`

```bash
git add [arquivo]
```

**O que faz:**

Coloca o arquivo selecionado na area de preparação para o commit, somente o arquivo selecionado

**Quando usar / observação:**

Quando alterar somente um arquivo, ou se quiser ir adicionando um arquivo modificado por vez

---

### 4. `git diff --staged`

```bash
git diff --staged
```

**O que faz:**

Faz a comparação de arquivos que ja foram modificados e estão aguardando o commit

**Quando usar / observação:**

Antes de fazer commit por garantia de salvar as alterações corretas

---

### 5. `git reset [arquivo]`

```bash
git reset [arquivo]
```

**O que faz:**

Retira o ariquivo do staging, desfaz o git add do arquivo

**Quando usar / observação:**

Quando fez git add em algum arquivo errado/engano

---

### 6. `git commit -m "[mensagem descritiva]"`

```bash
git commit -m "[mensagem descritiva]"
```

**O que faz:**

Serve para salvar no Git as alterações feitas, e em seguida uma mensagem sobre a alteração

**Quando usar / observação:**

Depois de dar git add e estiver pronto

---

## Checklist deste arquivo

- [x] 1. `git status`
- [x] 2. `git diff`
- [x] 3. `git add [arquivo]`
- [x] 4. `git diff --staged`
- [x] 5. `git reset [arquivo]`
- [x] 6. `git commit -m "[mensagem descritiva]"`

---

[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)
