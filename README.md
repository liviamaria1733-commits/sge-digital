# SGE Digital — Secretaria Escolar

Sistema web de emissão, registro e autenticação de documentos escolares
(certificado, histórico escolar, resultado final, declarações) com Portal do Egresso.

Projeto acadêmico — desenvolvimento de uma solução web para a secretaria de uma escola de ensino integral.

## Acessos de demonstração

| Perfil | E-mail | Senha |
|---|---|---|
| Secretaria | secretaria@escola.edu.br | 123456 |
| Gestão / Direção | gestor@escola.edu.br | 123456 |
| Administrador | admin@escola.edu.br | 123456 |
| Estudante / Egresso | ana.lima@aluno.edu.br | 123456 |

## Tecnologias

- HTML5 — estrutura das telas
- CSS3 — estilização e responsividade
- JavaScript — regras de negócio, emissão de documentos, QR Code e assinatura (SHA-256)
- qrcode-generator (CDN) — geração do QR Code de autenticidade

## Como executar

Abra o `index.html` no navegador, ou publique com GitHub Pages:

1. **Settings** → **Pages**
2. **Source**: *Deploy from a branch*
3. **Branch**: `main` · pasta `/ (root)`
4. **Save** e aguarde a publicação

Os dados da demonstração são salvos no `localStorage` do navegador.
