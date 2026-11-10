# Portfólio — Brandon Magalhães

Site pessoal em **React** com tema claro e escuro, animações e formulário de contato. Reúne apresentação, experiência profissional, formação, stack e projetos em uma página navegável.

## Stack

- **React 18** (Create React App)
- **styled-components** para tema e estilos
- **MUI** para ícones
- **react-router-dom** para a rota de detalhes do projeto
- **typewriter-effect** na seção inicial
- **EmailJS** no formulário de contato

## Seções

`HeroSection` · `Skills` · `Experience` · `Education` · `Projects` · `ProjectDetails` · `Contact` · `Footer`

## Como rodar

```bash
npm install
npm start
```

Abre em http://localhost:3000.

```bash
npm run build
```

Gera a versão de produção em `build/`.

## Formulário de contato

Usa EmailJS: configure o service ID, template ID e a chave pública no código antes de publicar. Não há backend próprio.

## Status

Projeto de portfólio mantido como peça de vitrine. Está pronto para deploy estático em Vercel, Netlify ou GitHub Pages.
