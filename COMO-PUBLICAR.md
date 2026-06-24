# 📖 Como publicar o grimório (perfil do GitHub)

Guia rápido pra deixar teu perfil **@LaioBomfimDev** com cara de bruxo. 🧙‍♂️

---

## 🪄 Passo 1 — Criar o repositório especial

O GitHub tem um truque: se você criar um repositório **com o mesmo nome do seu usuário**, o `README.md` dele vira a capa do seu perfil.

1. Vá em **https://github.com/new**
2. **Repository name:** `LaioBomfimDev` (idêntico ao seu usuário — o GitHub vai mostrar ✨ "you found a secret!")
3. Marque **Public**
4. Marque **Add a README file**
5. Clique em **Create repository**

---

## 🔮 Passo 2 — Subir os arquivos

Copie para o repositório:

- `README.md` ......................... a capa do perfil
- `.github/workflows/snake.yml` ....... a animação da serpente

### Opção A — pelo site (mais fácil)
1. No repositório, clique em **Add file → Upload files**
2. Arraste o `README.md`
3. Para o workflow: **Add file → Create new file**, digite o caminho
   `.github/workflows/snake.yml` e cole o conteúdo.
4. **Commit changes**

### Opção B — pelo terminal
```bash
git clone https://github.com/LaioBomfimDev/LaioBomfimDev.git
cd LaioBomfimDev
# copie README.md e a pasta .github para cá
git add .
git commit -m "🔮 Forjar grimório do Bruxo"
git push
```

---

## 🐍 Passo 3 — Ligar a serpente

1. No repositório, abra a aba **Actions**
2. Se aparecer um aviso, clique em **"I understand my workflows, enable them"**
3. Clique no workflow **"🐍 Gerar Serpente das Contribuições"** → **Run workflow**
4. Espere ~1 minuto. Isso cria a branch `output` com as imagens.
5. Pronto! A serpente vai aparecer no perfil. (Depois ela se atualiza sozinha a cada 12h.)

> Enquanto a Action não rodar, a imagem da serpente fica "quebrada" — é normal. 🩹

---

## ✏️ Passo 4 — Trocar os placeholders

Abra o `README.md` e procure por **`TROCAR`**. Edite estes links:

| O quê | Onde está | Coloque |
|------|-----------|---------|
| LinkedIn | `linkedin.com/in/seu-usuario` | seu LinkedIn |
| Instagram | `instagram.com/seu_usuario` | seu @ real |
| WhatsApp | `wa.me/5500000000000` | `55` + DDD + número |
| Site | `seu-site.com` | seu portfólio |
| E-mail | `neuroreabilitys@gmail.com` | já configurado ✅ |

> 💡 Os cards de **WhatsApp / Instagram / Site** já estão como template — é só ter a página e colar o link.

---

## 📜 Passo 5 — Mostrar o projeto em destaque

O card de **`sistema-acup`** só aparece se o repositório for **público**.
- Vá em `sistema-acup` → **Settings** → **General** → **Change visibility** → **Public**
- (Se preferir manter privado, me avise que troco por um card estático.)

---

## 🎨 Quer mudar as cores?

A paleta "magia negra roxa" usa estes tons (HEX):

| Cor | Uso |
|-----|-----|
| `10021F` | fundo (vazio arcano) |
| `2D0A4E` / `3C096C` | roxo escuro (badges) |
| `5A189A` / `7B2CBF` | roxo médio (bordas) |
| `9D4EDD` | roxo vivo (ícones) |
| `C77DFF` | roxo brilhante (destaque) |
| `E0AAFF` | lavanda (texto) |

É só trocar esses códigos no `README.md` que o visual inteiro muda junto. 🪄
