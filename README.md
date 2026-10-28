# Controle de alunos - Custódio Team

Sistema para acompanhar **mensalidades** e **graduações (cordas)** dos alunos de uma academia de Muay Thai.

> **Status:** protótipo (v0.1). Roda inteiro no navegador. Ainda não tem login nem servidor.

## O que já faz

- Mensalidades mês a mês: quem pagou, quem está atrasado e quanto falta receber
- Botão **Recebi** e cobrança por WhatsApp com mensagem pronta
- Cadastro de alunos com telefone, valor, dia de vencimento e histórico de pagamentos
- Graduações editáveis (cor da corda e ponta), com histórico de cada aluno
- Ajustes: nome da academia, valor e vencimento padrão, chave Pix, texto da cobrança e backup

## Identidade visual

O visual segue o logo da Custódio Team: vermelho, grafite e branco. O arquivo do logo está em `assets/logo-custodio-team.jpg` e uma versão leve também está embutida no `index.html`. Para trocar o nome ou a marca, edite a constante `BRAND` no começo do script.

## Como abrir

Abra o arquivo `index.html` no navegador (duplo clique). Os dados ficam salvos no próprio navegador (`localStorage`).

## Limitações atuais

- Os dados existem só no aparelho e no navegador onde foram cadastrados. Não há sincronização entre aparelhos.
- Não há login: qualquer pessoa com acesso ao aparelho vê os dados.
- Use **Ajustes > Copiar backup** com frequência.

## Roteiro

O plano de evolução (GitHub, banco de dados, login, hospedagem, Pix) está em [`docs/ROTEIRO.md`](docs/ROTEIRO.md).

## Segurança e privacidade

Nunca envie para este repositório:

- backups `.json` com dados reais de alunos
- senhas, chaves de API ou arquivos `.env`

Nome e telefone de alunos são dados pessoais e ficam sujeitos à LGPD.

## Direitos

© 2026 [seu nome]. Todos os direitos reservados. Repositório privado.
