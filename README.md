# Semana Robótica CPS

Site oficial da **Semana Robótica CPS**, desenvolvido com [Next.js](https://nextjs.org). Requer Node.js v18.17+.

## Requisitos

- [Node.js](https://nodejs.org/) v18.17 ou superior
- npm (incluído com o Node.js)

## Instalação e execução

**1. Clone o repositório**
```bash
git clone https://github.com/danvitoriano/semana-robotica-cps.git
cd semana-robotica-cps
```

**2. Instale as dependências**
```bash
npm install
```

**3. Inicie o servidor de desenvolvimento**
```bash
npm run dev
```

Acesse [http://localhost:3000](http://localhost:3000) no navegador para visualizar o projeto.

## Onde editar

**Configurações gerais** (tema, rotas ativas, idioma, etc.)
```
src/app/resources/config.js
```

**Conteúdo do site** (textos, links, informações exibidas nas páginas)
```
src/app/resources/content.js
```
> Para projetos com suporte a múltiplos idiomas, edite `src/app/resources/content-i18n.js`.

**Posts do blog e projetos**
```
src/app/[locale]/blog/posts/   ← posts do blog (.mdx)
src/app/[locale]/work/projects/ ← projetos (.mdx)
```

## Scripts disponíveis

| Comando | Descrição |
|---------|-----------|
| `npm run dev` | Inicia o servidor de desenvolvimento |
| `npm run build` | Gera a build de produção |
| `npm run start` | Inicia o servidor em modo produção (requer build prévia) |
| `npm run lint` | Executa o linter no código-fonte |

## Como contribuir

1. Faça um fork do repositório.
2. Crie uma branch para sua feature ou correção: `git checkout -b minha-feature`.
3. Faça commit das suas alterações: `git commit -m "feat: descrição da mudança"`.
4. Envie para o seu fork: `git push origin minha-feature`.
5. Abra um Pull Request descrevendo o que foi alterado e o motivo.

## Licença

Distribuído sob a licença CC BY-NC 4.0.
- Uso comercial não é permitido.
- É necessário dar os devidos créditos.

Consulte o arquivo `LICENSE` para mais informações.