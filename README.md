# Barbearia D' Santos — Unidade Av. Chico Júlio

Site institucional de página única (`index.html`), autocontido (sem dependências externas além de fontes do Google), responsivo e pronto para publicação via GitHub Pages.

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
- `robots.txt` / `sitemap.xml` — indexação em buscadores
- Dados estruturados (JSON-LD `HairSalon`) embutidos no `<head>` para melhor exibição em buscas locais

## Próximos passos sugeridos

- Substituir os elementos ilustrativos em SVG por fotografias profissionais da unidade (hero e seção "Experiência D' Santos")
- Preencher os links de Instagram/Facebook no rodapé (atualmente como placeholder `#`)
- Adicionar o link oficial de agendamento online quando disponível (botão já preparado em `#agendarOnlineBtn`)
