# Ficha Municipal Interativa — versão GitHub Pages

Este pacote já está pronto para publicação no GitHub Pages.

## Opção 1 — mais simples
1. Crie um repositório no GitHub.
2. Envie todos os arquivos desta pasta para a raiz do repositório.
3. No GitHub, abra **Settings > Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` (ou `master`) e a pasta `/ (root)`.
6. Salve. O GitHub vai gerar o link do site.

## Opção 2 — com GitHub Actions já pronto
Este pacote já inclui o workflow `.github/workflows/pages.yml`.

1. Envie a pasta completa para o repositório.
2. No GitHub, abra **Settings > Pages**.
3. Em **Source**, escolha **GitHub Actions**.
4. Faça um push para `main` ou `master`.
5. O deploy será feito automaticamente.

## Arquivos importantes
- `index.html`: página principal do dashboard.
- `404.html`: fallback.
- `.nojekyll`: evita interferência do Jekyll.
- `.github/workflows/pages.yml`: deploy automático opcional.

## Observação
A base já está incorporada no HTML. Portanto, o site abre pronto após o deploy, sem depender de upload adicional.
