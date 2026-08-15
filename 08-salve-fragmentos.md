# 08. Salve fragmentos

> Arquive e restaure mudanças incompletas.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Suprima o monitoramento](07-suprima-o-monitoramento.md) · [Índice](../README.md) · [Revise o histórico ➡](09-revise-o-historico.md)

---

## Comandos desta seção (4)

### 1. `git stash`

```bash
git stash
```

**O que faz:**

Guarda temporariamente as alterações que voce fez

**Quando usar / observação:**

Quando precisar trocar de branch ou realizar outra tarefa sem fazer commit das alterações atuais.

---

### 2. `git stash pop`

```bash
git stash pop
```

**O que faz:**

Recupera as alterações que foram guardadas anteriormente com git stash.

**Quando usar / observação:**

Quando quiser voltar a trabalhar nas alterações que estavam temporariamente guardadas

---

### 3. `git stash list`

```bash
git stash list
```

**O que faz:**

Mostra a lista de todas as alterações que estão guardadas temporariamente pelo git stash

**Quando usar / observação:**

Quando quiser verificar quais alterações estão armazenadas antes de recuperá-las

---

### 4. `git stash drop`

```bash
git stash drop
```

**O que faz:**

Remove um stash específico da lista de alterações guardadas.

**Quando usar / observação:**

Quando você não precisa mais de uma alteração que foi guardada com git stash.

---

## Checklist deste arquivo

- [x] 1. `git stash`
- [x] 2. `git stash pop`
- [x] 3. `git stash list`
- [x] 4. `git stash drop`

---

[⬅ Suprima o monitoramento](07-suprima-o-monitoramento.md) · [Índice](../README.md) · [Revise o histórico ➡](09-revise-o-historico.md)
