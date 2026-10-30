# Portfólio | Gustavo Schmitt Hatschbach

Portfólio pessoal de **Gustavo Schmitt Hatschbach**, desenvolvedor web e mobile. O site apresenta minha trajetória, tecnologias, projetos e formas de contato em uma experiência responsiva de página única.

## Conteúdo

- **Apresentação:** resumo do meu trabalho em aplicações web e Android.
- **Tecnologias:** ferramentas e linguagens com que trabalho.
- **Projetos:** demonstrações e links do Vendio e do DevCodes.
- **Sobre mim:** visão geral da minha atuação e forma de trabalho.
- **Contato:** e-mail e perfis profissionais.

## Projetos em destaque

### Vendio
Plataforma SaaS que integra ERP e e-commerce para apoiar a gestão de pequenos negócios. O portfólio apresenta o projeto como desenvolvido com Next.js, React e TypeScript.

- Aplicação: [vendiosystems.vercel.app](https://vendiosystems.vercel.app/)
- Código: [vendio-systems/vendio_frontend](https://github.com/vendio-systems/vendio_frontend)

### DevCodes
Aplicação para organizar os estudos de programação, com calendário, tarefas, anotações e biblioteca de arquivos de código. O portfólio apresenta o projeto como desenvolvido com React, Vite e Supabase.

- Repositório: [gustaaxz/devcodes](https://github.com/gustaaxz/devcodes)

## Tecnologias do portfólio

- [Astro](https://astro.build/) 7
- JavaScript e TypeScript
- HTML e CSS
- Google Fonts: Cormorant Garamond, DM Mono e DM Sans

As demonstrações visuais dos projetos Vendio e DevCodes são componentes Astro locais. Elas são mockups de apresentação; os links de acesso e código de cada projeto estão disponíveis nos respectivos blocos da página.

## Executar localmente

### Pré-requisitos

- Node.js `>=22.23.4` (versão definida em `package.json`)
- npm

### Instalação

```bash
git clone https://github.com/gustaaxz/portfolio.git
cd portfolio
npm install
```

### Desenvolvimento

No terminal, a partir da pasta do projeto:

```bash
npx astro dev --background
```

O servidor de desenvolvimento fica disponível em [http://localhost:4321](http://localhost:4321). Para administrar a instância iniciada em segundo plano:

```bash
npx astro dev status
npx astro dev logs
npx astro dev stop
```

Também é possível iniciar em primeiro plano com `npm run dev`.

### Build e pré-visualização

```bash
npm run build
npm run preview
```

O build de produção é gerado em `dist/`. O comando de pré-visualização serve esse build localmente.

## Estrutura do projeto

```text
.
├── public/
│   ├── favicon.ico
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── About.astro
│   │   ├── Contact.astro
│   │   ├── DevcodesMock.astro
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── JourneyRail.astro
│   │   ├── Project.astro
│   │   ├── Stack.astro
│   │   └── VendioMock.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

A página inicial compõe as seções a partir de `src/pages/index.astro`. Componentes reutilizáveis ficam em `src/components/`, o documento HTML e os metadados ficam em `src/layouts/Layout.astro`, e os estilos globais ficam em `src/styles/global.css`.

## Acessibilidade e movimento

As animações de entrada usam a API `IntersectionObserver`. O movimento do elemento visual e da trilha de rolagem considera a preferência do sistema por movimento reduzido (`prefers-reduced-motion`). A navegação principal usa âncoras para as seções da própria página.

## Contato

- E-mail: [contatogustavosh@gmail.com](mailto:contatogustavosh@gmail.com)
- GitHub: [@gustaaxz](https://github.com/gustaaxz)
- LinkedIn: [gustavosch](https://www.linkedin.com/in/gustavosch)

## Licença

Nenhuma licença de uso foi especificada até o momento. Entre em contato para solicitar autorização de uso ou redistribuição do conteúdo e do código deste portfólio.
