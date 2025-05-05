[README.md](https://github.com/user-attachments/files/20042953/README.md)#Lista de Arvores-Urbanas
Lista de espécies que são utilizadas na arborização, assim como as que podem vir a ser.

A planilha com os dados é a intitulada "arvores_urbanas.xlsm". 

Ao clicar em "arvores_urbanas.xlsm", baixe o arquivo clicando em "View raw" e visualize no Excel, Google Planilhas ou Libre Office.

Para trabalhar continuamente no projeto:
# 📊 Fluxo de Edição da Planilha `arvores_urbanas.xlsm` com Git

Este é o passo a passo recomendado para editar a planilha de forma segura usando Git, evitando conflitos e perdas de informações.

## ✅ 1. Antes de tudo: atualize seu repositório local

Abra o terminal na pasta do projeto e execute:

```bash
git pull origin main
```

Isso garante que você está com a **versão mais atual da planilha**.

---

## 📝 2. Edite a planilha normalmente

- Abra o arquivo `arvores_urbanas.xlsm` com o Excel.
- Faça suas edições.
- Salve o arquivo.

---

## ➕ 3. Adicione a nova versão ao Git

Após salvar a planilha, rode no terminal:

```bash
git add arvores_urbanas.xlsm
```

---

## 💬 4. Crie um commit com uma mensagem clara

```bash
git commit -m "Atualiza dados de espécies e corrige informações da aba X"
```

---

## 🚀 5. Envie as mudanças para o GitHub

```bash
git push origin main
```

---

## 🔁 Dica importante

Sempre repita o **passo 1** (`git pull`) antes de começar um novo dia de edição ou quando for abrir a planilha novamente.

---

## ⚠️ Em caso de conflito (erro ao dar `git pull`)

Se aparecer uma mensagem de **conflito**, significa que outra pessoa também editou o arquivo.

### ➤ Opções de resolução:

**a. Manter sua versão:**

```bash
git add arvores_urbanas.xlsm
git commit -m "Resolve conflito mantendo minha versão"
git push origin main
```

**b. Usar a versão do GitHub (descarta sua edição):**

```bash
git restore --theirs arvores_urbanas.xlsm
git add arvores_urbanas.xlsm
git commit -m "Resolve conflito usando versão remota"
git push origin main
```

---

Para dúvidas ou sugestões, entre em contato com a equipe do projeto.
oading README.md…]()
