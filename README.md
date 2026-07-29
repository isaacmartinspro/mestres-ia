# Mestres.IA — Home do portal

Home estática e responsiva do portal oficial do livro **Inteligência Artificial nos Negócios**.

## Estrutura

- `index.html` — página principal
- `assets/styles.css` — identidade visual, layout, responsividade e animações
- `assets/script.js` — menu mobile, animações e formulário demonstrativo

## Publicar no GitHub Pages

1. Crie ou abra o repositório `mestres-ia` no GitHub.
2. Envie todo o conteúdo desta pasta para a raiz do repositório.
3. No GitHub, acesse `Settings` → `Pages`.
4. Em **Build and deployment**, selecione `Deploy from a branch`.
5. Escolha a branch `main` e a pasta `/root`.
6. Clique em `Save`.
7. O GitHub publicará o site em um endereço semelhante a:
   `https://SEU-USUARIO.github.io/mestres-ia/`

## Conectar o domínio mestres.ia.br

1. Em `Settings` → `Pages`, informe `mestres.ia.br` em **Custom domain**.
2. No provedor do domínio, crie um registro CNAME:
   - Host/Nome: `www` ou o subdomínio desejado
   - Destino: `SEU-USUARIO.github.io`
3. Para usar o domínio raiz, siga os registros A indicados pelo próprio GitHub Pages.
4. Marque **Enforce HTTPS** quando o certificado estiver disponível.

## Formulário

O formulário atual é demonstrativo e não envia dados. Para ativá-lo, integre com uma ferramenta como Brevo, RD Station, Mailchimp, ConvertKit, Formspree ou uma API própria.

## Próximas páginas sugeridas

- Livro
- Autores
- Conteúdos
- Recursos
- Empresas
- Eventos
- Contato
