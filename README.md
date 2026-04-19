# 🎼 HNC Treino

Visualizador e reprodutor de partituras musicais no formato MusicXML, desenvolvido para músicos que desejam estudar e praticar peças diretamente no navegador.

## ✨ Funcionalidades

- 📄 **Carregamento de partituras** — suporte a arquivos MusicXML (`.xml`, `.mxl`)
- 🎵 **Reprodução automática** — toca as notas com sincronização visual
- 🎹 **Seleção de parte** — visualize e reproduza partes instrumentais individuais
- 🌙 **Tema claro/escuro** — alternância entre modo claro (papel bege) e escuro
- 📱 **PWA (Progressive Web App)** — instalável em dispositivos móveis e desktop, com suporte offline

## 🚀 Como usar

1. Abra o aplicativo no navegador (ou instale como PWA).
2. Clique em **"Carregar Partitura"** e selecione um arquivo `.xml` ou `.mxl`.
3. Use os controles de reprodução para tocar, pausar e navegar pela partitura.
4. Para focar em um instrumento, selecione a parte desejada no seletor de partes.

## 📦 Instalação como PWA

Ao acessar o aplicativo pelo Chrome, Edge ou Safari Mobile, você verá a opção de **"Adicionar à tela inicial"** ou **"Instalar aplicativo"**. Após instalado, o HNC Treino funciona mesmo sem conexão com a internet.

## 🛠️ Tecnologias utilizadas

| Biblioteca | Função |
|---|---|
| [OpenSheetMusicDisplay](https://github.com/opensheetmusicdisplay/opensheetmusicdisplay) | Renderização de partituras MusicXML |
| [Soundfont Player](https://github.com/danigb/soundfont-player) | Síntese de áudio por soundfonts |
| [JSZip](https://stuk.github.io/jszip/) | Leitura de arquivos `.mxl` comprimidos |
| [WebAudioFont](https://github.com/surikov/webaudiofont) | Banco de sons MIDI via Web Audio API |

## 📂 Estrutura do projeto

```
hnc-treino/
├── index.html       # Aplicação principal (HTML, CSS e JS inline)
├── manifest.json    # Manifesto PWA
├── sw.js            # Service Worker (cache offline)
├── icons/
│   ├── icon-192.png # Ícone PWA 192×192
│   └── icon-512.png # Ícone PWA 512×512
└── README.md
```

## 📄 Licença

Este projeto é de uso interno do grupo HNC. Todos os direitos reservados.
