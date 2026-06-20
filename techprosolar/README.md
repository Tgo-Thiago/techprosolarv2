# Techpro Solar — Landing Page

Site institucional / landing page de vendas da **Techpro Solar** (CNPJ: 44.150.790/0001-67).

## Estrutura

```
techprosolar/
├── index.html          ← página única (todo CSS/JS embutido)
├── Property_1_1.png    ← logo horizontal colorida
├── Frame_9.png         ← ícone da marca (verde escuro)
├── Logo_Redondo_Sem_fundo_Techpro.png  ← logo redonda
├── vercel.json         ← configuração de deploy Vercel
└── README.md
```

## Deploy — Passo a Passo

### 1. GitHub

```bash
# Na pasta do projeto:
git init
git add .
git commit -m "feat: landing page Techpro Solar v1"

# Crie um repositório no GitHub (ex: techprosolar-site)
git remote add origin https://github.com/SEU_USUARIO/techprosolar-site.git
git branch -M main
git push -u origin main
```

### 2. Vercel

1. Acesse [vercel.com](https://vercel.com) e faça login com GitHub
2. Clique em **"Add New Project"**
3. Selecione o repositório `techprosolar-site`
4. Framework Preset: **Other** (static site)
5. Root Directory: `/` (deixe padrão)
6. Clique em **Deploy**

O Vercel detectará o `vercel.json` e fará o deploy automático.

### 3. Domínio personalizado (techprosolar.com.br)

No painel da Vercel:
1. Vá em **Settings → Domains**
2. Adicione `techprosolar.com.br` e `www.techprosolar.com.br`
3. A Vercel mostrará os registros DNS a configurar

No **Registro.br**:
1. Acesse seu painel em registro.br
2. Clique no domínio `techprosolar.com.br`
3. Vá em **"Configurar DNS"**
4. Adicione os registros que a Vercel indicar:
   - Registro `A` apontando para o IP da Vercel
   - Registro `CNAME` para `www` apontando para `cname.vercel-dns.com`
5. Aguarde propagação (5–30 minutos normalmente)

## Personalização

- **Cores:** edite as variáveis CSS em `:root` no `<style>` do `index.html`
- **Conteúdo:** textos e dados estão diretamente no HTML, bem comentados
- **WhatsApp:** busque `5519992746549` para alterar o número se necessário
- **E-mail:** busque `contato@techprosolar.com.br`

## Contato

- 📞 (19) 99274-6549
- ✉️ contato@techprosolar.com.br
- 🌐 techprosolar.com.br
