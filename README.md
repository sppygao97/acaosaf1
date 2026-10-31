# Ação SAF — Gestão de Atletas

Site estático (HTML/CSS/JS puro) com login por CPF e cadastro de atletas por categoria (Profissional, Sub-20, Sub-17).

## Acesso inicial
- CPF: 063.660.843-35 (Administrador)
- Senha inicial: admin123

## Publicar no GitHub
```bash
git init
git add .
git commit -m "Primeira versão do site Ação SAF"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/acao-saf.git
git push -u origin main
```

## Hospedar na Vercel
1. Acesse vercel.com e entre com sua conta do GitHub.
2. Clique em "Add New… > Project" e importe o repositório `acao-saf`.
3. Framework Preset: "Other". Deixe Build Command e Output Directory em branco.
4. Clique em "Deploy".

## Observação
Os dados ficam no localStorage do navegador (não são compartilhados entre dispositivos).
