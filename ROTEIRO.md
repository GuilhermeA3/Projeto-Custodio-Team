# Roteiro de evolução

Marque cada etapa ao concluir.

- [ ] **1. GitHub:** conta com verificação em duas etapas, repositório **privado**, arquivos enviados
- [ ] **2. Organizar o código:** separar em arquivos e pastas (sugestão: Vite + React)
- [ ] **3. Banco de dados (Supabase):** tabelas de academias, alunos, graduações e pagamentos, com acesso separado por academia
- [ ] **4. Login:** e-mail e senha, recuperação de senha, verificação em duas etapas e bloqueio após tentativas erradas
- [ ] **5. Trocar o armazenamento:** sai o navegador, entra o banco; migrar os dados pelo backup exportado pelo app
- [ ] **6. Hospedagem:** Vercel, Netlify ou Cloudflare Pages ligados ao GitHub, com HTTPS e domínio próprio
- [ ] **7. Teste real:** 2 a 3 meses com o professor, anotando o que ele usa e o que ignora
- [ ] **8. Depois:** LGPD e termos de uso, Pix automático, relatórios, e só então CNPJ e venda

## Regras do projeto

- Nunca colocar senhas ou chaves no código; usar variáveis de ambiente
- Nunca subir backups com dados reais de alunos
- Não criar sistema próprio de criptografia ou de senha; usar o serviço de autenticação
