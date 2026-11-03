# Controle de alunos - Custódio Team

Sistema para acompanhar **mensalidades** e **graduações (cordas)** dos alunos, com **login** e dados guardados em banco de dados (Supabase).

> **Status:** v0.2. Acesso por e-mail e senha, dados por academia, bloqueio por teste vencido ou assinatura suspensa.

## Arquivos

- `index.html`: o aplicativo
- `config.js`: endereço e chave **publicável** do Supabase (a chave secreta nunca entra aqui)

## Como configurar

1. No Supabase, rode os scripts SQL (estrutura e segurança; depois criação da academia e do professor).
2. Em Authentication, desligue o cadastro aberto de novos usuários.
3. Cole a chave publicável (`sb_publishable_...`) no `config.js`.
4. Publique o projeto (Netlify, Vercel ou Cloudflare Pages ligados a este repositório).
5. No Supabase, em Authentication > URL Configuration, cadastre o endereço publicado como Site URL.

## Segurança

- As regras do banco (RLS) mostram a cada usuário somente os dados da própria academia.
- O professor não consegue alterar prazo de teste, status da assinatura nem a ligação com a academia.
- O app sai sozinho após 30 minutos sem uso (ajustável em `config.js`).
- Nunca envie para este repositório: chave secreta (`sb_secret_` ou `service_role`), senha do banco, e-mail ou senha de usuários, backups com dados reais de alunos.

## Direitos

© 2026 [seu nome]. Todos os direitos reservados. Repositório privado.
