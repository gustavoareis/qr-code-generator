# QR Code Generator

Gerador de QR Codes dinâmico com personalização de cores, logo e download em PNG.

![Next.js](https://img.shields.io/badge/Next.js-15.3.2-black?style=flat-square&logo=nextdotjs)
![React](https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript)

## Funcionalidades

- Geração de QR Code em tempo real a partir de URLs
- Personalização de cor do QR Code e cor de fundo
- Upload de logo personalizado no centro do QR Code
- Tamanhos de logo: 24px, 38px, 50px
- Download do QR Code gerado em PNG

## Tecnologias

- [Next.js 15](https://nextjs.org/) + React 19 + TypeScript
- [qrcode.react](https://github.com/zpao/qrcode.react) — geração do QR Code
- [react-icons](https://react-icons.github.io/react-icons/) — ícones

## Instalação e uso

```bash
# Clonar repositório
git clone https://github.com/seu-usuario/qr-code-generator.git
cd qr-code-generator

# Instalar dependências
npm install

# Iniciar servidor de desenvolvimento
npm run dev
```

Acesse [http://localhost:3000](http://localhost:3000).

## Scripts

| Comando | Descrição |
|---------|-----------|
| `npm run dev` | Servidor de desenvolvimento |
| `npm run build` | Build de produção |
| `npm run start` | Executar build de produção |
| `npm run lint` | Verificar linting |

## Estrutura do projeto

```
src/
└── app/
    ├── page.tsx      # Componente principal
    ├── layout.tsx    # Layout raiz
    └── styles.css    # Estilos globais
```

## Licença

MIT
