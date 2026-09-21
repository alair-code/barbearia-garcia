# Barbearia Garcia

Site institucional estático da Barbearia Garcia, desenvolvido a partir do Template Básico de barbearias.

## Estrutura

- `index.html` — página principal.
- `estilos/style.css` — identidade visual, responsividade e acessibilidade.
- `javascript/configuracao.js` — dados do negócio, serviços, WhatsApp, endereço, horário e galeria.
- `javascript/script.js` — comportamento do menu, WhatsApp, galeria/lightbox e ano do rodapé.
- `recursos/identidade/` — logo e favicon.
- `recursos/imagens/` — imagens da galeria.
- `404.html` — página de erro personalizada.

## Como personalizar

Para reutilizar a estrutura em outra barbearia, altere primeiro:

`javascript/configuracao.js`

É possível trocar sem editar o HTML:

- nome da barbearia;
- descrição e título principal;
- WhatsApp e mensagem automática;
- endereço e localização;
- horário de atendimento;
- serviços, preços e duração;
- imagens e textos alternativos da galeria.

A identidade visual pode ser ajustada em `estilos/style.css`.

## Fluxo do produto

Este é o modelo **Básico**:

**Site → WhatsApp → cliente combina o horário com a barbearia.**

Não há banco de dados, painel administrativo, autenticação, API, pagamentos ou sistema de disponibilidade de horários.

## Validação

Com Node.js instalado, execute:

```bash
npm run check
```

O comando verifica a sintaxe dos arquivos JavaScript principais.

## Publicação

O projeto é estático e pode ser publicado em serviços como Vercel, Netlify ou GitHub Pages.

## Observação

Os dados comerciais, preços, telefone, endereço, horários e imagens devem ser conferidos antes da publicação definitiva para o cliente.
