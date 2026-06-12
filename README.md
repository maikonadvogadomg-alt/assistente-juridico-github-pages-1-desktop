# assistente juridico github pages (1) — App Desktop

Aplicativo gerado pelo APK Builder para Windows, Mac e Linux.

## Como compilar

### Usando GitHub Actions (automático)
1. Suba este repositório no GitHub
2. O workflow `.github/workflows/build-desktop.yml` compila automaticamente
3. Baixe os executáveis na aba **Actions → Artifacts**

### Manualmente
```bash
npm install
npm run build
```

Os arquivos estarão em `dist/`:
- **Windows**: `assistente-juridico-github-pages--1--Setup-3.1.2.exe`
- **Mac**: `assistente-juridico-github-pages--1--3.1.2.dmg`
- **Linux**: `assistente-juridico-github-pages--1--3.1.2.AppImage`

## Requisitos
- Node.js 18+
- npm

## Gerado por
[APK Builder](https://replit.com) — Maikon Caldeira
