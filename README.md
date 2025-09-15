# bootcamp2-chrome-ext--GSelo90-
Extensão Chrome (Manifest V3)

Extensão criada como parte do desafio do Bootcamp II.
Ela serve como base para entender conceitos de extensões Chrome usando Manifest V3, incluindo popup, background service worker e manipulação de armazenamento local.

Estrutura do Projeto
├── icons/
│   ├── icon16.png
│   ├── icon32.png
│   ├── icon48.png
│   └── icon128.png
│
├── src/
│   ├── background/
│   │   └── service_worker.js
│   │
│   └── popup/
│       ├── popup.html
│       └── popup.js
│
├── index.html
├── manifest.json
└── README.md

Instalação Manual

Para rodar a extensão no Chrome em modo de desenvolvimento:

Acesse chrome://extensions/

Ative o Modo do Desenvolvedor no canto superior direito.

Clique em "Carregar sem compactação" (Load unpacked).

Selecione a pasta do projeto.

A extensão será carregada e aparecerá na barra de ferramentas do Chrome.

