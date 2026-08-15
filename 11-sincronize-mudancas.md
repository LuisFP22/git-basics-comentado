# 11. Sincronize mudanças

> Registre um repositório remoto e troque o histórico de versão.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)

---

## Comandos desta seção (4)

### 1. `git fetch [nome-remoto]`

```bash
git fetch [nome-remoto]
```

**O que faz:**

Busca as atualizações do repositório remoto e atualiza as locais, sem alterar os arquivos atuais

**Quando usar / observação:**

Quando quiser verificar se existem novos commits no GitHub

---

### 2. `git merge [nome-remoto]/[branch]`

```bash
git merge [nome-remoto]/[branch]
```

**O que faz:**

Junta na sua branch atual as alterações de uma branch remota

**Quando usar / observação:**

Quando quiser incorporar alterações que estão no repositório remoto à sua branch local

---

### 3. `git push [alias] [branch]`

```bash
git push [alias] [branch]
```

**O que faz:**

Envia os commits da sua branch local para o repositório remoto

**Quando usar / observação:**

Quando quiser publicar suas alterações no GitHub ou atualizar a branch remota
---

### 4. `git pull`

```bash
git pull
```

**O que faz:**

Baixa as alterações do repositório remoto e já integra essas alterações na sua branch atual

**Quando usar / observação:**

Quando quiser atualizar sua branch local

---

## Checklist deste arquivo

- [x] 1. `git fetch [nome-remoto]`
- [x] 2. `git merge [nome-remoto]/[branch]`
- [x] 3. `git push [alias] [branch]`
- [x] 4. `git pull`

---

[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)
