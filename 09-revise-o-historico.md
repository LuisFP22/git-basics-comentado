# 09. Revise o histórico

> Navegue e inspecione a evolução dos arquivos do projeto.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Salve fragmentos](08-salve-fragmentos.md) · [Índice](../README.md) · [Desfaça commits ➡](10-desfaca-commits.md)

---

## Comandos desta seção (4)

### 1. `git log`

```bash
git log
```

**O que faz:**

Mostra o histórico de commits do repositório

**Quando usar / observação:**

Quando quiser consultar quais commits foram feitos, suas mensagens, autores e datas

---

### 2. `git log --follow [arquivo]`

```bash
git log --follow [arquivo]
```

**O que faz:**

Mostra o histórico de commits, incluindo o histórico anterior caso o arquivo tenha sido renomeado ou movido

**Quando usar / observação:**

Quando quiser descobrir todas as alterações feitas em um arquivo ao longo do tempo

---

### 3. `git diff [primeiro-branch]...[segundo-branch]`

```bash
git diff [primeiro-branch]...[segundo-branch]
```

**O que faz:**

Mostra as diferenças entre duas branches, permitindo ver o que mudou entre elas

**Quando usar / observação:**

Quando quiser comparar o conteúdo de duas branches

---

### 4. `git show [commit]`

```bash
git show [commit]
```

**O que faz:**

Mostra os detalhes de um commit específico

**Quando usar / observação:**

Mostra os detalhes de um commit específico

---

## Checklist deste arquivo

- [x] 1. `git log`
- [x] 2. `git log --follow [arquivo]`
- [x] 3. `git diff [primeiro-branch]...[segundo-branch]`
- [x] 4. `git show [commit]`

---

[⬅ Salve fragmentos](08-salve-fragmentos.md) · [Índice](../README.md) · [Desfaça commits ➡](10-desfaca-commits.md)
