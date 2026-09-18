# Barbearia D' Santos — Unidade Av. Chico Júlio

Site institucional de página única (`index.html`), autocontido (sem dependências externas além das fontes do Google), responsivo e pronto para publicação via GitHub Pages.

## Como publicar (GitHub Pages)

1. No repositório, vá em **Settings → Pages**.
2. Em "Build and deployment", selecione **Deploy from a branch**.
3. Escolha a branch `main` e a pasta `/ (root)`.
4. Salve. O site ficará disponível em:
   `https://otavioeleuterio2020-ctrl.github.io/barbeariadsantos/`

## Domínio próprio

Se você quiser apontar um domínio próprio (ex: barbeariadsantos.com.br):

1. Crie um arquivo `CNAME` na raiz do repositório contendo apenas o domínio, ex: `barbeariadsantos.com.br`.
2. No seu provedor de DNS, crie um registro `CNAME` apontando para `otavioeleuterio2020-ctrl.github.io`, ou registros `A` apontando para os IPs do GitHub Pages (185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153).
3. Em **Settings → Pages**, adicione o domínio customizado e ative "Enforce HTTPS" quando disponível.

## Estrutura

- `index.html` — site completo (HTML + CSS + JS embutidos)
- `assets/` — fotografias reais da unidade (extraídas dos vídeos enviados)
- `robots.txt` / `sitemap.xml` — indexação em buscadores
- Dados estruturados (JSON-LD `HairSalon`) embutidos no `<head>` para melhor exibição em buscas locais

## Próximos passos sugeridos

- Adicionar fotografias profissionais adicionais (cortes finalizados, fachada, equipe) conforme disponíveis
- Preencher o link do Instagram no rodapé (atualmente como placeholder `#`)
- Adicionar o link oficial de agendamento online quando disponível (botão "AGENDAR ONLINE" já preparado, atualmente aponta para a seção de contato)

## Segurança

Importante: o token de acesso do GitHub usado para publicar este commit foi compartilhado em texto puro em uma conversa de chat. Por padrão de segurança, esse token deve ser considerado comprometido — revogue-o em **Settings → Developer settings → Personal access tokens** e gere um novo assim que possível, mesmo que já tenha sido usado apenas para esta tarefa autorizada.
