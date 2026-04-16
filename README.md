# Dashboard Amazul + AGU

## Conteúdo
- `index.html`: dashboard pronto para GitHub Pages
- `404.html`: cópia do app para compatibilidade com Pages
- `plotly.min.js` e `xlsx.full.min.js`: bibliotecas locais
- `agu_data.js`: base AGU já normalizada e restrita aos municípios da Amazônia Azul presentes na base principal
- `municipios_base_data.js` e `br_states_data.js`: geometrias locais para funcionamento sem `fetch`
- `fontes/`: planilhas originais utilizadas como referência

## Publicação no GitHub Pages
1. Substitua os arquivos atuais do repositório por este pacote.
2. Faça commit e push na branch publicada.
3. Em GitHub Pages, use a raiz do repositório e a branch principal.
4. O site abrirá por `index.html`.

## Observação
Esta versão já incorpora o bloco **Perfil de execução AGU** com:
- filtro por ano
- troca de categorização
- ranking em R$
- comparação percentual com a primeira dimensão territorial selecionada
- tabela detalhada
