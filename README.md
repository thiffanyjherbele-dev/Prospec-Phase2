# Prospec Phase2

Site de inteligência de mercado para prospecção B2B.

## Como publicar na Vercel

### 1. Faça upload dos arquivos para o GitHub
Suba os 3 arquivos deste projeto para o repositório `Prospec-Phase2`:
- `index.html`
- `vercel.json`
- `api/analyze.js`

### 2. Conecte o repositório na Vercel
- Acesse: https://vercel.com
- Clique em **Add New → Project**
- Selecione o repositório `Prospec-Phase2`
- Clique em **Deploy**

### 3. Configure a chave de API
- No painel da Vercel, vá em **Settings → Environment Variables**
- Adicione:
  - **Name:** `ANTHROPIC_API_KEY`
  - **Value:** sua chave (começa com `sk-ant-...`)
- Clique em **Save**
- Vá em **Deployments** e clique em **Redeploy**

### 4. Pronto!
Seu site estará disponível em `https://prospec-phase2.vercel.app` (ou similar).
Compartilhe o link com Mateus, Gustavo e toda a equipe.

## Obtendo sua chave de API
- Acesse: https://console.anthropic.com
- Menu: **API Keys → Create Key**
- Copie a chave e cole na Vercel conforme passo 3
